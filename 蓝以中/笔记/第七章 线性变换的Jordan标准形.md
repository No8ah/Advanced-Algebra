>[!summary]- **引入**
>$$第四章-\S 4 -结尾$$
>$$\quad \Downarrow \quad $$
>$$\mathscr{A}在\textcolor{pink}{\underline{\textbf{基}}}下的\textcolor{pink}{\underline{\textbf{矩阵}}}A\quad \Rightarrow \quad \textcolor{orange}{\underline{\textbf{准对角形}}}D$$
>$But$
>$$\quad \Downarrow \quad $$
>$$一般情况下 \qquad 我们做不到$$
>$Qs1:$
>$$能不能 \qquad 将\forall \ \mathscr{A} \in End(V(\mathbb{C}))化为尽可能简单的\textcolor{pink}{\underline{\textbf{矩阵}}}A呢?$$
>$$\quad \Downarrow \quad $$
>$$\textcolor{orange}{\underline{\textbf{Jordan形矩阵}}} +\textcolor{orange}{\underline{\textbf{幂零线性变换}}}$$
## 一、幂零线性变换的Jordan标准形

### 0. 引入

1. 定义(  [[幂零线性变换]]  ) #高代下/第七章/重要定义
	- $\exists \ m \in \mathbb{N}_{+} \quad S.t. \quad \mathscr{A}^{m}=0$
	2. 定义(  [[幂零矩阵]]  ) #高代下/第七章/重要定义 
		- $\exists \ m \in \mathbb{N}_{+} \quad S.t. \quad A^{m}=0$

>[!error]- **衔接**
>$$研究\qquad \textcolor{pink}{\underline{\textbf{线性变换}}}\mathscr{A}的\textcolor{orange}{\underline{\textbf{特征向量}}}和\textcolor{orange}{\underline{\textbf{特征值}}}有重要意义$$
>$$\quad \Downarrow \quad $$
>$$我们来研究 \qquad \textcolor{orange}{\underline{\textbf{幂零线性变换}}}$$
1. 命题1.1(  $\mathscr{A}是\textcolor{orange}{\underline{\textbf{幂零线性变换}}} \quad \Rightarrow \quad 2个结论$  ) #高代下/第七章/重要命题
	- **解释**
		- $只要: \qquad \mathscr{A}是\textcolor{orange}{\underline{\textbf{幂零线性变换}}}$
		- $那么:\qquad \mathscr{A}有\textcolor{red}{\underline{\textbf{唯一}}}的\textcolor{orange}{\underline{\textbf{特征值}}}\lambda_{0}=0$
	- **1个先决条件**
		1. $dim \ V( \mathbb{K})=n$
	- **2个结论**
		1. $\mathscr{A}的\textcolor{orange}{\underline{\textbf{特征多项式}}}为f(\lambda)=\lambda^{n}$
		2. $\mathscr{A}有\textcolor{red}{\underline{\textbf{唯一}}}的\textcolor{orange}{\underline{\textbf{特征值}}}\lambda_{0}=0$
### 1. 循环不变子空间

>[!summary]- **引入**
>$$研究好了\qquad \textcolor{orange}{\underline{\textbf{幂零线性变换}}}$$
>$$\quad \Downarrow \quad $$
>$$我们来研究\qquad \textcolor{orange}{\underline{\textbf{循环不变子空间}}}I(\alpha)$$

1. 引理(  $2个条件 \quad \Rightarrow \quad \alpha\ , \ \mathscr{A}\alpha \ ,\ \cdots \ , \ \mathscr{A}^{k-1}\alpha \textcolor{red}{\underline{\textbf{线性无关}}}\quad(k是\textcolor{orange}{\underline{\textbf{最小正整数}}}\quad k \geq 1)$  )
	- **2个条件**
		1. $dim \ V(\mathbb{K})=n$
		2. $\mathscr{A}是V内的一个\textcolor{orange}{\underline{\textbf{幂零线性变换}}}$
			- $\exists \ m \in N_{+}\quad S.t. \quad \mathscr{A}^{m}=\mathscr{0}$

>[!error]- **衔接**
>$$通过证明 \qquad \exists \ \min k \in \mathbb{N}_{+} \quad S.t. \quad \alpha \ , \ \mathscr{A}\alpha \ , \ \cdots \ , \ \mathscr{A}^{k-1}\alpha \textcolor{orange}{\underline{\textbf{线性无关}}}$$
>$$\quad \Downarrow \quad $$
>$$我们给出\qquad \textcolor{orange}{\underline{\textbf{循环不变子空间}}}I(\alpha)的\textcolor{pink}{\underline{\textbf{定义}}}$$
1. 定义(  [[非零向量生成的线性变换的循环不变子空间]]  )
	- $I(\alpha)=L(\alpha \ , \ \mathscr{A}\alpha \ , \ \cdots \ , \ \mathscr{A}^{k-1}\alpha)$
		1. $I(\alpha)为\mathscr{A}的一个\textcolor{orange}{\underline{\textbf{不变子空间}}}$
		2. $dim \ I(\alpha)=k$
		- **其中**
			- $\alpha \neq 0 \in V$

>[!error]- **衔接**
>$$\textcolor{orange}{\underline{\textbf{线性变换}}}\mathscr{A}在\textcolor{orange}{\underline{\textbf{基}}}\mathscr{A}^{k-1}\alpha \ , \ \cdots \ , \ \alpha下的\textcolor{pink}{\underline{\textbf{矩阵}}}A长什么样呢?$$
>$$\quad \Updownarrow \quad$$
>$$我们来研究 \qquad \mathscr{A}在\textcolor{orange}{\underline{\textbf{基}}}\mathscr{A}^{k-1}\alpha \ , \ \cdots \ , \ \alpha 下的\textcolor{pink}{\underline{\textbf{矩阵}}}A$$
>$$\quad \Downarrow \quad $$
>$$\textcolor{orange}{\underline{\textbf{Jordan形矩阵}}}J$$
1. 定义(  [[Jordan形矩阵]]  )
	 - $J=diag\{J_{1} \ , \ \cdots \ , \ J_{n}\}$
	2. 定义(  [[Jordan块]]  )
		- $J_{i}=\begin{bmatrix}0 &  1&  & 0\\ \vdots  & 0 & \ddots  & \\ \vdots  &  & \ddots  & 1\\0 & \cdots  & \cdots  &0\end{bmatrix}_{n_{i}×n_{i}}$


>[!error]- **衔接**
>$Qs:$
>$$这组\textcolor{orange}{\underline{\textbf{基}}}是否一定存在呢?$$
>$$\quad \Downarrow \quad $$
>$$\textcolor{pink}{\underline{\textbf{命题1.2}}}$$


1. 命题1.2(  $\exists \ \textcolor{orange}{\underline{\textbf{基}}} \in V \quad S.t. \quad \mathscr{A}在V的\textcolor{pink}{\underline{\textbf{基}}}下的\textcolor{pink}{\underline{\textbf{矩阵}}}A为\textcolor{red}{\underline{\textbf{Jordan形}}}J\quad \Leftrightarrow \quad  1个结论$  ) #高代下/第七章/重要命题 
	- **解释**
		- $只需:\qquad V能拆解为一些\textcolor{orange}{\underline{\textbf{循环不变子空间}}}的\textcolor{orange}{\underline{\textbf{直和}}}$
		- $那么: \qquad 我们就能找到这组\textcolor{orange}{\underline{\textbf{基}}}$
	- **1个先决条件**
		1. $\mathscr{A}是\dim V (\mathbb{K})=n上的一个\textcolor{orange}{\underline{\textbf{幂零线性变换}}}$
	- **1个结论**
		1. $V= I(\alpha_{1}) \oplus \cdots \oplus I(\alpha_{s})$
### 2. 幂零线性变换的Jordan标准形

1. 命题1.3(  $2个条件\quad \Rightarrow \quad 2个结论$  )
	- **2个条件**
		1. $\bar{\alpha}=\alpha+M为\bar{V}=V / M中的一个\textcolor{orange}{\underline{\textbf{非零元素}}}$
		2. $I(\bar{\alpha})为\mathscr{A}在\bar{V}内\textcolor{pink}{\underline{\textbf{诱导变换}}}的一个k维\textcolor{orange}{\underline{\textbf{循环不变子空间}}}$
			- $I(\alpha)=L(\alpha \ , \ \mathscr{A}\alpha \ , \ \cdots \ , \ \mathscr{A}^{k}\alpha) \quad (\mathscr{A}^{k}\alpha \in M)$
	- **2个结论**
		1. $I(\alpha)为\mathscr{A}在V内的一个k+1维\textcolor{orange}{\underline{\textbf{循环不变子空间}}}$
			- $I(\alpha)=L(\alpha,\mathscr{A} \ , \ \cdots \ , \ \mathscr{A}^{k}\alpha)$
		2. $\mathscr{A}^{k}\alpha \in M$
1. 命题1.4(  $\mathscr{A}是\textcolor{orange}{\underline{\textbf{幂零线性变换}}}\quad \Rightarrow \quad \exists \ \textcolor{orange}{\underline{\textbf{基}}} \in V \quad S.t. \quad \mathscr{A}在V的\textcolor{pink}{\underline{\textbf{基}}}下的\textcolor{pink}{\underline{\textbf{矩阵}}}A为\textcolor{red}{\underline{\textbf{Jordan形}}}J$  ) #高代下/第七章/重要命题 
	- **解释**
		- $只需: \qquad \mathscr{A}是\textcolor{orange}{\underline{\textbf{幂零线性变换}}}$
		- $那么:\qquad 我们就能找到\textcolor{orange}{\underline{\textbf{基}}}\quad S.t. \quad \mathscr{A}在\textcolor{pink}{\underline{\textbf{基}}}下的\textcolor{pink}{\underline{\textbf{矩阵}}}A为\textcolor{orange}{\underline{\textbf{Jordan形}}}$
	- **1个先决条件**
		1. $dim \ V(\mathbb{K})=n$
3. 定义(  [[循环幂零线性变换]]  ) #高代下/第七章/重要定义 
	- $\mathscr{A}^{n-1}\neq 0 \quad but\quad \mathscr{A}^{n}=0$
		- $\textcolor{orange}{\underline{\textbf{注意}}} \quad k=n \in \mathbb{N}_{+}$
		- $必定\exists \ \alpha \in V \quad S.t. \quad \mathscr{A}^{n-1}\alpha \neq 0 \quad but \quad \mathscr{A}^{n}\alpha=0$
	1. 定义(  [[循环基]]  ) #高代下/第七章/重要定义 
		- $\mathscr{A}^{n-1}\alpha \ , \  \cdots \ , \  \alpha$
			- $\textcolor{orange}{\underline{\textbf{循环幂零线性变换}}}\mathscr{A}在\textcolor{orange}{\underline{\textbf{循环基}}}下的\textcolor{pink}{\underline{\textbf{矩阵}}}A为\textcolor{orange}{\underline{\textbf{Jordan形}}}J$
			- $J=\begin{bmatrix}0 & 1 &  & \\& 0 & \ddots  & \\&  & \ddots  &  1\\&  &  & 0\end{bmatrix}_{n×n}$

>[!error]- **衔接**
>$$这个\textcolor{orange}{\underline{\textbf{Jordan形}}}有什么性质呢?$$

1. $\textcolor{red}{\underline{\textbf{n阶}}}\textcolor{orange}{\underline{\textbf{Jordan形}}}的性质$
	- $JA \quad \Leftrightarrow \quad 将A \textcolor{orange}{\underline{\textbf{向上平移1行}}}$
	- $if \quad k \geq n \quad \Rightarrow \quad J^{k}=0 \quad \Leftrightarrow \quad 将E \textcolor{orange}{\underline{\textbf{向上平移k行}}}$
## 二、一般线性变换的Jordan标准形

>[!summary]- **引入**
>$$\textcolor{pink}{\underline{\textbf{线性空间}}}(\mathbb{C})内\forall \ \textcolor{orange}{\underline{\textbf{线性变换}}}\mathscr{A}的\textcolor{orange}{\underline{\textbf{Jordan形}}}J长什么样呢?$$

### 1. Jordan块与Jordan形

1. 定义(  [[Jordan块]]  )
	- $J=\begin{bmatrix}\lambda_{0} & 1 &  & 0\\  & \lambda_{0} & \ddots & \\   &   & \ddots & 1\\0 &   &  & \lambda_{0}\end{bmatrix}_{n×n}$
	- **特别地**
		- $n=1时\quad \Rightarrow \quad J=\lambda_{0}$
		- $if \quad J是上述Jordan块\quad \Rightarrow \quad J有\textcolor{orange}{\underline{\textbf{唯一}}}的\textcolor{orange}{\underline{\textbf{特征值}}}\lambda_{0}(n重根)$ 
1. 定义(  [[Jordan形矩阵]]  )
	- $J=diag \{J_{1}\ , \ \cdots \ , \ J_{s}\}$
	- **其中**
		- $J_{i}=\begin{bmatrix}\lambda_{i} & 1 &  & 0\\  & \lambda_{i} & \ddots & \\   &   & \ddots & 1\\0 &   &  & \lambda_{i}\end{bmatrix}_{n_{i}×n_{i}} \quad (i=1\ , \ 2\ , \ \cdots \ , \ s)$
		- $J的\textcolor{orange}{\underline{\textbf{特征值}}}为\lambda_{i}(n_{i}重根) \quad i=1 \ , \ 2\ , \ \cdots \ , \ s$

>[!error]- **衔接**
>$\S1中:$
>$$\lambda_{i}=0 \quad (i=1\ , \ 2\ , \ \cdots \ , \ s)$$
>$$\quad \Updownarrow \quad$$
>$$特殊情况$$
>$$\quad \Downarrow \quad $$
>$Qs1:$
>$$对于\qquad \forall \ \textcolor{orange}{\underline{\textbf{特征值}}}呢?$$
>$$\quad \Downarrow \quad $$
>$$可以归结为上述情况吗?$$
>$Qs2:$
>$$对于\qquad \forall \ \mathscr{A} \in End(V(\mathbb{C}))$$
>$$\quad \Downarrow \quad $$
>$$可以\qquad 归结为\textcolor{orange}{\underline{\textbf{幂零线性变换}}}吗?$$
>$$\quad \Updownarrow \quad$$
>$$能不能\qquad \textcolor{orange}{\underline{\textbf{找出一组基}}}\quad S.t. \quad \mathscr{A}在\textcolor{pink}{\underline{\textbf{基}}}下的\textcolor{pink}{\underline{\textbf{矩阵}}}A是\textcolor{orange}{\underline{\textbf{Jordan形矩阵}}}J呢?$$
>$$\quad \Downarrow \quad $$
>$$\S2-2.Jordan标准形的存在性$$
### 2. Jordan标准形的存在性

>[!summary]- **引入**
>$$首先 \qquad 我们对\mathscr{A} \in End(V(\mathbb{K}))进行讨论 \quad (\forall \ \mathbb{K})$$

1. 命题2.1(  $if \quad \exists \ \lambda_{0}\in \mathbb{K} \quad S.t. \quad \mathscr{A}-\lambda_{0}\mathscr{E}是\textcolor{orange}{\underline{\textbf{幂零线性变换}}} \quad \Rightarrow \quad 1个结论$  )
	- **解释**
		- $实际: \qquad \S1-1.-命题1.4$
		- $本质: \qquad 为了将\forall \ \mathscr{A} \in End(V(\mathbb{C}))归结为\textcolor{orange}{\underline{\textbf{幂零线性变换}}}$
		- $只需: \qquad \textcolor{orange}{\underline{\textbf{找到}}}\lambda_{0} \in \mathbb{K} \quad S.t. \quad \mathscr{A}-\lambda_{0} \mathscr{E}是 \textcolor{orange}{\underline{\textbf{幂零线性变换}}}$
		- $那么: \qquad 就能\textcolor{orange}{\underline{\textbf{找到基}}} \quad S.t. \quad \forall \ \mathscr{A}的\textcolor{pink}{\underline{\textbf{矩阵}}}A为\textcolor{orange}{\underline{\textbf{Jordan标准形}}}J了$
	- **1个先决条件**
		- $\mathscr{A}\in End(V(\mathbb{K}))$
	- **1个结论**
		- $\exists \ \textcolor{orange}{\underline{\textbf{基}}} \in V \quad S.t. \quad \mathscr{A}在这组\textcolor{pink}{\underline{\textbf{基}}}下的\textcolor{pink}{\underline{\textbf{矩阵}}}A为\textcolor{red}{\underline{\textbf{Jordan标准形}}}J$

>[!error]- **衔接**
>$$为了\qquad 更好地研究\mathscr{B}=\mathscr{A}-\lambda_{0}\mathscr{E}$$
>$$\quad \Downarrow \quad $$
>$$我们给出\qquad \textcolor{orange}{\underline{\textbf{子空间序列}}}的定义$$
1. 定义(  [[子空间序列]]  )
	- $M_{i}=Ker \mathscr{B}^{i} \quad i=1\ , \ 2\ , \ \cdots$
	- $N_{i}=Im \mathscr{B}^{i} \quad i=1 \ , \ 2\ , \ \cdots$

>[!error]- **衔接**
>$$那么\qquad 这个\textcolor{orange}{\underline{\textbf{子空间序列}}}有什么性质呢?$$

- **子空间序列的3个性质**
	1. 性质1(  包含性质  )			
		1. $\{0\}=M_{0} \subseteq M_{1} \subseteq M_{2} \subseteq \cdots$
		2. $V = N_{0} \supseteq N_{1} \supseteq N_{2} \supseteq \cdots$
	3. 性质2(  直和性质  )
		1. $\dim M_{i} +\dim N_{i} =n \quad n=0\ , \ 1\ , \ 2\ , \ \cdots$
	4. 性质3(  最小性质  )
		1. $M_{0} \subset M_{1} \subset \cdots \subset M_{k} =M_{k+1} =\cdots$
		1. $N_{0} \supset N_{1} \supset \cdots \supset N_{k}=N_{k+1} = \cdots$
	5. 性质4(  分解性质  )
		1. $V=M_{k} \oplus N_{k} \quad \forall \ \textcolor{pink}{\underline{\textbf{上述}}}的k$
		- **其中**
			1. $M_{k}与N_{k}均是\mathscr{A}的\textcolor{orange}{\underline{\textbf{不变子空间}}}$

>[!error]- **衔接**
>$$利用\qquad \textcolor{orange}{\underline{\textbf{子空间序列}}}的性质$$
>$$\quad \Downarrow \quad $$
>$$可以\qquad 将大空间V拆解为2个\textcolor{orange}{\underline{\textbf{不变子空间序列}}}的\textcolor{orange}{\underline{\textbf{直和}}}$$
>$并且$
>$$\mathscr{B}|{M_{k}}为\textcolor{orange}{\underline{\textbf{幂零线性变换}}}$$
>$$利用\qquad \textcolor{pink}{\underline{\textbf{命题2.1}}}$$
>$$\quad \Downarrow \quad $$
>$$可以利用\qquad \textcolor{orange}{\underline{\textbf{数学归纳法}}}研究\forall \ \mathscr{A} \in End(V(\mathbb{C}))了$$
>$由于$
>$$\textcolor{orange}{\underline{\textbf{不变子空间}}}\quad 与 \quad \mathscr{A}的\textcolor{orange}{\underline{\textbf{特征值}}}与\textcolor{orange}{\underline{\textbf{特征向量}}}联系密切$$
>$$\quad \Downarrow \quad $$
>$$\textcolor{pink}{\underline{\textbf{命题2.2}}}$$


1. 命题2.2(  $1个条件 \quad \Rightarrow \quad \exists \ \textcolor{orange}{\underline{\textbf{基}}}\in V \quad S.t. \quad \mathscr{A}在这组\textcolor{pink}{\underline{\textbf{基}}}下的\textcolor{pink}{\underline{\textbf{矩阵}}}A为\textcolor{red}{\underline{\textbf{Jordan标准形}}}J$  ) #高代下/第七章/重要命题 
	- $判断\mathscr{A}在\textcolor{pink}{\underline{\textbf{基}}}下的\textcolor{pink}{\underline{\textbf{矩阵}}}A是否为\textcolor{orange}{\underline{\textbf{Jordan标准形}}}J的重要命题$
	- $\S2-2.-命题2.1-简化条件版本$
	- **解释**
		- $只需: \qquad \mathscr{A}的\textcolor{orange}{\underline{\textbf{特征多项式}}}的\textcolor{orange}{\underline{\textbf{根}}}\textcolor{red}{\underline{\textbf{都在}}}\mathbb{K}内$
		- $那么: \qquad 就能\textcolor{orange}{\underline{\textbf{找到}}}这组\textcolor{pink}{\underline{\textbf{基}}}$
		- $并且:\qquad \mathscr{A}在\textcolor{pink}{\underline{\textbf{基}}}下的\textcolor{pink}{\underline{\textbf{矩阵}}}A\textcolor{orange}{\underline{\textbf{为}}}\textcolor{red}{\underline{\textbf{Jordan标准形}}}J$
		- **总结**
			1. $求出\mathscr{A}在\textcolor{pink}{\underline{\textbf{基}}}下的\textcolor{pink}{\underline{\textbf{矩阵}}}A$
			2. $求出f(\lambda)=|\lambda \cdot E - A|=0 的\textcolor{orange}{\underline{\textbf{零点}}}$
			4. $判断\textcolor{orange}{\underline{\textbf{这些零点}}}是否\textcolor{red}{\underline{\textbf{都在}}}\mathbb{K}内$
				- $if \quad OK \quad \Rightarrow \quad A\textcolor{orange}{\underline{\textbf{能化为}}}\textcolor{red}{\underline{\textbf{Jordan标准形}}}J$
				- $if \quad NOT \quad \Rightarrow \quad A \textcolor{orange}{\underline{\textbf{不能化为}}}\textcolor{red}{\underline{\textbf{Jordan标准形}}}J$
	- **1个先决条件**
		- $\mathscr{A} 是\dim V(\mathbb{K}) = n内的\textcolor{orange}{\underline{\textbf{线性变换}}}$
			- $\mathscr{A} \in End(V(\mathbb{K}))$
	- **1个条件**
		- $f(\lambda)=|\lambda E-A|的\textcolor{orange}{\underline{\textbf{根}}}\textcolor{red}{\underline{\textbf{全属于}}}\mathbb{K}$
	- **其中**
		1. $J=diag(J_{1} \ , \ \cdots \ , \ J_{s})$
			- $\mathscr{A}的\textcolor{orange}{\underline{\textbf{Jordan标准形}}}$
		2. $J_{i}为\textcolor{orange}{\underline{\textbf{Jordan块}}}\quad (\textcolor{pink}{\underline{\textbf{复数域}}}\mathbb{C}上的)(i \in \mathbb{N}_{+})$
	- **小推论**
		- $when \ \ \mathbb{K}=\mathbb{C}\ \ 时$
			- $\mathscr{A}在\mathbb{C}下的\textcolor{pink}{\underline{\textbf{矩阵}}}A \textcolor{red}{\underline{\textbf{一定}}}能\textcolor{orange}{\underline{\textbf{化为}}}\textcolor{red}{\underline{\textbf{Jordan标准形}}}J$
	- **小推论**
		- $when \ \ \mathbb{K} \neq \mathbb{C}\ \ 时$
			- $\mathscr{A}在\mathbb{K}下的\textcolor{pink}{\underline{\textbf{矩阵}}}A \textcolor{red}{\underline{\textbf{不一定}}}能\textcolor{orange}{\underline{\textbf{化为}}}\textcolor{red}{\underline{\textbf{Jordan标准形}}}J$
### 3. Jordan标准形的唯一性

>[!summary]- **引入**
>$$if \quad \mathscr{A} \in End(V(\mathbb{K}))下的\textcolor{pink}{\underline{\textbf{矩阵}}}A\textcolor{orange}{\underline{\textbf{可以化为}}}\textcolor{red}{\underline{\textbf{Jordadn标准形}}}J$$
>$Qs:$
>$$这个\textcolor{orange}{\underline{\textbf{Jordan标准形}}}J是\textcolor{orange}{\underline{\textbf{唯一}}}的吗?$$
>$$\quad \Downarrow \quad $$
>$$我们来研究\qquad \textcolor{orange}{\underline{\textbf{子空间序列}}}与\textcolor{orange}{\underline{\textbf{幂零线性变换}}}\mathscr{B}的\textcolor{orange}{\underline{\textbf{矩阵}}}B之间的关系$$
>$$\quad \Downarrow \quad $$
>$$\textcolor{pink}{\underline{\textbf{命题2.3}}}$$


1. 命题2.3(  $\dim M_{i}=n-r(B^{i})$  )
	- **解释**
		- $为了: \qquad 在\textcolor{pink}{\underline{\textbf{命题2.4}}}中更好地进行计算$
	- **其中**
		1. $i=0,1\ , \ \cdots$
		2. $r(B^{i})表示B^{i}的\textcolor{pink}{\underline{\textbf{秩}}}$
		3. $B=A- \lambda_{0}E$
3. 命题2.4(  $3个条件\quad \Rightarrow \quad 1个结论$  )  #高代下/第七章/重要命题 
	- $求解\mathscr{A}的\textcolor{orange}{\underline{\textbf{Jordan形}}}J的命题$
	- **解释**
		- $只需: \qquad \mathscr{A}的\textcolor{orange}{\underline{\textbf{特征多项式}}}的\textcolor{orange}{\underline{\textbf{根}}}\textcolor{red}{\underline{\textbf{全属于}}}\mathbb{K}$
		- $那么: \qquad \textcolor{orange}{\underline{\textbf{Jordan块}}}J_{i}的计算方法就能给出\quad i=1\ , \ 2\ , \ \cdots \ , \ s$
		- $也就是说: \qquad \textcolor{orange}{\underline{\textbf{Jordan块}}}J_{i}由\textcolor{orange}{\underline{\textbf{子空间序列}}}M_{i}\textcolor{red}{\underline{\textbf{唯一决定}}}$
			- $与\textcolor{orange}{\underline{\textbf{基的选取}}}\textcolor{red}{\underline{\textbf{无关}}}$
	- **3个条件**
		1. $\mathscr{A}\in End(V(\mathbb{K}))$
		2. $\mathscr{A}的\textcolor{orange}{\underline{\textbf{特征多项式}}}的\textcolor{orange}{\underline{\textbf{根}}}\textcolor{red}{\underline{\textbf{全属于}}}\mathbb{K}$
			- $保证了\textcolor{orange}{\underline{\textbf{能找到一组基}}}\quad S.t. \quad \mathscr{A}在\textcolor{pink}{\underline{\textbf{基}}}下的\textcolor{pink}{\underline{\textbf{矩阵}}}A为\textcolor{orange}{\underline{\textbf{Jordan标准形}}}J$
			- $\textcolor{pink}{\underline{\textbf{命题2.2}}}$
		1. $J是\mathscr{A}的\textcolor{orange}{\underline{\textbf{任一}}}\textcolor{orange}{\underline{\textbf{Jordan标准形}}}$
	- **1个结论**
		1. $\forall \ \lambda_{0} \quad  2\dim M_{l}-\dim M_{l+1} - \dim M_{l-1}=\cdots$
			- $\lambda_{0}是\mathscr{A}的\textcolor{orange}{\underline{\textbf{特征值}}}$
			- $r(B^{l+1})+r(B^{l-1})-2r(B^{r})= \cdots$
		1. $\cdots = J中以\lambda_{0}为\textcolor{orange}{\underline{\textbf{特征值}}}\quad 且 \quad \textcolor{orange}{\underline{\textbf{阶为l}}}的\textcolor{orange}{\underline{\textbf{Jordan块的个数}}}$
	- **推论**
		1. $\mathscr{A}的\textcolor{orange}{\underline{\textbf{Jordan标准形}}}J\ , \ if \quad 不计\textcolor{pink}{\underline{\textbf{主对角线}}}上的\textcolor{orange}{\underline{\textbf{Jordan块}}}J_{i}的\textcolor{orange}{\underline{\textbf{排列次序}}}\quad \Rightarrow \quad J是\textcolor{red}{\underline{\textbf{唯一的}}}$
		2. $2个条件 \quad \Rightarrow \quad \mathscr{A}的\textcolor{orange}{\underline{\textbf{Jordan标准形}}}J中以\lambda_{0}为\textcolor{orange}{\underline{\textbf{特征值}}}的\textcolor{orange}{\underline{\textbf{l阶}}}\textcolor{orange}{\underline{\textbf{Jordan块}}}J_{i}的\textcolor{red}{\underline{\textbf{个数}}}为r(B^{l+1})+r(B^{l-1})-2r(B^{l})$ #高代下/第七章/重要推论
			- **2个条件**
				1. $\mathscr{A}在\textcolor{pink}{\underline{\textbf{某一组基}}}下的\textcolor{pink}{\underline{\textbf{矩阵}}}为A$
				2. $\lambda_{0}是\mathscr{A}的\textcolor{orange}{\underline{\textbf{任一特征值}}}$
			- **其中**
				- $B=A-\lambda_{0}E$

>[!error]- **衔接**
>$$将上面的结果综合起来$$
>$$\quad \Downarrow \quad $$
>$$\textcolor{pink}{\underline{\textbf{定理2.1}}}$$


1. 定理2.1(  $1个条件\quad \Rightarrow \quad \exists \ \textcolor{orange}{\underline{\textbf{基}}}\quad S.t. \quad \mathscr{A}在\textcolor{pink}{\underline{\textbf{这组基}}}下的\textcolor{pink}{\underline{\textbf{矩阵}}}A为\textcolor{orange}{\underline{\textbf{Jordan形}}}J$  )
	- $判断\mathscr{A}的\textcolor{pink}{\underline{\textbf{矩阵}}}A \textcolor{orange}{\underline{\textbf{能化为}}}\textcolor{red}{\underline{\textbf{Jordan标准形}}}J的定理$
	- **解释**
		- $只需: \qquad \mathscr{A}的\textcolor{orange}{\underline{\textbf{特征多项式}}}的\textcolor{orange}{\underline{\textbf{根}}}\textcolor{red}{\underline{\textbf{全属于}}}\mathbb{K}$
		- $那么:\qquad 就能\textcolor{orange}{\underline{\textbf{找到一组基}}}\quad S.t. \quad \mathscr{A}在\textcolor{pink}{\underline{\textbf{基}}}下的\textcolor{pink}{\underline{\textbf{矩阵}}}A为\textcolor{orange}{\underline{\textbf{Jordan标准形}}}J$
	- **1个先决条件**
		1. $\mathscr{A} \in End(V)$
	- **1个条件**
		1. $\mathscr{A}的\textcolor{orange}{\underline{\textbf{特征多项式}}}的\textcolor{orange}{\underline{\textbf{根}}}\textcolor{red}{\underline{\textbf{全属于}}}\mathbb{K}$
	- **其中**
		- $除了主对角线上Jordan块J_{i}的排序\textcolor{pink}{\underline{\textbf{可以不同}}}外\ , \ J由\mathscr{A}\textcolor{red}{\underline{\textbf{唯一决定}}}$
		- $J_{i}=\begin{bmatrix}\lambda_{i} & 1 &  & 0\\  & \lambda_{i} & \ddots & \\   &   & \ddots & 1\\0 &   &  & \lambda_{i}\end{bmatrix}_{n_{i}×n_{i}} \quad (i=1\ , \ 2\ , \ \cdots \ , \ s)$
	- **小推论**
		- **1个条件**
			1. $\forall \  \textcolor{orange}{\underline{\textbf{基}}} \quad S.t. \quad  \mathscr{A}的\textcolor{pink}{\underline{\textbf{矩阵}}}A \textcolor{red}{\underline{\textbf{都不为}}}\textcolor{orange}{\underline{\textbf{Jordan形}}}J$
		- **1个结论**
			1. $\exists \ \lambda_{0} \notin \mathbb{K} \quad S.t. \quad f(\lambda_{0})=0$
		- **其中**
			1. $f(\lambda)是\mathscr{A}的\textcolor{orange}{\underline{\textbf{特征多项式}}}$

>[!error]- **衔接**
>$$由于\qquad \textcolor{pink}{\underline{\textbf{矩阵论}}}\quad \Leftrightarrow \quad \textcolor{pink}{\underline{\textbf{线性映射}}}的语言$$
>$$\quad \Updownarrow \quad$$
>$$\textcolor{orange}{\underline{\textbf{线性变换}}}\mathscr{A}在\textcolor{orange}{\underline{\textbf{不同基}}}下的\textcolor{pink}{\underline{\textbf{矩阵}}}是\textcolor{red}{\underline{\textbf{相似}}}的$$
>$$\quad \Downarrow \quad $$
>$$\textcolor{pink}{\underline{\textbf{定理2.2}}}(\textcolor{pink}{\underline{\textbf{矩阵论}}}的语言)$$
1. 定理2.2(  $1个条件 \quad \Rightarrow \quad A(\mathbb{K}) \sim \textcolor{orange}{\underline{\textbf{Jordan形}}}J$  )
	- $判断A 是否 \textcolor{orange}{\underline{\textbf{相似于}}}\textcolor{red}{\underline{\textbf{Jordan标准形}}}J的定理$
	- **解释**
		- $只需:\qquad A的\textcolor{orange}{\underline{\textbf{特征多项式}}}的\textcolor{orange}{\underline{\textbf{根}}}\textcolor{red}{\underline{\textbf{全属于}}}\mathbb{K}$
		- $那么:\qquad A就\textcolor{orange}{\underline{\textbf{相似}}}于\textcolor{orange}{\underline{\textbf{Jordan标准形}}}J$
		- $也就是说: \qquad   A可以化为\textcolor{orange}{\underline{\textbf{准对角形}}}$
	- **1个先决条件**
		1. $A \in M_{n}(\mathbb{K})$
	- **1个条件**
		1. $A的\textcolor{orange}{\underline{\textbf{特征多项式的根}}}\textcolor{red}{\underline{\textbf{全属于}}}\mathbb{K}$
	- **其中**
		- $除了主对角线上Jordan块J_{i}的排序\textcolor{pink}{\underline{\textbf{可以不同}}}外\ , \ J由A \textcolor{red}{\underline{\textbf{唯一决定}}}$
		- $J_{i}=\begin{bmatrix}\lambda_{i} & 1 &  & 0\\  & \lambda_{i} & \ddots & \\   &   & \ddots & 1\\0 &   &  & \lambda_{i}\end{bmatrix}_{n_{i}×n_{i}} \quad (i=1\ , \ 2\ , \ \cdots \ , \ s)$
	- **小推论**
		- $when \ \ \mathbb{K}=\mathbb{C}\ \ 时$
			- $\forall \ A \in M_{n}(\mathbb{C})总是满足条件$
	- 定义(  [[A的Jordan形]]  )
		- $A \sim J= diag \{J_{1} \ , \ \cdots \ , \  J_{s}\}$

>[!attention]- **总结**
>$$完全解决了\qquad \mathbb{C}上\textcolor{orange}{\underline{\textbf{线性变换}}}\mathscr{A}和\textcolor{orange}{\underline{\textbf{复矩阵}}}A的\textcolor{orange}{\underline{\textbf{标准形}}}的问题$$
### 4. Jordan标准形的计算方法

>[!summary]- **引入**
>$那么:$
>$$给定\qquad \mathscr{A} \in End(V)$$
>$$如何计算\qquad \mathscr{A}的\textcolor{orange}{\underline{\textbf{Jordan标准形}}}J呢?(假设J存在)$$
>$$\quad \Updownarrow \quad$$
>$$\S2-3.-\textcolor{pink}{\underline{\textbf{命题2.4}}}-推论$$


- 计算$\mathscr{A}的Jordan标准形J$
- 计算步骤
	- 条件
		1. $给定\mathscr{A} \in End(V)$
		2. 给定$A \in M_{n}(\mathbb{K})$
	1. $计算\mathscr{A}在V的\textcolor{pink}{\underline{\textbf{基}}}\xi_{1} \ , \ \cdots \ , \ \xi_{n}下的矩阵A \quad (if \quad 给定A \ , \ 则可省去该步骤)$
	2. $求出A的\textcolor{orange}{\underline{\textbf{全部不同特征值}}}\lambda_{1}\ , \ \cdots \ , \ \lambda_{t} \quad if \quad \lambda_{i} \in \mathbb{K}$
	3. $\forall \ \lambda_{i}  \quad  令 B=A - \lambda_{i}E$
		- $利用公式r(B^{l+1})+r(B^{l-1})-2r(B^{l})=右式 \quad l=1\ , \ 2\ , \ \cdots$
		- $右式=以\lambda_{i}为\textcolor{orange}{\underline{\textbf{特征值}}}\ , \ \textcolor{orange}{\underline{\textbf{阶}}}为l的Jordan块J_{i}的\textcolor{red}{\underline{\textbf{个数}}}$
	4. $将获得的Jordan块J_{i}按\textcolor{orange}{\underline{\textbf{任意次序排列}}}成Jordan形J=diag \{J_{1}\ , \ \cdots \ , \ J_{s}\}$
## 三、最小多项式

> [!summary]- 引入
> $$使用\textcolor{orange}{\underline{\textbf{多项式}}}研究\textcolor{pink}{\underline{\textbf{线性变换}}}\mathscr{A}或者\textcolor{pink}{\underline{\textbf{矩阵}}}A$$
### 1. 方阵的化零多项式

1. 定义(  [[方阵的化零多项式]]  )
	- $g(x)$

>[!error]- **衔接**
>$$给定一个\qquad m次多项式g(x)$$
>$$\quad \Downarrow \quad $$
>$$如何判断\qquad g(x)是\textcolor{orange}{\underline{\textbf{化零多项式}}}呢?$$
>$$\quad \Downarrow \quad $$
>$$\textcolor{pink}{\underline{\textbf{命题3.1}}}$$


1. 命题3.1(  $g(x)是J的\textcolor{orange}{\underline{\textbf{化零多项式}}}\quad \Leftrightarrow \quad 2个充分条件$  )
	 - $判断g(x)是否是J的\textcolor{orange}{\underline{\textbf{化零多项式}}}的命题$
	- **解释**
		- $只需： \qquad 判断\lambda_{0}的\textcolor{orange}{\underline{\textbf{重数}}}是否 \geq J的\textcolor{orange}{\underline{\textbf{阶数}}}n$
		- $那么: \qquad 就能判断g(x)是不是J的\textcolor{orange}{\underline{\textbf{化零多项式}}}$
		- $if \quad OK \quad \Rightarrow \quad g(x) \textcolor{orange}{\underline{\textbf{是}}}J的\textcolor{orange}{\underline{\textbf{化零多项式}}}$
		- $if \quad NOT  \quad \Rightarrow \quad g(x)\textcolor{orange}{\underline{\textbf{不是}}}J的\textcolor{orange}{\underline{\textbf{化零多项式}}}$
	- **2个先决条件**
		1. $给定\mathbb{K}上的\textcolor{orange}{\underline{\textbf{Jordan形矩阵}}}J$
		2. $g(x)是\mathbb{K}上的一个\textcolor{orange}{\underline{\textbf{m次多项式}}}$
	- **2个充分条件**
		1. $\lambda_{0}是g(x)的一个\textcolor{orange}{\underline{\textbf{零点}}}$
			- $g(\lambda_{0})=0$
		2. $\lambda_{0}的\textcolor{orange}{\underline{\textbf{重数}}} \geq J的\textcolor{orange}{\underline{\textbf{阶数}}}n$

>[!error]- **衔接**
>$$是否\qquad 还有其他方法判断f(x)是不是\textcolor{orange}{\underline{\textbf{化零多项式}}}呢?$$
>$$\quad \Downarrow \quad $$
>$$\textcolor{pink}{\underline{\textbf{Hamilton-Cayley}}}定理$$
1. [[Hamilton-Cayley定理]](  $f(\lambda)=|\lambda E -A| \quad \Rightarrow \quad f(A)=0$  )
	- $判断f(x)是否是的\textcolor{orange}{\underline{\textbf{化零多项式}}}的定理$
	- **解释**
		- $只需:\qquad f(\lambda)是A的\textcolor{orange}{\underline{\textbf{特征多项式}}}$
		- $那么:\qquad f(\lambda)是A的\textcolor{orange}{\underline{\textbf{化零多项式}}}$
	- **2个先决条件**
		1. $A \in M_{n}(\mathbb{K})$
		2. $f(\lambda)=|\lambda E-A|是A的\textcolor{orange}{\underline{\textbf{特征多项式}}}$
	- **小推论**
		- $\forall \ A \in M_{n}(\mathbb{K})必定有\textcolor{orange}{\underline{\textbf{首项系数}}}=1的\textcolor{orange}{\underline{\textbf{n次化零多项式}}}$
	- **小推论**
		- $\forall \ A^{n} \in M_{n}(\mathbb{K})可以由E \ , \ A \ , \ \cdots \ , \ A^{n-1}\textcolor{orange}{\underline{\textbf{线性表示}}}$

>[!attention]- **引出问题**
>$$E \ , \ A \ , \  \cdots \ , \ A^{n-1}是否还有\textcolor{pink}{\underline{\textbf{某个}}}A^{k}可被它前面的向量\textcolor{orange}{\underline{\textbf{线性表示}}}?$$
### 2. 方阵的最小多项式

1. 定义(  [[方阵的最小多项式]]  )
	- $\varphi(x)是A的\textcolor{orange}{\underline{\textbf{最小多项式}}}$
	- **3个条件**
		1. $\textcolor{orange}{\underline{\textbf{化零多项式}}}$
			- $\varphi(A)=0$
		2. $\textcolor{orange}{\underline{\textbf{首项系数}}}=1$
			- $\varphi(x)= 1 \cdot x^{k} + a_{1} \cdot x^{k-1} + \cdots$
		3. $\textcolor{orange}{\underline{\textbf{次数}}}\textcolor{red}{\underline{\textbf{最低}}}$
	- **性质**
		1. $\varphi(x)\textcolor{pink}{\underline{\textbf{系数}}} \in \mathbb{K}$
		2. $\varphi(x)的\textcolor{orange}{\underline{\textbf{首项系数}}}=1$
		3. $\varphi(A)=0$
		4. $if \quad \exists \ \textcolor{orange}{\underline{\textbf{非零多项式}}}g(x) \in \mathbb{K} \quad S.t. \quad g(A)=0 \quad \Rightarrow \quad \deg g(x) \geq \deg \varphi(x)$

> [!note]- **引出问题**
> 事实:
> $$A的\textcolor{orange}{\underline{\textbf{最小多项式 }}}\textcolor{pink}{\underline{\textbf{存在}}}$$
> 一、
> $$\textcolor{pink}{\underline{\textbf{最小多项式}}}是否\textcolor{orange}{\underline{\textbf{唯一}}}?$$
> 二、
> $$如何\textcolor{orange}{\underline{\textbf{求出}}}\textcolor{pink}{\underline{\textbf{最小多项式}}}?$$
1. 引理(  $if \quad AX=0在\mathbb{C}上有\textcolor{orange}{\underline{\textbf{非零解}}}\quad \Rightarrow \quad AX=0在\mathbb{K}上也有\textcolor{red}{\underline{\textbf{非零解}}}$  )
	- **解释**
		- $研究 \mathbb{C} \quad \Leftrightarrow \quad  研究 \mathbb{K}$
	- **1个先决条件**
		- $AX=0 \quad 是数域\mathbb{K}上的\textcolor{pink}{\underline{\textbf{齐次线性方程组}}}$
3. 命题3.2(  $4个条件 \quad \Rightarrow \quad \deg \varphi(x) = \deg \psi(x)$  )
	- **解释**
		- $\mathscr{A}的\textcolor{pink}{\underline{\textbf{矩阵}}}A的\textcolor{orange}{\underline{\textbf{最小多项式}}}\varphi(x)是\textcolor{red}{\underline{\textbf{唯一}}}的$
	- **4个条件**
		1. $A \in M_{n}(\mathbb{K})$
		2. $\varphi(x)是A在\mathbb{K}上的一个\textcolor{orange}{\underline{\textbf{最小多项式}}}$
			- $\varphi(A)=0$
		1. $A \in M_{n}(\mathbb{C})$
		2. $\psi(x)是A在\mathbb{C}上的一个\textcolor{orange}{\underline{\textbf{最小多项式}}}$
			- $\psi(A)=0$
4. 命题3.3(  $2个条件\quad \Rightarrow \quad A在\mathbb{K}内的\textcolor{orange}{\underline{\textbf{最小多项式}}}\varphi(x)是\textcolor{red}{\underline{\textbf{唯一}}}的$  )
	- $\textcolor{orange}{\underline{\textbf{求解}}}A的\textcolor{red}{\underline{\textbf{最小多项式}}}\varphi(x)的命题:\quad \textcolor{orange}{\underline{\textbf{Jordan标准形法}}}$
	- **2个先决条件**
		1. $A \in M_{n}(\mathbb{K})$
		2. $A的\textcolor{orange}{\underline{\textbf{特征多项式}}}为f(\lambda)=|\lambda E -A|$
	- **2个条件**
		1. $f(\lambda)在\mathbb{C}内有\textcolor{pink}{\underline{\textbf{k}}}个\textcolor{red}{\underline{\textbf{互不相同}}}的\textcolor{orange}{\underline{\textbf{特征值}}}\lambda_{1} \ , \ \cdots \ , \ \lambda_{k}$
			- $\lambda_{i}  \ \neq \ \lambda_{j} \quad 1  \leqslant i  \ \neq \  j \leqslant k$
			- $f(\lambda_{m})=0 \quad 1  \leqslant m  \leqslant k$
		1. $A在\mathbb{C}内的\textcolor{pink}{\underline{\textbf{Jordan形}}}J以\lambda_{i}为\textcolor{orange}{\underline{\textbf{特征值}}}的\textcolor{pink}{\underline{\textbf{Jordan块}}}J_{i}的\textcolor{orange}{\underline{\textbf{最高阶数}}}为l_{i}$
	- **其中**
		- $\varphi(x)= \prod\limits^{k}_{i=1}(x-\lambda_{i})^{l_{i}}$
			- $\lambda_{i} \in \mathbb{K} \quad 1  \leqslant i  \leqslant k$
		- $\lambda_{1} \ , \ \cdots \ , \ \lambda_{n}\textcolor{orange}{\underline{\textbf{未必全属于}}}\mathbb{K}$
			- $\exists \ \lambda_{0}  \notin \mathbb{K} \quad S.t. \quad f(\lambda_{0})=0$
		- $\varphi(x)的\textcolor{orange}{\underline{\textbf{所有系数}}}都 \in \mathbb{K}$
	- **推论**(  $1个条件 \quad \Rightarrow \quad 1个结论$  )
		- **1个先决条件**
			1. $A、B \in M_{n}(\mathbb{K})$
		- **1个条件**
			1. $A \sim B$
		- **1个结论**
			1. $A与B在\mathbb{K}内的\textcolor{orange}{\underline{\textbf{最小多项式}}}\textcolor{red}{\underline{\textbf{相同}}}$
		1. 定义(  [[线性变换的最小多项式]]  )
			- $\varphi(x)$
	- **推论**(  $1个必要条件\quad \Leftrightarrow \quad 1个充分条件$  )
		- **2个先决条件**
			1. $A \in M_{n}(\mathbb{K})$
			2. $A的\textcolor{orange}{\underline{\textbf{特征多项式}}}的\textcolor{orange}{\underline{\textbf{根}}} \textcolor{red}{\underline{\textbf{都属于}}}\mathbb{K}$
		- **1个必要条件**
			1. $A在\mathbb{K}内\textcolor{orange}{\underline{\textbf{相似于}}}\textcolor{red}{\underline{\textbf{对角矩阵}}}$
		- **1个充分条件**
			1. $A的\textcolor{orange}{\underline{\textbf{最小多项式}}}\textcolor{red}{\underline{\textbf{没有}}}\textcolor{orange}{\underline{\textbf{重根}}}$
		1. 定义(  [[半单矩阵]]  )
			- $A$
		2. 定义(  [[半单线性变换]]  )
			- $\mathscr{A}$
	- **推论**(  $1个必要条件 \quad \Leftrightarrow \quad  1个充分条件$  )
		- $判断A是否\textcolor{orange}{\underline{\textbf{可对角化}}}的推论$
		- **3个先决条件**
			1. $\dim V(\mathbb{K} )=n$
			2. $\mathscr{A} \in End(V)$
			3. $\mathscr{A}的\textcolor{orange}{\underline{\textbf{特征多项式}}}的\textcolor{orange}{\underline{\textbf{根}}}\textcolor{red}{\underline{\textbf{全属于}}}\mathbb{K}$
		- **1个必要条件**
			1. $\mathscr{A}的\textcolor{pink}{\underline{\textbf{矩阵}}}A \textcolor{red}{\underline{\textbf{可对角化}}}$
				- $A \sim D$
		- **1个充分条件**
			1. $\mathscr{A}是\textcolor{red}{\underline{\textbf{半单线性变换}}}$
				- $\mathscr{A}的\textcolor{orange}{\underline{\textbf{最小多项式}}}\textcolor{red}{\underline{\textbf{没有}}}\textcolor{orange}{\underline{\textbf{重根}}}$

5. 矩阵的$\textcolor{orange}{\underline{\textbf{最小多项式}}}的计算方法$
	1. $计算Jordan标准形法$
	2. $找最小m法$
		- 计算步骤
			1. $考虑E \ , \ A \ , \ A^{2} \ , \ \cdots \in M_{n}(\mathbb{K})$
			2. $\textcolor{orange}{\underline{\textbf{从左至右}}}\ , \ 找出\min m \in \mathbb{N}_{+} \quad S.t. \quad A^{m}能被上式\textcolor{orange}{\underline{\textbf{线性表示}}}$
				- $A^{m}=a_{1}A^{m-1} + \cdots a_{m}E \quad a_{i} \in \mathbb{K}$
			3. $\varphi(x)=x^{m}-a_{1}x^{m-1}- \cdots -a_{m}$
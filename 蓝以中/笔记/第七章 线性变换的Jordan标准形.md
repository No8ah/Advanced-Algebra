## 一、幂零线性变换的Jordan标准形

1. 定义(  [[幂零线性变换]]  ) #高代下/第七章/重要定义
	- $\exists \ m \in \mathbb{N}_{+} \quad S.t. \quad \mathbb{A}^{m}=0$
	2. 定义(  [[幂零矩阵]]  ) #高代下/第七章/重要定义 
		- $\exists \ m \in \mathbb{N}_{+} \quad S.t. \quad A^{m}=0$
1. 命题1.1(  $\mathbb{A}是\textcolor{orange}{\underline{\textbf{幂零线性变换}}} \quad \Rightarrow \quad 2个结论$  ) #高代下/第七章/重要命题
	- **2个结论**
		1. $\mathbb{A}的\textcolor{orange}{\underline{\textbf{特征多项式}}}为f(\lambda)=\lambda^{n}$
		2. $\mathbb{A}有\textcolor{red}{\underline{\textbf{唯一}}}的特征值\lambda_{0}=0$
### 1. 循环不变子空间

1. 引理(  $2个条件 \quad \Rightarrow \quad \alpha\ , \ \mathbb{A}\alpha \ ,\ \cdots \ , \ \mathbb{A}^{k-1}\alpha \textcolor{red}{\underline{\textbf{线性无关}}}\quad(k是\textcolor{orange}{\underline{\textbf{最小正整数}}}\quad k \geq 1)$  )
	- **2个条件**
		1. $V是\textcolor{pink}{\underline{\textbf{数域}}}\mathbb{K}上的n维\textcolor{orange}{\underline{\textbf{线性空间}}}$
		2. $\mathbb{A}是V内的一个\textcolor{orange}{\underline{\textbf{幂零线性变换}}}$
3. 定义(  [[循环不变子空间]]  )(  $I(\alpha)=L(\alpha\ , \ \mathbb{A}\alpha \ , \ \cdots \ , \ \mathbb{A}^{k-1}\alpha)$  )
	- $I(\alpha)为\mathbb{A}的一个\textcolor{red}{\underline{\textbf{不变子空间}}}$
	2. 定义(  [[Jordan形矩阵]]  )(  $J=diag\{J_{1} \ , \ \cdots \ , \ J_{n}\}$  )
	3. 定义(  [[Jordan块]]  )(  $J_{i}$  )
5. 命题1.2(  $\exists \ \textcolor{pink}{\underline{\textbf{基}}} \in V \quad S.t. \quad \mathbb{A}在V的\textcolor{pink}{\underline{\textbf{基}}}下的矩阵为\textcolor{red}{\underline{\textbf{Jordan形}}}\quad \Leftrightarrow \quad  1个结论$  ) #高代下/第七章/重要命题 
	- **1个先决条件**
		1. $\mathbb{A}是\dim V (\mathbb{K})=n上的一个\textcolor{orange}{\underline{\textbf{幂零线性变换}}}$
	- **1个结论**
		1. $V= I(\alpha_{1}) \oplus \cdots \oplus I(\alpha_{s})$
### 2. 幂零线性变换的Jordan标准形

1. 命题1.3(  $2个条件\quad \Rightarrow \quad 1个结论$  )
	- **2个条件**
		1. $\bar{\alpha}=\alpha+M为\bar{V}=V / M中的一个\textcolor{orange}{\underline{\textbf{非零元素}}}$
		2. $I(\bar{\alpha})为\mathbb{A}在\bar{V}内\textcolor{pink}{\underline{\textbf{诱导变换}}}的一个k维\textcolor{orange}{\underline{\textbf{循环不变子空间}}}$
			- $I(\alpha)=L(\alpha \ , \ \mathbb{A}\alpha \ , \ \cdots \ , \ \mathbb{A}^{k}\alpha) \quad (\mathbb{A}^{k}\alpha \in M)$
1. 命题1.4(  $\mathbb{A}是\textcolor{orange}{\underline{\textbf{幂零线性变换}}}\quad \Rightarrow \quad \exists \ \textcolor{pink}{\underline{\textbf{基}}} \in V \quad S.t. \quad \mathbb{A}在V的\textcolor{pink}{\underline{\textbf{基}}}下的矩阵为\textcolor{red}{\underline{\textbf{Jordan形}}}$  ) #高代下/第七章/重要命题 
2. 定义(  [[循环幂零线性变换]]  )(  $\mathbb{A}$  ) #高代下/第七章/重要定义 
	- $\mathbb{A}^{n-1}\neq 0 \quad \mathbb{A}^{n}=0$
		- $\textcolor{orange}{\underline{\textbf{注意}}} \quad k=n \in \mathbb{N}_{+}$
	1. 定义(  [[循环基]]  )(  $\alpha \ , \ \mathbb{A}\alpha \cdots \ , \ \mathbb{A}^{n-1}\alpha$  ) #高代下/第七章/重要定义 
		- **1个条件**
			- $\mathbb{A} \quad is \quad \textcolor{orange}{\underline{\textbf{循环幂零线性变换}}}$
		- $\mathbb{A}在\textcolor{orange}{\underline{\textbf{循环基}}}下的矩阵为\textcolor{red}{\underline{\textbf{Jordan块}}}\quad (M_{n}(\mathbb{K}))$
## 二、一般线性变换的Jordan标准形

### 1. Jordan块与Jordan形

1. 定义(  [[Jordan块]]  )
	- $J_{i}$
1. 定义(  [[Jordan形矩阵]]  )
	- $J=diag \{J_{1}\ , \ \cdots \ , \ J_{s}\}$
### 2. Jordan标准形的存在性

1. 命题2.1(  $if \quad \exists \ \lambda_{0}\in \mathbb{K} \quad S.t. \quad \mathbb{A}-\lambda_{0}\mathbb{E}是\textcolor{orange}{\underline{\textbf{幂零线性变换}}} \quad \Rightarrow \quad 1个结论$  )
	- **1个先决条件**
		- $\mathbb{A}是\dim V(\mathbb{K}) =n上的\textcolor{orange}{\underline{\textbf{线性变换}}}$
	- **1个结论**
		- $\exists \ \textcolor{orange}{\underline{\textbf{基}}} \in V \quad S.t. \quad \mathbb{A}在这组基下的矩阵为\textcolor{red}{\underline{\textbf{Jordan标准形}}}$
2. 定义(  [[子空间序列]]  )
	- $M_{i}=Ker \mathscr{B}^{i}$
	- $N_{i}=Im \mathscr{B}^{i}$
	- **3个性质**
		1. 包含性质
			1. $\{0\}=M_{0} \subseteq M_{1} \subseteq M_{2} \subseteq \cdots$
			2. $V = N_{0} \supseteq N_{1} \supseteq N_{2} \supseteq \cdots$
		2. $\dim M_{i} +\dim N_{i} =n \quad n=0\ , \ 1\ , \ 2\ , \ \cdots$
		3. 最小性质
			1. $M_{0} \subset M_{1} \subset \cdots \subset M_{k} =M_{k+1} =\cdots$
			2. $N_{0} \supset N_{1} \supset \cdots \supset N_{k}=N_{k+1} = \cdots$
1. 命题2.2(  $1个条件 \quad \Rightarrow \quad \exists \ \textcolor{pink}{\underline{\textbf{基}}}\in V \quad S.t. \quad \mathbb{A}在这组基下的矩阵为\textcolor{red}{\underline{\textbf{Jordan标准形}}}J$  ) #高代下/第七章/重要命题 
	- **1个先决条件**
		- $\mathbb{A} 是\dim V(\mathbb{K}) = n内的\textcolor{orange}{\underline{\textbf{线性变换}}}$
	- **1个条件**
		- $f(\lambda)=|\lambda E-A|的\textcolor{orange}{\underline{\textbf{根}}}\textcolor{red}{\underline{\textbf{全属于}}}\mathbb{K}$
	- **其中**
		1. $J=diag(J_{1} \ , \ \cdots \ , \ J_{s})\quad (称为\mathbb{A}的\textcolor{orange}{\underline{\textbf{Jordan标准形}}})$
		2. $J_{i}为\textcolor{orange}{\underline{\textbf{Jordan块}}}\quad (\textcolor{pink}{\underline{\textbf{复数域}}}\mathbb{C}上的)(i \in \mathbb{N}_{+})$
### 3. Jordan标准形的唯一性

1. 命题2.3(  $\dim M_{i}=n-r(B^{i})$  )
	- **其中**
		1. $i=0,1\ , \ \cdots$
		2. $r(B^{i})表示B^{i}的\textcolor{pink}{\underline{\textbf{秩}}}$
		3. $B=A- \lambda_{0}E$
1. 命题2.4(  $3个条件\quad \Rightarrow \quad 1个结论$  )
	- **3个条件**
		1. $\mathbb{A}是\dim V(\mathbb{K}) = n上的\textcolor{orange}{\underline{\textbf{线性变换}}}$
		2. $f(\lambda)的\textcolor{orange}{\underline{\textbf{根}}}\textcolor{red}{\underline{\textbf{全属于}}}\mathbb{K}$
		3. $J是\mathbb{A}的\textcolor{pink}{\underline{\textbf{任一}}}\textcolor{orange}{\underline{\textbf{Jordan标准形}}}$
	- **1个结论**
		1. $\forall \ \lambda_{0} \quad  2\dim M_{l}-\dim M_{l+1} - \dim M_{l-1}=\cdots\quad(\lambda_{0}是\mathbb{A}的\textcolor{pink}{\underline{\textbf{特征值}}})$
		2. $\cdots = J中以\lambda_{0}为\textcolor{orange}{\underline{\textbf{特征值}}}\quad 且 \quad \textcolor{orange}{\underline{\textbf{阶为l}}}的\textcolor{orange}{\underline{\textbf{Jordan块的个数}}}$
	- **推论**
		1. $\textcolor{orange}{\underline{\textbf{线性变换}}}的\textcolor{orange}{\underline{\textbf{Jordan标准形J}}}\ , \ if \quad 不计\textcolor{pink}{\underline{\textbf{主对角线}}}上的Jordan块J_{i}的\textcolor{orange}{\underline{\textbf{排列次序}}}\quad \Rightarrow \quad J是\textcolor{red}{\underline{\textbf{唯一的}}}$
		2. $2个条件 \quad \Rightarrow \quad \mathscr{A}的Jordan标准形J中以\lambda_{0}为\textcolor{pink}{\underline{\textbf{特征值}}}的\textcolor{orange}{\underline{\textbf{l阶}}}Jordan块J_{i}的\textcolor{red}{\underline{\textbf{个数}}}为r(B^{l+1})+r(B^{l-1})-2r(B^{l})$ #高代下/第七章/重要推论
			- **2个条件**
				1. $\textcolor{orange}{\underline{\textbf{线性变换}}}\mathscr{A}在\textcolor{pink}{\underline{\textbf{某一组基}}}下的矩阵为A$
				2. $\lambda_{0}是\mathscr{A}的\textcolor{orange}{\underline{\textbf{任一特征值}}}$
			- **其中**
				- $B=A-\lambda_{0}E$
2. 定理2.1(  $1个条件\quad \Rightarrow \quad \exists \ V中\textcolor{orange}{\underline{\textbf{一组基}}}\quad S.t. \quad \mathscr{A}在\textcolor{pink}{\underline{\textbf{这组基}}}下的矩阵A为Jordan形J=diag \{J_{1}\ , \ \cdots \ , \ J_{s}\}$  )
	- **1个先决条件**
		1. $\mathscr{A} \in End(V)$
	- **1个条件**
		1. $A的\textcolor{orange}{\underline{\textbf{特征多项式的根}}}\textcolor{red}{\underline{\textbf{全属于}}}\mathbb{K}$
	- **其中**
		- $除了主对角线上Jordan块J_{i}的排序\textcolor{pink}{\underline{\textbf{可以不同}}}外\ , \ J由\mathscr{A}\textcolor{red}{\underline{\textbf{唯一决定}}}$
3. 定理2.2(  $1个条件 \quad \Rightarrow \quad A(\mathbb{K}) \sim Jordan形J=diag \{J_{1}\ , \ \cdots \ , \ J_{s}\}$  )
	- **1个先决条件**
		1. $A \in M_{n}(\mathbb{K})$
	- **1个条件**
		1. $A的\textcolor{orange}{\underline{\textbf{特征多项式的根}}}\textcolor{red}{\underline{\textbf{全属于}}}\mathbb{K}$
	- **其中**
		- $除了主对角线上Jordan块J_{i}的排序\textcolor{pink}{\underline{\textbf{可以不同}}}外\ , \ J由A \textcolor{red}{\underline{\textbf{唯一决定}}}$
	- 定义(  [[A的Jordan形]]  )
		- $A \sim J= diag \{J_{1} \ , \ \cdots \ , \  J_{s}\}$
		- **注意**
			- $J_{i}不同$
### 4. Jordan标准形的计算方法

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
> [!summary]+ 引入
> $$使用\textcolor{orange}{\underline{\textbf{多项式}}}研究\textcolor{pink}{\underline{\textbf{线性变换}}}\mathscr{A}或者\textcolor{pink}{\underline{\textbf{矩阵}}}A$$
### 1. 方阵的化零多项式

1. 定义(  [[方阵的化零多项式]]  )
	- $if \quad g(A)=0$
	- $g(x)  \ \  \overset{\triangle}{=} \ \ A的一个\textcolor{orange}{\underline{\textbf{化零多项式}}}$
	- **2个条件**
		1. $A \in M_{n}(\mathbb{K})$
		2. $g(x)是\mathbb{K}上的一个\textcolor{orange}{\underline{\textbf{多项式}}}$
1. 命题3.1(  $g(x)是J的\textcolor{orange}{\underline{\textbf{化零多项式}}}\quad \Leftrightarrow \quad 2个条件$  )
	- **2个先决条件**
		1. $给定\mathbb{K}上的Jordan形矩阵J$
		2. $g(x)是\mathbb{K}上的一个\textcolor{orange}{\underline{\textbf{m次多项式}}}$
	- **2个条件**
		1. $\lambda_{0}是g(x)的一个\textcolor{orange}{\underline{\textbf{零点}}}$
		2. $\lambda_{0}的\textcolor{orange}{\underline{\textbf{重数}}} \geq J的\textcolor{orange}{\underline{\textbf{阶数}}}n$
2. [[Hamilton-Cayley定理]](  $f(\lambda)=|\lambda E -A| \quad \Rightarrow \quad f(A)=0$  )
	- **2个先决条件**
		1. $A \in M_{n}(\mathbb{K})$
		2. $f(\lambda)=|\lambda E-A|是A的\textcolor{orange}{\underline{\textbf{特征多项式}}}$

>[!attention]+ **引出问题**
>$$E \ , \ A \ , \  \cdots \ , \ A^{n-1}是否还有\textcolor{pink}{\underline{\textbf{某个}}}A^{k}可被它前面的向量\textcolor{orange}{\underline{\textbf{线性表示}}}?$$
### 2. 方阵的最小多项式

1. 定义(  [[方阵的最小多项式]]  )
	- $\varphi(x)是A的\textcolor{orange}{\underline{\textbf{最小多项式}}}$
	- **性质**
		1. $\varphi(x)\textcolor{pink}{\underline{\textbf{系数}}} \in \mathbb{K}$
		2. $\varphi(x)的\textcolor{orange}{\underline{\textbf{首项系数}}}=1$
		3. $\varphi(A)=0$
		4. $if \quad \exists \ \textcolor{orange}{\underline{\textbf{非零多项式}}}g(x) \in \mathbb{K} \quad S.t. \quad g(A)=0 \quad \Rightarrow \quad \deg g(x) \geq \deg \varphi(x)$

> [!note]+ **引出问题**
> 事实:
> $$A的\textcolor{orange}{\underline{\textbf{最小多项式 }}}\textcolor{pink}{\underline{\textbf{存在}}}$$
> 一、
> $$\textcolor{pink}{\underline{\textbf{最小多项式}}}是否\textcolor{orange}{\underline{\textbf{唯一}}}?$$
> 二、
> $$如何\textcolor{orange}{\underline{\textbf{求出}}}\textcolor{pink}{\underline{\textbf{最小多项式}}}?$$
1. 引理(  $if \quad AX=0在\mathbb{C}上有\textcolor{orange}{\underline{\textbf{非零解}}}\quad \Rightarrow \quad AX=0在\mathbb{K}上也有\textcolor{red}{\underline{\textbf{非零解}}}$  )
	- **1个先决条件**
		- $AX=0 \quad 是数域\mathbb{K}上的\textcolor{pink}{\underline{\textbf{齐次线性方程组}}}$
2. 命题3.2(  $2个条件 \quad \Rightarrow \quad \deg \varphi(x) = \deg \psi(x)$  )
	- **2个先决条件**
		1. $A \in M_{n}(\mathbb{K})$
		2. $\varphi(x)是A的一个\textcolor{orange}{\underline{\textbf{最小多项式}}}$
	- **2个条件**
		1. $A \in M_{n}(\mathbb{C})$
		2. $A在\mathbb{C}上的一个\textcolor{orange}{\underline{\textbf{最小多项式}}}为 \psi(x)$
3. 命题3.3(  $2个条件\quad \Rightarrow \quad A在\mathbb{K}内的\textcolor{orange}{\underline{\textbf{最小多项式}}}\varphi(x)是\textcolor{red}{\underline{\textbf{唯一}}}的$  )
	- **2个先决条件**
		1. $A \in M_{n}(\mathbb{K})$
		2. $A的\textcolor{orange}{\underline{\textbf{特征多项式}}}为f(\lambda)=|\lambda E -A|$
	- **2个条件**
		1. $f(\lambda)在\mathbb{C}内有\textcolor{pink}{\underline{\textbf{k}}}个\textcolor{red}{\underline{\textbf{互不相同}}}的\textcolor{orange}{\underline{\textbf{特征值}}}\lambda_{1} \ , \ \cdots \ , \ \lambda_{k}$
		2. $A在\mathbb{C}内的Jordan形J以\lambda_{i}为\textcolor{orange}{\underline{\textbf{特征值}}}的Jordan块J_{i}的\textcolor{orange}{\underline{\textbf{最高阶数}}}为l_{i}$
	- 其中
		- $\varphi(x)= \prod\limits^{k}_{i=1}(x-\lambda_{i})^{l_{i}}$
		- $\lambda_{1} \ , \ \cdots \ , \ \lambda_{n}\textcolor{orange}{\underline{\textbf{未必全属于}}}\mathbb{K}$
		- $\varphi(x)的\textcolor{orange}{\underline{\textbf{所有系数}}}都 \in \mathbb{K}$
	1. 推论1(  $A \sim B \quad \Rightarrow \quad A与B在\mathbb{K}内的\textcolor{orange}{\underline{\textbf{最小多项式}}}\textcolor{red}{\underline{\textbf{相同}}}$  )
		- **1个先决条件**
			1. $A、B \in M_{n}(\mathbb{K})$
		1. 定义(  [[线性变换的最小多项式]]  )
			- $\varphi(x)$
	1. 推论2(  $A在\mathbb{K}内\textcolor{orange}{\underline{\textbf{相似于}}}\textcolor{red}{\underline{\textbf{对角矩阵}}} \quad \Leftrightarrow \quad A的\textcolor{orange}{\underline{\textbf{最小多项式}}}\textcolor{red}{\underline{\textbf{没有重根}}}$  )
		- **2个先决条件**
			1. $A \in M_{n}(\mathbb{K})$
			2. $A的\textcolor{orange}{\underline{\textbf{特征多项式}}}的\textcolor{orange}{\underline{\textbf{根}}} \textcolor{red}{\underline{\textbf{都属于}}}\mathbb{K}$
		1. 定义(  [[半单矩阵]]  )
			- $A \in M_{n}(\mathbb{K})$
		2. 定义(  [[半单线性变换]]  )
			- $\mathbb{A}$
	1. 推论3(  $\mathbb{A}的\textcolor{pink}{\underline{\textbf{矩阵}}}\textcolor{red}{\underline{\textbf{可对角化}}} \quad \Leftrightarrow \quad \mathbb{A}是\textcolor{red}{\underline{\textbf{半单线性变换}}} \quad \leftrightarrow \quad A的\textcolor{orange}{\underline{\textbf{最小多项式}}}\textcolor{red}{\underline{\textbf{无重根}}}$  )
		- **3个先决条件**
			1. $\dim V(\mathbb{K} )=n$
			2. $\mathbb{A} \in End(V)$
			3. $\mathbb{A}的\textcolor{orange}{\underline{\textbf{特征多项式}}}的\textcolor{orange}{\underline{\textbf{根}}}\textcolor{red}{\underline{\textbf{全属于}}}\mathbb{K}$
1. 矩阵的$\textcolor{orange}{\underline{\textbf{最小多项式}}}的计算方法$
	1. $计算Jordan标准形法$
	2. $找最小m法$
		- 计算步骤
			1. $考虑E \ , \ A \ , \ A^{2} \ , \ \cdots \in M_{n}(\mathbb{K})$
			2. $\textcolor{orange}{\underline{\textbf{从左至右}}}\ , \ 找出\min m \in \mathbb{N}_{+} \quad S.t. \quad A^{m}能被上式\textcolor{orange}{\underline{\textbf{线性表示}}}$
				- $A^{m}=a_{1}A^{m-1} + \cdots a_{m}E \quad a_{i} \in \mathbb{K}$
			3. $\varphi(x)=x^{m}-a_{1}x^{m-1}- \cdots -a_{m}$
$$V是数域\mathbb{K}上的一个n维线性空间$$
$$M是V的一个子空间$$
$$\alpha是V的一个向量$$
$$如果\exists \ \alpha^{'} \ \in \ V$$
$$S.t. \ \ \alpha^{'}- \alpha \in M$$
$$称为\alpha^{'}与\alpha \underline{ \textbf{模M同余}}$$
$$\tag{模M同余}记为\alpha^{'} \equiv \alpha(mod \textbf{M})$$
## 性质 ：
### 反身性 ：
$$\alpha \equiv \alpha(modM)$$
证明 ：
由[[子空间]]的性质 得到 ：
$$\alpha - \alpha =  \bar{0} \ \in \ M \ \ 显然成立$$
### 对称性 ：
$$\alpha^{'} \equiv \alpha(mod M) \ \ \Rightarrow \alpha \equiv \alpha^{'}(mod M)$$
证明 ：
根据[[模M同余]]的定义 得到 ：
$$\alpha^{'}-\alpha \ \in \ M$$
由[[子空间]]的性质 得到 ：
$$-(\alpha^{'}-\alpha) = \alpha - \alpha^{'}\ \in \ M$$
也就是说 ：
$$\alpha \equiv \alpha^{'}(mod M)  \ \ 得证 \ \ !$$
### 传递性 ：
$$\alpha^{''} \equiv \alpha^{'}(mod M)$$
并且 ：
$$\alpha^{'} \equiv \alpha(mod M)$$
$$\Rightarrow \ \ \alpha^{''} \equiv \alpha(mod M)$$
证明 ：
由[[模M同余]]的定义 得到 ：
$$\alpha^{''}-\alpha^{'}\in M$$
$$\alpha^{'}- \alpha \in M$$
由[[子空间]]的定义 得到 ：
$$(\alpha^{''}-\alpha^{'})+(\alpha^{'}-\alpha) \in M$$
也就是 ：
$$\alpha^{''}-\alpha \in M$$
由[[模M同余]]的定义 得到 ：
$$\alpha^{''} \equiv \alpha(mod M)\ \ 得证 \ \ !$$
## 相关定义 ：
1. [[同余类与同余类的代表元]]

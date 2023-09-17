# Relations

## Relations and Their Properties 关系与关系性质

### 二元关系

> 关系：集合A到集合B的二元关系R时A×B的子集(subset).及任一序偶的集合确定一个关系，记作：R:A×B, aRb。  
> 函数是特殊的关系

#### complementary relation 补关系

### properties of relations 关系性质

#### reflexive 自反性

> 对于每个元素 a∈A 都有 (a,a)∈R，即 $\forall$a∈A, aRa。则称定义在集合A中的关系R是自反的  
> $\forall$x(x∈A ——> (x,x)∈R)

注：集合A上$2^{n^2-n}$种自反关系。A×A有$n^2$个序偶，如果要是自反，每个子集中必须含有n个(a,a),即减去这n个，然后求子集

#### irreflexive 反自反性

> 对于每个元素 a∈A 都有 (a,a)$\notin$R,则称定义在集合A中的关系R是反自反的  
> $\forall$x(x∈A ——> (x,x)$\notin$R)

例：  

* R1={(a,b)|a<b},
* A = $\emptyset$

注：不是自反不一定是反自反

#### symmetric 对称性

> 对于任意a,b∈A,若只要(a,b)∈R就有(b,a)∈R,则称定义在集合A中的关系R是对称的  
> $\forall$x$\forall$y ((x,y)∈R->(y,x)∈R)

例：  

* R1 = {(a,b)| a = b or a = -b}

注：

* 这里只要有(a,b)，就一定得有(b,a),才是对称的

#### antisymmetric 反对称性

> 对于任意a,b∈A,若(a,b)∈R并且(b,a)∈R,则一定有 a = b,则称定义在集合A中的关系R是反对称的  
> $\forall$x$\forall$y((x,y)∈R $\bigwedge$ (y,x)∈R ——>x=y )

例：  

* R1 = {(a,b)|a$\leq$b}

#### transitive 传递性

> 如果对于任意a,b,c ∈A，(a,b)∈R 且(b,c)∈R则(a,c)∈R,那么定义在集合A上的关系R就满足传递性。  
> $\forall$a$\forall$b$\forall$c(((a,b)∈R$\bigwedge$(b,c)∈R)——>(a,c)∈R)

例：  

* R1 = {(a,b)|a$\leq$b}

注：

1. 当前提不成立时，也满足传递性。如 A={(a,b)}
2. R$\supseteq$R$^n$当且仅当R具有传递性

### 运算

$\bigvee$ ,$\bigwedge$, - ,$\oplus$(除去相同的序偶)

### composition 关系的合成

> R1是集合A到B的关系，R2是集合B到集合C的关系。则R2和R1的合成是A到C的关系：

* 若$\exists$y∈B,使得(x,y)∈R1且(y,z)∈R2,则(x,z)∈R2,则(x,z) ∈ R2$\omicron$R1,表示关系R1与R2的合成


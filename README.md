# borealis
- borealis 路径设置

暂时设置 BOREALIS='/borealis'
在 /etc/profile 里加入  BOREALIS='/borealis' 并在后面导出 export BOREALIS  ,source profile 重新加载配置文件

文件共享时输入的ip地址要注意看 ipconfig  /all


http://cs.brown.edu/research/borealis/public/

- borealis的依赖包说明

CCache   ccache编译器编译，然后缓存编译生成的信息，从而在下一次编译时，利用这个缓存加快编译的速度

antlr     Another Tool for Language Recognition   开源语法分析器  Used by Borealis to parse XML

Xerces     用c++解析xml文件

Glpk       线性规划库   Used by the Load Manager component

Gsl        C 写成的用于科学计算的库  Used for Predictive queries.

doxygen   代码文档生成器

Ocv     Used for Array processing (ASAP)

gcc地址  https://gcc.gnu.org/pub/gcc/releases/gcc-4.1.1/



实现了自制C--语言的一遍扫描编译，包括词法分析、LR(1)语法分析、属性文法+中间代码生成、MIPS汇编生成
编译脚本由Python实现，兼容python2.7与3.7，图形界面由WPF实现，使用了IronPython进行脚本执行

支持以下特性:
1. 一种基本类型int
2. 赋值表达式，循环/选择/判断/跳出语句
3. 函数定义与函数调用

 未实现:
1. 浮点数、字符、字符串
2. 数组
3. 错误检查
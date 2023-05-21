# C-compiler
同济大学 计科 编译原理 课程设计 类C编译器



- 编译

```bash
make
```

- 启动

```bash
./parser
```

- 清单：
  - main.cpp：主函数
  - common.cpp：公共函数
  - myParse.cpp：词法分析器
  - grammarParser.cpp:语义语法分析器
  - blocksGenerator.cpp：基本块分析器
  - memManager.cpp：寄存器及内存管理器
  - objectCodeGenerator.cpp：目标代码生成器
  - WordParseGrammar.txt：词法文法
  - grammar.txt：语法文法
  - test.txt：正确测试用例
  - testWrong1.txt：错误测试用例1
  - testWrong2.txt：错误测试用例2
  - testWrong3.txt：错误测试用例3
  - code.asm：生成的目标代码


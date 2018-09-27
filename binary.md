# 二进制安全常用工具

## 基础工具
* peda
* pyelftools
* pwntools
* capstone
* llvm
* qemu
* gdb
* ida



## Fuzz工具

|名称|简介|链接|
|:-:|:-:|:-:|
| afl-fuzz | 非常流行的Fuzz工具 | http://lcamtuf.coredump.cx/afl/
| win-afl | 适用于Windows平台的afl | https://github.com/googleprojectzero/winafl
| TriforceAFL | 基于qemu的全系统模拟Fuzz工具 | https://github.com/nccgroup/TriforceAFL
| Peach Fuzzer | fuzz前通过了解被测试程序的结构信息编写pit配置文件来指导fuzz | http://www.peach.tech/products/peach-fuzzer/ 
| vuzzer | fuzz前静态分析比较指令，提取种子；fuzz中基于pin插桩反馈变异；给更深的路径更高权重| https://github.com/vusec/vuzzer
| driller| 结合了符号执行的fuzz（angr+afl）| https://github.com/shellphish/driller
| honggfuzz | Google 开发fuzz工具 | https://github.com/google/honggfuzz|



## 符号执行工具

|名称|简介|链接|
|:-:|:-:|:-:|
| angr | 软件分析平台，python框架，支持符号执行，包含控制流图分析等多种技术 | http://angr.io/|
| s2e |  软件分析平台，基于虚拟机，在线符号执行，包含多种程序分析技术 | http://s2e.systems/|
| z3 | 约束求解器 | https://github.com/z3prover|

## IoT工具
|名称|简介|链接|
|:-:|:-:|:-:|
| binwalk | 解固件工具 | https://github.com/ReFirmLabs/binwalk|
| pyserial | 串口连接工具 | https://github.com/pyserial/pyserial|


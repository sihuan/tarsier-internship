# Week2 TODO

### 制作 risc-v mugen 测试套/测试用例 repo

- 阅读、改进已有能成功运行的测试套和用例
- 将适用于 risc-v openEuler 的测试用例组织成单独 repo 并提供使用文档

### 尝试解决 mugen 测试效率问题

####  从 脚本中运行多个 mugen 实例

- 多个 mugen 可能相互干扰，比如不能同时运行 rpm install （文件锁）

####  在多个 qemu 虚拟机进行测试

- qemu 网络问题
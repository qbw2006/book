Idea快捷键整理

| 快捷键                    | 重要性<br />必备：熟练掌握<br />推荐：建议掌握<br />无视：不用掌握 | 介绍                                       |
| ---------------------- | ---------------------------------------- | ---------------------------------------- |
| **Ctrl + A**           | **必备**                                   | **全选**                                   |
| Ctrl + Alt + A         | 无视                                       | VCS相关                                    |
| Ctrl + Shift + A       | 推荐                                       | 搜索Actions                                |
| Ctrl + Alt + Shift + A | 无视                                       | type alias                               |
|                        |                                          |                                          |
| **Ctrl + B**           | **必备**                                   | **找到变量或方法的声明或调用**                        |
| **Ctrl + Alt + B**     | **必备**                                   | **找到抽象方法或接口方法的所有实现**                     |
| **Ctrl + Shift + B**   | **必备**                                   | **找到变量或方法的类型定义。<br />比如String a;在a上使用会转到String类定义** |
| Ctrl + Alt + Shift + B | 无视                                       | 插件相关                                     |
|                        |                                          |                                          |
| **Ctrl + C**           | **必备**                                   | **复制**                                   |
| **Ctrl + Alt + C**     | **推荐**                                   | **重构，将当前选择的局部变量变为静态常量**                  |
| Ctrl + Shift + C       | 推荐                                       | 复制路径，比如在类型String上使用，<br />会复制String在文件系统的绝对路径 |
| Ctrl + Alt + Shift + C | 无视                                       | 插件相关                                     |
|                        |                                          |                                          |
| **Ctrl + D**           | **必备**                                   | **复制当前行代码，并粘贴到下一行**                      |
| Ctrl + Alt + D         | 无视                                       | 插件相关                                     |
| Ctrl + Shift + D       | 无视                                       | 插件相关                                     |
| Ctrl + Alt + Shift + D | 无视                                       | 插件相关                                     |
|                        |                                          |                                          |
| **Ctrl + E**           | **必备**                                   | **最近浏览过的文件**                             |
| Ctrl + Alt + E         | 无视                                       | 插件相关                                     |
| **Ctrl + Shift + E**   | **必备**                                   | **最近修改过的文件**                             |
| Ctrl + Alt + Shift + E | 无视                                       | 无                                        |
|                        |                                          |                                          |
| **Ctrl + F**           | **必备**                                   | **在当前文件进行文本查找**                          |
| Ctrl + Alt + F         | 推荐                                       | 重构，将当前选择的局部变量变为成员变量                      |
| **Ctrl + Shift + F**   | **必备**                                   | **在当前路径进行文本查找**                          |
| Ctrl + Alt + Shift + F | 推荐                                       | 调用findbug扫描当前文件                          |
|                        |                                          |                                          |
| **Ctrl + G**           | **必备**                                   | **跳转到行列**                                |
| Ctrl + Alt + G         | 无视                                       | 无                                        |
| Ctrl + Shift + G       | 无视                                       | 无                                        |
| Ctrl + Alt + Shift + G | 无视                                       | 无                                        |
|                        |                                          |                                          |
| **Ctrl + H**           | **必备**                                   | **当前类的继承关系**                             |
| **Ctrl + Alt + H**     | **必备**                                   | **当前方法在何处有调用**                           |
| Ctrl + Shift+ H        | 推荐                                       | 找到虚函数或接口函数的所有实现                          |
| Ctrl + Alt + Shift + H | 无视                                       | 设置代码分析等级                                 |
|                        |                                          |                                          |
| Ctrl + I               | 推荐                                       | 自动生成当前类要实现的接口的代码                         |
| Ctrl + Alt + I         | 无视                                       | 自动换行，光标会按行向下移动                           |
| Ctrl + Shift+ I        | 无视                                       | 快速定义                                     |
| Ctrl + Alt + Shift+ I  | 无视                                       | 运行指定名称的inspection                        |
|                        |                                          |                                          |
| **Ctrl + J**           | **必备**                                   | **插入模板代码<br />比如public static final int这么一长串代码，<br />使用本快捷键然后选择psfi，会自动生成** |
| **Ctrl + Alt + J**     | **必备**                                   | **当前代码被模板代码包裹**                          |
| Ctrl + Shift + J       | 推荐                                       | 合并行，将多行合并成一行                             |
| Ctrl + Alt + Shift + J | 无视                                       | 功能类似rename，但范围只在当前文件中                    |
|                        |                                          |                                          |
| Ctrl + K               | 无视                                       | 插件相关                                     |
| Ctrl + Alt + K         | 无视                                       | 插件相关                                     |
| Ctrl + Shift+ K        | 无视                                       | 插件相关                                     |
| Ctrl + Alt + Shift+ K  | 无视                                       | 插件相关                                     |
|                        |                                          |                                          |
| Ctrl + L               | 推荐                                       | 找到当前被选择名称的下个引用处                          |
| **Ctrl + Alt + L**     | **必备**                                   | **根据format整理代码**                         |
| Ctrl + Shift + L       | 推荐                                       | 找到当前被选择名称的上个引用处，与Ctrl+L相返                |
| Ctrl + Alt + Shift + J | 推荐                                       | 设置整理代码的策略                                |
|                        |                                          |                                          |
| Ctrl + M               | 无视                                       | 当前行滚动到界面中间                               |
| **Ctrl + Alt + M**     | **必备**                                   | **重构，提炼方法**                              |
| Ctrl + Shift+ M        | 无视                                       | 移动光标到前括号                                 |
| Ctrl + Alt + Shift + M | 无视                                       | 无                                        |
|                        |                                          |                                          |
| **Ctrl + N**           | **必备**                                   | **根据名称查找类**                              |
| **Ctrl + Alt + N**     | **必备**                                   | **重构，内联方法**                              |
| **Ctrl + Shift+ N**    | **必备**                                   | **根据名称查找文件**                             |
| Ctrl + Alt + Shift + N | 无视                                       | 根据名称查找symbols                            |
|                        |                                          |                                          |
| **Ctrl + O**           | **必备**                                   | **查看本类所有继承方法**                           |
| **Ctrl + Alt + O**     | **必备**                                   | **优化引入**                                 |
| Ctrl + Shift + O       | 无视                                       | 无                                        |
| Ctrl + Alt + Shift + O | 无视                                       | 无                                        |
|                        |                                          |                                          |
| **Ctrl + P**           | **必备**                                   | **显示被调用方法的参数信息**                         |
| Ctrl + Alt + P         | 推荐                                       | 重构，提炼参数                                  |
| Ctrl + Shift + P       | 推荐                                       | 选择表达式                                    |
| Ctrl + Alt + Shift + P | 推荐                                       | 重构，提炼参数                                  |
|                        |                                          |                                          |
| **Ctrl + Q**           | **必备**                                   | **显示javadoc**                            |
| Ctrl + Alt + Q         | 无视                                       | 无                                        |
| Ctrl + Shift + Q       | 无视                                       | 无                                        |
| Ctrl + Alt + Shift + Q | 无视                                       | 无                                        |
|                        |                                          |                                          |
| **Ctrl + R**           | **必备**                                   | **在当前文件中替换**                             |
| Ctrl + Alt + R         | 无视                                       | 无                                        |
| **Ctrl + Shift + R**   | **必备**                                   | **在当前路径中替换**                             |
| Ctrl + Alt + Shift + R | 无视                                       | 无视                                       |
|                        |                                          |                                          |
| **Ctrl + S**           | **必备**                                   | **保存**                                   |
| Ctrl + Alt + S         | 推荐                                       | 打开settings                               |
| Ctrl + Shift+ S        | 无视                                       | 无                                        |
| Ctrl + Alt + Shift + S | 推荐                                       | 打开 project structrue                     |
|                        |                                          |                                          |
| Ctrl + T               | 无视                                       | 无                                        |
| **Ctrl + Alt + T**     | **必备**                                   | **使用模板包裹当前代码，与Ctrl+Alt+J模板不同**           |
| Ctrl + Shift + T       | 推荐                                       | 创建单元测试                                   |
| Ctrl + Alt + Shift + T | 推荐                                       | 打开重构策略                                   |
|                        |                                          |                                          |
| **Ctrl + U**           | **必备**                                   | **找到虚函数和接口函数的定义**                        |
| Ctrl + Alt + U         | 无视                                       | 无                                        |
| **Ctrl + Shift + U**   | **必备**                                   | **转换大小写**                                |
| Ctrl + Alt + Shift + U | 无视                                       | 插件相关                                     |
|                        |                                          |                                          |
| **Ctrl + V**           | **必备**                                   | **粘贴**                                   |
| Ctrl + Alt + V         | 推荐                                       | 重构，提炼局部变量                                |
| Ctrl + Shift + V       | 无视                                       | 从操作历史中                                   |
| Ctrl + Alt + Shift + V | 无视                                       | 粘贴代码时不考虑format                           |
|                        |                                          |                                          |
| **Ctrl + W**           | **必备**                                   | **扩大选中范围**                               |
| Ctrl + Alt +  W        | 无视                                       | 无                                        |
| **Ctrl + Shift  + W**  | **必备**                                   | **缩小选中范围**                               |
| Ctrl + Alt + Shift + W | 无视                                       | 无                                        |
|                        |                                          |                                          |
| **Ctrl + X**           | **必备**                                   | **剪切**                                   |
| Ctrl + Alt + X         | 无视                                       | 使用Xpath查找                                |
| Ctrl + Shift + X       | 无视                                       | 无                                        |
| Ctrl + Alt + Shift + X | 无视                                       | 插件相关                                     |
|                        |                                          |                                          |
| **Ctrl + Y**           | **必备**                                   | **删除行**                                  |
| Ctrl + Alt + Y         | 推荐                                       | 从仓库同步代码                                  |
| Ctrl + Shift + Y       | 无视                                       | 无                                        |
| Ctrl + Alt + Shift + Y | 无视                                       | 无                                        |
|                        |                                          |                                          |
| **Ctrl + Z**           | **必备**                                   | **撤销**                                   |
| Ctrl + Alt + Z         | 无视                                       | 无                                        |
| **Ctrl + Shift + Z**   | **必备**                                   | **反撤销**                                  |
| Ctrl + Alt + Shift + Z | 无视                                       | 无                                        |


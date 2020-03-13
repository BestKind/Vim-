# 进入 vim
使用 vim 命令

# 退出 vim
在 normal 模式下使用 `:q` 

# 模式
- normal 普通模式 只读模式，无法编辑
- insert 插入模式 编辑模式
- visual 可视化模式
- command 命令模式


# 模式切换
normal 切换至 插入模式的方法: 
 - i insert 在当前字符前开始插入
 - a append 在当前字符后开始插入
 - o open a line below 在当前行的下面一行开始插入

 - I insert before line 在当前行最开始插入
 - A append after line 在当前行最后开始输入
 - O open a line above 在当前行的上面一行开始插入

normal 切换至 可视化模式的方法：使用 `v` 按键
 - v 切换为 visual 模式
 - V 选择行
 - ctrl + v 块状选择

命令模式：在 normal 模式下输入 `:` 之后执行命令，如 `:wq` 即保存退出
 - :w 保存 :q 退出
 - :vs 竖分屏 :sp  横分屏
 - :% s/foo/bar/g 全局替换
 - :/  查询

`tips`: 任何模式都需要从 normal 模式进入，而从其他模式切换为 normal 模式的方法都一样，按下 `esc` 按键



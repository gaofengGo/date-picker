# 日历组件
mocha 测试框架
should 断言库 assertion
安装在 devDependencies
测试驱动开发 TDD
git branch
git checkout
master dev test 个人开发分支
test 将进入我们的业务开发流程

js babel 编译
css stylus|sass|less
预编译 体力活 变量 for 函数
.styl => .css

stylus -w -m styl/ -o css/
生成css map文件， 有了它，便于调试

body margin 0 padding 0
css reset
normalize.css
colors.css
前端后端无界限

stylus 模块化方式，@import 将任务模块化划分， 以_.styl 将会编译到原文件，不会生成新文件。

stylus 为了方便省写选择器，提供结构嵌套。
以tab作为缩进，不结束缩进，里面所有的代码单元都可以引用到父类选择器
.parent
    .child
就会生成.parent .child
css 的一个作用域
.parent
    &.parent_other_class
        ...


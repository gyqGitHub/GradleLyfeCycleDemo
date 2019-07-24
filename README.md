# GradleLyfeCycleDemo
gradle构建，执行task的生命周期

把项目目录下的pre-commit文件**剪切**到你本地项目目录下的.git/hooks文件夹下，同时删除hooks文件下的pre-commit.sample文件，才能实现在提交前执行代码检查。没有剪切的话，还要注意**把项目目录下的pre-commit文件删除**，可能是因为和.git/hooks文件下的同名文件引起冲突会导致不能提交

如果跑的是fireline，只需要将pre-commit文件中的checkstyle换成runFireline

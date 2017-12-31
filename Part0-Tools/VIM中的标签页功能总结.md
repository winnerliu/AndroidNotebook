# VIM中的标签页功能总结

1. 配置 

set tabpagemax=18 VIM默认只能打开10个标签页，在配置文件可以修改这个限制： 

set showtabline=0 不显示标签栏 
set showtabline=1 这是默认设置，意思是，在创建标签页后才显示标签栏。 
set showtabline=2 总是显示标签栏 

2. 命令行命令： 

:tabe filename 用标签页打开文件 
:tabnew filename 用标签页打开文件 
:tab split 用标签页打开当期编辑的文件 
:tabf filename* 用标签页打开与通配符匹配的一个文件 
:tabs 显示所有标签页，> 指示当前页，+ 显示修改未保存 

:tabc 关闭当前标签页，功能等同于:q 
:tabo 关闭所有标签页 

:tabn 跳转后一个标签页 
:tabp 跳转前一个标签页 
:tabfirst 跳转第一个标签页 
:tabr 跳转第一个标签页 
:tablast 跳转最后一个标签页 

:tabm 0/1/2 将当前标签页移动到第1/2/3个页面位置 

:tabdo 对多个标签页同时执行命令，如 
:tabdo %s/aaa/bbb/g 

3. 操作命令: 

gt 跳转后一个标签页 
gT 跳转前一个标签页
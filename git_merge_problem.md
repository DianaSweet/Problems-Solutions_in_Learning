#Git合并分支出现 Please enter a commit message to explain why this merge is necessary.  

Git合并分支时报错:  
Please enter a commit message to explain why this merge is necessary.  

    merge brach "test"
    # Please enter a commit message to explain why this merge is necessary,
    # especially if it merges an updated upstream into a topic branch. 
    #
    # Lines starting with '#' will be ignored, and an empty message aborts
    # the commit.

解决方法：  
1. 按键盘左上角"Esc"；  
2. 输入":wq",按回车键即可。  
（注意，输入的内容是引号内的内容:wq，为引号+wq，不含双引号）  
如果想补充合并原因，可采取以下步骤：  
3. 按键盘字母 i 进入insert模式；  
4. 修改最上面那行黄色合并信息,可以不修改。  
之后再执行上面的两步操作。  
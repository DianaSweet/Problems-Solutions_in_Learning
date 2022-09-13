# git拉取仓库，报错Failed to connect to github.com port 443: Timed out  

今天在上传github的时候遇到了如下情况：  

    `Failed to connect to github.com port 443: Timed out`

各大网站有许多解决方法，这里可以列举一下：  

1.关闭代理服务器：  
    使用代理服务器会导致这样类似的问题，但我尝试后没有奏效。

2.重新设置git的代理：  
    首先更改git的代理；
    `$ git config --global http.proxy "127.0.0.1:1080"`
    然后取消代理；
    `$ git config --global --unset http.proxy`
    之后就成功上传了。

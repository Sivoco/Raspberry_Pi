1. 修改pip文件
    ```
    sudo nano /etc/pip.conf
    ```
2. 把内容替换为科技大学镜像
    ```
    [global]
    index-url = https://mirrors.ustc.edu.cn/pypi/web/simple
    format = columns
    ```
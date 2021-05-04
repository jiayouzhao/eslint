# ESlint全局配置

1. 下载eslint

    ```
        npm install -g eslint
    ```

2. vscode扩展 下载eslint

3. 全局设置eslint

    随便找一个地方，新建文件夹demo

    在此文件下的终端里按顺序执行下面命令
    ```
        npm init 
    ```
    ```
        eslint --init
    ```
    在eslint --init里，我设置的个人规范，其他的规范最好是全局下载。

    demo文件里生成一个.eslintrc.js的文件

    将.eslintrc.js文件移动到你的nodejs文件（npm包下载的位置，方便以后在寻找，比如我的是E:/nodejs）

4. vscode里文件 -> 首选项 -> 设置 

    输入eslint，进入Show Documentation

    在settings.json里添加并保存

    ```
        "eslint.options": {
        
            "configFile": "E:\\nodejs\\.eslintrc.js"
        }
    ```

5. 规范地址  https://eslint.bootcss.com/docs/rules/

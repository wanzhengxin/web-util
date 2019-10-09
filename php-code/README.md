# PHP 代码规范工具使用说明

## 安装

* 本地安装php环境, 并且配置相应的环境变量, 使得php命令能直接运行
* 使用以下命令把相关脚本软链到项目中, 其中的**此项目路径**请务必使用绝对路径

    ```sh
    $ cd ${PHP项目路径}/.git/hooks
    $ ln -sf ${此项目路径}/php-code/hooks/pre-commit
    $ ln -sf ${此项目路径}/php-code/hooks/prepare-commit-msg
    $ ln -sf ${此项目路径}/php-code/hooks/commit-msg

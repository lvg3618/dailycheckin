# 本地使用教程

## 一、安装

```bash
pip install dailycheckin --user
```

## 二、编写 `config.json` 配置文件

参考[配置说明文档](https://sitoi.gitee.io/dailycheckin/settings/) ，并修改 `config.json`

## 三、单次运行

1. 运行全部脚本

    ```bash
    dailycheckin
    ```

2. 运行指定脚本（包含），可以同时选择多个，用「空格」分开

    ```bash
    dailycheckin --include MUSIC163_ACCOUNT_LIST BAIDU_URL_SUBMIT_LIST 
    ```

3. 运行指定脚本（排除），可以同时选择多个，用「空格」分开

    ```bash
    dailycheckin --exclude MUSIC163_ACCOUNT_LIST BAIDU_URL_SUBMIT_LIST 
    ```

## 四、更新

```bash
pip install dailycheckin --user --upgrade
```

# 文件介绍

1. `_coverpage.md`：背景设置
2. `_navbar.md`：右上角导航栏设置
3. `_sidebar.md`：侧边栏目录设置
4. `.nojekyll`：用于阻止 GitHub Pages 会忽略掉下划线开头**的文件**

# docsify
1. `{docsify-ignore}`和`docsify-ignore-all` 侧边栏不显示标题，使用例子：`# 不会显示在侧边栏{docsify-ignore}`

# windows下使用docsify
1. 下载并安装Node.js：https://nodejs.org/zh-cn/

2. 安装docsify-cli

    ```bash
    # 安装
    npm i docsify-cli -g
    # 验证
    docsify -v
    ```

3. 创建文件夹并执行命令

    ```bash
    mkdir docsify
    cd docsify
    docsify init ./
    ```

4. 运行服务器

    ```bash
    docsify serve ./
    ```

5. 浏览器输入

    ```bash
    http://localhost:3000/
    ```

# Vs code 编辑markdown实时预览
1. 打开命令行：`CTRL + SHIFT + P`
2. 输入：`markdown`
3. 选择：`打开侧边预览`
4. 按键：`CTRL + K` 
5. 按键：`V`

# git 操作
1. 添加到暂存区
   ```bash
   git add --all
   ```
   
2. 添加到本地仓库

   ```bash
   git commit -m "描述"
   ```

3. 推送到远程仓库

   ```bash
   git push git@github.com:TheJavaRookie/docsify.git
   ```

   


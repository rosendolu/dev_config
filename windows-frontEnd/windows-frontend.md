# windows-frontend development
## windows 系统设置

- 磁盘分区
- cmd颜色配置
- 任务栏设置
- 桌面壁纸

## 网络配置

- shadowsocks
  - [安装客户端](https://github.com/shadowsocks/shadowsocks-windows)
  - 配置节点
- vpn

## 开发环境配置

- ### [vscode](https://code.visualstudio.com/)

- [typora](https://typora.io/)

- [github desktop](https://desktop.github.com/)

- chrome

- chrome canary

- [node](https://nodejs.org/zh-cn/download/package-manager/#windows)
  
  - npm
  - nrm
  
  ```shell
  npm i -g nrm  // 安装
       
  nrm ls 
  
  nrm use 
  ```
  
- [git](https://git-scm.com/download/win)

  ```shell
  git config --list
  git config --global user.name "John Doe"
  git config --global user.email johndoe@example.com
  git config --global core.editor code
  ```

  ```shell
  配置了代理的情况下  
  git config --global http.proxy http://127.0.0.1:1080
  ```

  - git commit
    - [install](https://git-scm.com/download/win)

  ```shell
  npm install -g commitizen  // 安装
  
  npm install -g cz-conventional-changelog  // 安装 cz-commitizen-changelog
  
      // 直接在home路径下新建该文件，配置也可以
  echo { "path": "cz-conventional-changelog" } > c:\users\xxxx\.czrc   // windows系统
  
  git cz  // 替换git commit ，以后提交直接用 git cz
  ```

- licecap


- nvm-windows


- winRAR
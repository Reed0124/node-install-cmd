# node-install-cmd
个人常用 Node.js 安装、版本管理、环境配置指令集合

## 资源下载
### 安装包：
https://nodejs.org/zh-cn/download
<img width="1472" height="1074" alt="image" src="https://github.com/user-attachments/assets/b06b5822-7929-4711-b059-89b74ebe3f7d" />

### 全部默认一键安装，其中只需要将安装路径安装在D盘
<img width="572" height="93" alt="image" src="https://github.com/user-attachments/assets/2c90653c-36a2-4d61-8ee8-dcf99176c262" />

### 查看是否安装成功
<img width="871" height="480" alt="image" src="https://github.com/user-attachments/assets/c024c01b-4c4a-46e6-9a58-23e8e319d75e" />

### 修改 npm 的全局安装路径（防止C盘占用）和缓存路径
<img width="1067" height="769" alt="image" src="https://github.com/user-attachments/assets/9cd9da86-3204-4cbb-9850-e68b8721b6aa" />

## 修改相关配置（按 Win + X -> 选择 终端管理员）
### 解除 PowerShell 默认脚本禁用限制，让 npm 等全局命令正常运行，仅对当前用户生效
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
<img width="1481" height="760" alt="image" src="https://github.com/user-attachments/assets/51fde984-9b1e-49ad-b826-b6f2fe65993f" />

### 修改npm全局安装包的默认路径
npm config set prefix "D:\develop\nodejs\node_global"
### 修改npm全局缓存路径
npm config set cache "D:\develop\nodejs\node_cache"
### 查看是否修改成功
npm config get prefix
npm config get cache
<img width="1481" height="760" alt="image" src="https://github.com/user-attachments/assets/0af1ee69-ea3f-433d-9195-a1aa1e4f4b1a" />





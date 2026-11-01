# work

一个基于 Node.js 的示例项目。

## 安装说明

### 环境要求

- Node.js 18 或更高版本（推荐使用 LTS 版本）
- npm 9 或更高版本（随 Node.js 一起安装）

可以使用以下命令检查版本：

```bash
node -v
npm -v
```

### 安装步骤

1. 克隆仓库并进入项目目录：

   ```bash
   git clone https://github.com/LiangJie-0226/work.git
   cd work
   ```

2. 安装项目依赖：

   ```bash
   npm install
   ```

3. 启动项目：

   ```bash
   npm start
   ```

   开发时如需热更新，可改用：

   ```bash
   npm run dev
   ```

4. （可选）运行测试：

   ```bash
   npm test
   ```

启动成功后，在浏览器中访问 <http://localhost:3000> 即可查看运行效果。

### 常见问题

- **`npm install` 速度慢或失败**：可以切换 npm 镜像源，例如
  `npm install --registry=https://registry.npmmirror.com`。
- **端口被占用**：可通过环境变量指定端口，例如 `PORT=8080 npm start`。

# ng-uni

基于 uni-app 的跨端项目。

## 开发

```bash
# 安装依赖（按需选择包管理器）
npm install
# 或
pnpm install

# 启动 H5
npm run dev:h5

# 启动微信小程序
npm run dev:mp-weixin

# 构建 H5
npm run build:h5
```

> 具体可用脚本以 `package.json` 中的 `scripts` 为准。

## 目录结构

```
├── src/            # 源码（页面、组件、静态资源等）
├── manifest.json   # uni-app 应用配置
├── pages.json      # 页面路由与全局样式配置
└── package.json
```

## 许可证

见 [LICENSE](LICENSE)。

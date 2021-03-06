# vue-spa-template
基于 vue3 + typescript + webpack 的项目模板

## 特性

- [x] 开箱即用的项目模板
- [x] 代码风格统一（eslint/stylelint/prettier/commitlint/husky/EditorConfig）
- [x] 环境配置（dotenv）
- [ ] Mock server（mockjs）
- [ ] 异常监控（sentry）
- [ ] 单元测试（jest）
- [ ] 其他
  - [ ] 全局 less 变量

## 项目结构

```bash
.husky
public
env     # 环境配置文件
src
├─ __tests__    # 测试用例
├─ assets       # 静态资源（图标、图片、...）
├─ mock         # mock-server、mock 数据
├─ router       # 路由配置和文件
├─ service      # 接口配置和调用函数
├─ utils        # 工具函数
├─ components   # 公共组件
├─ views        # 页面
│  └─ Home.vue
├─ App.tsx
├─ index.tsx
package.json
yarn.lock
# ...此处省略了一些配置文件
```

## 注意

- vscode 建议安装 eslint、prettier、stylelint 插件

## 最后

该项目会持续更新，欢迎 comment ~

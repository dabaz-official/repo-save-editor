# R.E.P.O 存档编辑器

[<img src="https://flagcdn.com/w20/cn.png" alt="中国国旗"> 简体中文](./README.cn.md)

<div>
  <img src="src/app/icon.png" alt="R.E.P.O Save Editor Logo" width="200" height="200" />
</div>

## 总览

R.E.P.O 存档编辑器是一个用于编辑 R.E.P.O 存档文件的网络应用。这个工具帮助玩家来调整各种游戏参数，包括：

- 玩家统计和属性
- 运行状态和货币
- 已购买的物品和升级
- 团队设置与配置

## 技术

这个项目使用现代 Web 技术构建，包括：

- **Next.js 15** - 使用 App 路由的 React 框架
- **React 19** - UI 库
- **TypeScript** - 类型安全的 JavaScript
- **TailwindCSS 4** - 面向应用的 CSS 框架
- **next-intl** - 国际化支持
- **shadcn/ui** - 可使用的 UI 组件（基于 Radix UI）
- **Lucide React** - 好看且一致的图标库

## 开始

```bash
# 克隆原 GitHub 库
git clone https://github.com/luccasfr/repo-save-editor.git

# 进入项目路径
cd repo-save-editor

# 安装依赖项
yarn install

# 启动开发服务器
yarn run dev
```

在浏览器中打开 [http://localhost:3000](http://localhost:3000) 以查看应用。

## 如何使用

1. 找到你的 R.E.P.O 存档文件（通常在 `%USERPROFILE%\AppData\LocalLow\semiwork\Repo\saves`）
2. 上传存档文件到编辑器
3. 根据你的期望修改参数
4. 下载修改后的存档文件
5. 将旧存档文件替换为修改后的存档文件

## 致谢

由衷感激 [N0edL's R.E.P.O Save Editor](https://github.com/N0edL/R.E.P.O-Save-Editor) 提供了 Python 中带有密钥的加密功能，这些功能被提取并使用 Node.js 实现，最后用于本项目。

## Author

<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/luccasfr">
          <img src="https://github.com/luccasfr.png?size=200" alt="Lucas Ferreira" />
          <p>Lucas Ferreira</p>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/dabaz-official">
          <img src="https://github.com/dabaz-official.png?size=200" alt="DabAZ" />
          <p>DabAZ</p>
        </a>
      </td>
    </tr>
  </tbody>
</table>

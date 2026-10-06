# 鸿伴复盘 · 条款托管站

「鸿伴复盘」（HarmonyOS / HarmonyOS NEXT 应用）对外公示的法律文本静态站，用于 AppGallery Connect「隐私政策网址」及用户查阅。

## 目录结构

```
/
├── index.html              首页：两份协议入口与应用定性摘要
├── privacy-policy.html     隐私政策（发布稿）
├── user-agreement.html     用户协议（发布稿）
├── README.md
└── .nojekyll               关闭 Jekyll，HTML 原样发布
```

Pages 配置：Source 选 **Deploy from a branch**，分支 `main`、目录 **Root**。

## 访问地址

主链接走自定义域名（Cloudflare 前置，带 `.html` 的请求会 307 到无扩展名地址，所以对外一律给无扩展名这条）：

- 隐私政策 `https://honggufupan.juehuojue.com/privacy-policy`
- 用户协议 `https://honggufupan.juehuojue.com/user-agreement`
- 首页 `https://honggufupan.juehuojue.com/`

GitHub Pages 镜像：`https://xiegen2020.github.io/honggufupantiaokuan/`（同内容，用带 `.html` 的路径）。

## 内容与维护

- 纯静态 HTML：无 JavaScript、无外部字体与脚本、无统计与 Cookie、无第三方资源，与本应用"不联网、无第三方 SDK"的口径保持一致。
- 正文由应用工程文档生成，与端内「设置 - 隐私与安全」中的文本同源。**任何一处改动，母本、端内页面与本站点必须同批改**，并同步版本号与生效日期，否则应用市场会以"端内外不一致"驳回。
- 页面内出现的"本应用不收集任何个人信息""数据仅存储于用户设备本地"等表述，均对应应用代码的真实状态：应用未申请网络权限，亦未接入第三方 SDK。

## 主体信息

运营主体：临沂峰火澜山网络科技有限公司
联系邮箱：lanfengzhiwoyi@163.com
ICP 备案号：鲁ICP备2026021902号-4A

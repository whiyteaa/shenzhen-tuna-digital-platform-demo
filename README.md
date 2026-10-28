# 深圳国际金枪鱼交易中心 · 数字化交易平台 DEMO（发布站）

本仓库仅承载演示站点的**密文**文件。演示页与可下载资源在发布前已用访问密码加密，
未持密码者即使取得本仓库全部内容，也只能得到无法解读的密文。

- 演示站点：<https://whiyteaa.github.io/shenzhen-tuna-digital-platform-demo/>

访问需在页面输入密码，验证通过后由浏览器本地解密并渲染。

## 目录

| 路径 | 说明 |
| --- | --- |
| `index.html` | 密码验证页（登录门） |
| `config.json` | 解密参数（盐值、迭代次数、资源清单） |
| `credential.json` | 密码校验凭据（哈希，不含明文） |
| `page.enc` | 演示页密文 |
| `assets/*.enc` | 可下载资源密文 |

明文源码与内部测算资料托管于私有仓库 `shenzhen-tuna-digital-platform`。

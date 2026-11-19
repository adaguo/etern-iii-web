# ETERN.III 手碟馆预约网页版 — 临时预览

手碟馆预约网页版的临时预览，托管在 GitHub Pages 上，方便店主和朋友打开测试。

- 预览地址：`https://<你的 GitHub 用户名>.github.io/etern-iii-web/`（以仓库 Pages 设置页显示的为准）
- 数据层：Supabase（Postgres，新加坡区），页面直接连线上库，约课、取消、充值都会真实写库
- 登录：邮箱 + 密码（Supabase Auth）。测试账号分顾客、老师、店主三个身份，密码请向店主索取

## 测试账号（三个身份）

- 顾客：`customer@test.etern-iii.com`
- 老师：`teacher@test.etern-iii.com`（林老师，只看自己教的课）
- 店主：`admin@test.etern-iii.com`（登录后底部出现「管理」tab）

密码不放在公开仓库里，请向店主索取。测试账号仅供测试，上线前删除。

## 注意

- 这是临时预览，`index.html` 是从最新构建导出的静态快照；页面改动后需要重新导出再推上来
- 小程序源码在另一个仓库（`etern-iii-miniprogram`），不在这里
- 预览结束后可以直接删除这个仓库

# 家族星图 Family Star Map

- **查看（实时）**：`https://你的用户名.github.io/仓库名/` ——打开就是站长最新发布的资料，只能看，不能改。
- **编辑**：在网址后面加 `?edit=1`。编辑只保存在你自己的设备里，不会影响别人。

## 亲戚怎么补充 / 修改资料

**方法 A：导出后发给站长（最简单）**
1. 打开编辑链接，修改资料，点「导出数据」，得到 `data.json`。
2. 把文件发给站长（WhatsApp、微信、邮件都可以）。

**方法 B：在 GitHub 提交 Pull Request（需要 GitHub 账号）**
1. 先用编辑链接修改并「导出数据」。编辑链接总是从最新版本开始，不会改到旧资料。
2. 打开本仓库，点 **Add file → Upload files**，拖入 `data.json`（同名覆盖）。
3. 点 **Propose changes**，再点 **Create pull request**，写一句说明。

## 站长怎么合并
- **收到文件**：打开编辑链接，点「导入数据」，选择「合并」（同一个人以新文件为准，没有的会新增），检查无误后「导出数据」，用 **Add file → Upload files** 覆盖仓库里的 `data.json`。
- **收到 Pull Request**：点仓库的 **Pull requests**，打开那一条，在 **Files changed** 检查，再点 **Merge pull request → Confirm merge**。
- 1～10 分钟后网站就会显示新资料。

## 注意
- 两个人基于同一个旧版本各自修改，后合并的人可能覆盖先合并的人。合并后请通知其他亲戚「载入线上版本」再继续编辑。
- 本站不会自动保存到 GitHub，只有站长更新 `data.json` 后，所有人才会看到变化。

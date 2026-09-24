# kaiyulx.com — 凯域留学纪念页

## 上线到 GitHub Pages
1. 在 GitHub 新建一个 public 仓库，比如 `kaiyulx`，把这个文件夹里的所有文件上传进去（index.html、CNAME、images/）。
2. 仓库 Settings → Pages → Source 选 "Deploy from a branch"，Branch 选 `main` / `(root)`，保存。
3. GoDaddy → 域名 kaiyulx.com → DNS，删掉原来的 parking 记录（`@` 的 A 记录和 `www` 的 CNAME），然后添加：
   - A  `@`  185.199.108.153
   - A  `@`  185.199.109.153
   - A  `@`  185.199.110.153
   - A  `@`  185.199.111.153
   - CNAME  `www`  `<你的GitHub用户名>.github.io`
4. 回到 Settings → Pages，Custom domain 填 `www.kaiyulx.com`，等 DNS 生效（几分钟到几小时）后勾选 **Enforce HTTPS**。

## 换成吉卜力风格
把改好的图片按原名（01.jpg … 11.jpg）放进 images/ 覆盖即可，代码不用动。
图片说明文字在 index.html 里的 `slides` 数组中修改。

# tesla-fleet-key

Tesla Fleet API 公钥静态托管（GitHub Pages）。

- 对外只暴露 `/.well-known/appspecific/com.tesla.3p.public-key.pem`
- 私钥 `fleet-key.pem` 只在本地签名代理中使用，**永不入库**

启用 Pages：Settings → Pages → Source: Deploy from a branch → main / root，Custom domain 填 `tesla.qcgg.fun`。
[幽灵车尔尼桑的歌单（腾讯云静态网站托管）](https://ock.cn/j7tnh)

## 使用技术

python 利用excel 生成json

react + antd 前端

腾讯云静态网站托管 部署

## 本地部署指令

- 环境

```bash
pip install -r requirements.txt
npm install
```

然后根据个性化定制修改`歌单表格`、`src/App.tsx`和`public/index.html`相关内容

- 运行测试

```bash
npm run start
```

- 构建静态网页

```bash
npm run build
```

构建成功后会生成在`build`文件夹内

## 腾讯云静态网站部署

1. fork本仓库并进行修改，生成新json；
2. 按照腾讯云静态网站部署的步骤关联你fork的仓库进行部署。
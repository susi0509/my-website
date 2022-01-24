前提：
node.js版本 >= 14
npm安装，建议yarn的安装

安装命令：
npx create-docusaurus@latest my-website facebook

运行命令：
cd my-website
npx docusaurus start

默认启动端口3000，更改端口
npx docusaurus start --port 3001

跳转地址：
http://localhost:3000





# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.




---
sidebar_position: 1
---

# 基础配置

## 账号密码
### Git
``` js
yupeng.sun@newwinner.com.cn Syp2014Ss622
```

http://gitlab.yintech.net/rjhy/frontend/h5/hxg-app-h5/-/project_members

### 蓝湖
``` js
yupeng.sun@newwinner.com.cn net@cctv3
```

### 禅道

https://rhjs.techgp.cn/zentao/product-all.html

``` js
yupeng.sun Syp2025@Jfzt
```

### figma

``` js
yupeng.sun@newwinner.com.cn net@cctv3
```


### yapi

http://yapi.techgp.cn/

``` js
yupeng.sun@newwinner.com.cn net@cctv3
```

## 常见问题
1. 请使用`nvm`对`Node`进行管理
2. 各个项目能用的`Node`版本是有所不同，如果版本不对，构建失败请按照以下顺序重试

> 即使使用相同的 package.json，不同的 Node.js 版本（比如 18 和 16）也可能导致依赖的安装结果有所不同。

``` js
npm cache clean --force
rm -rf node_modules
npm install
```

3. 先运行

``` js
export NODE_OPTIONS=--openssl-legacy-provider
```

然后`npm run serve` ...
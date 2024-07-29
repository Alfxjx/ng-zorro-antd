# CARI

[2024-07-29]修改了分页时，无法约束输入小数的问题。（此问题后续的版本已更新，如果更新ng版本，可以切换回去用开源的主版本）

## build & publish

```
npm i --legacy-peer-deps
npm run build:lib

npm adduser -registry http://<ip>:<port>/repository/npm-host/
# 输入 账号密码

cd publish

npm publish -registry http://<ip>:<port>/repository/npm-host/

```

## notes 

后续如果要修改，需要修改 components/package.json 里的版本，注意不要和ng-zorro重复
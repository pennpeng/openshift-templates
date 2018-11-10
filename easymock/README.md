# 部署Easymock
Easymock模板是自己制作的
[Easymock地址](https://github.com/easymock/easymock)
## 部署之前请在先运行
oc adm policy add-scc-to-user anyuid -z easymock -n {{ namespace }}
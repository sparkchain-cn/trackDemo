#火花溯源的demo

#安装
npm install

#启动
npm start

#数据的上传
URL：http://localhost:8200/track/add
提交方式：POST
##数据格式
tracker:AAAAA
event:product
trackObjs:aaa,bbb,ddd

#数据查询
查询条件:按照trackObj完全匹配查询，会把区块链上对应hash返回，以便查询链上原始数据。

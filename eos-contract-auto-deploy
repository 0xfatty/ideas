# EOS智能合约自动部署


监听GitHub，有更新则自动打包，打包结束自动部署到目标网络


## 授权
* 创建setcode权限
* 授权setcode权限给系统账号

cleos set account permission contract.eos setcode '{"threshold":1,"keys":[],"accounts":[{"permission":{"actor":"autoset.eos","permission":"eosio.code"},"weight":1}]}
cleos set action permission contract.eos eosio setcode setcode

合约账号：contract.eos
部署账号：autoset.eos

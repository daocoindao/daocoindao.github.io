# daocoindao.github.io
## 基本描述
* 基于使能了SSL的TCP长连接
* 适用于MCU通过Modem连接服务器的通信模型
* 无特别说明，多字节数据使用小字节序

## 基本包格式

test     | Head | Length   | Data       | Check
-------- | --- | ------- | --------- | ----
Byte Size | 1    | 2        | Max: 1280  | 2
Comment   | 0xA5 | See | See    | See 





First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

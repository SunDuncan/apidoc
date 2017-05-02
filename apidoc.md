APIDOC >接口文档的规则
-------------------------------
*不涉及自定义规则的接口文档*
[详情请见官网](http://apidocjs.com)

|规则的名称|用法|
|:--------:|:--:|
|下载|npm install apidoc -g|
|运行|apidoc -i myapp/(文档目录) -o apidoc/(目标的目录)|
|宏定义一个接口|@apiDefine 名字|
|使用宏定义|@apiUse 名字|
|接口的类型（get,post,put）|@api {get/post/put} 路由 描述|
|定义每个单位接口的版本|@apiVersion 0.2.0|
|定义接口的名字|@apiName 接口的名字|
|定义分组|@apiGroup 分组的名字|
|每个接口所需要的参数|@apiParam {Number}(参数的类型) 名字 描述|
|接口成功的返回数据|@apiSuccess {String} 名字 描述|
|返回数据的样式|@apiSuccessExample 名字 \n HTTP/1.1 200 OK{}|
|接口失败的返回数据|@apiError {String}类型(可省略) 名字 描述|
|返回失败的数据样式|@apiErrorExample 名字 \n HTTP/1.1 404 Not Found {}|
|直接页面测试|@apiSampleRequest url|

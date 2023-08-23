# NationalUniversitiesJson
全国各省份大学JSON数据


#项目结构
public
-areas.json
-大学.json
universityCollecter
-spiders
--spiders.py
-datafliter.py
-areas.json
README.MD


#使用方法
#spiders.py 检索数据保存文件 -基于百度serach接口检索需要的数据
-ak:需要替换成自己申请的百度开发者ak
-file_name:保存的文件名
-request:可参考开发文档https://lbsyun.baidu.com/faq/api?title=webapi/guide/webservice-placeapi/district添加需要请求的参数
-school:可参考开发文档https://lbsyun.baidu.com/faq/api?title=webapi/guide/webservice-placeapi/district添加需要保存的参数

#datafliter.py 筛选检索后的文件，进一步筛选文件
-search:筛选的字段名，可根据自己需要进一步修改
-school:筛选后要增加的字段名

#运行
#spiders.py scrapy runspider spiders.py
#datafliter.py phthon datafliter.py

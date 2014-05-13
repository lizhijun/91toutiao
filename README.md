91toutiao
=========

The API of  91TouTiao.com  

Resource URL
------------
- http://91toutiao.com/api/{section}?per_page={pageSize}&page_th={pageNumber}

参数
----

参数名称                  | 描述
------------------------- | ------
**section**<br>*必需*     | 现在支持的参数值可以是(`hot`,`new`,`rising`,`controversial`,`top`)
**pageSize**<br>*必需*    | 每页加载记录条数，如`10`
**pageNumber**<br>*必需*  | 加载第几页，如：加载第一页，则写`0`

请求实例
--------

**GET** `http://91toutiao.com/api/hot?per_page=10&page_th=0`

        {
              data: [
                        {
                            score: "1",
                            hotness: "518.125",
                            id: "1901",
                            rid: "9pswf2",
                            title: "SAN网络性能问题排错指南",
                            content: "",
                            url: "https://community.emc.com/docs/DOC-33408",
                            thumbnail: null,
                            domain: "emc.com",
                            created: "1399950066",
                            username: "honeybee",
                            tag: "StartupNews",
                            comments: "0"
                            }
                    ]
        }

更多接口
--------
开发中，敬请期待！


最佳实践
--------
敬请期待！

官方网站
--------
[1GAOXIAO](http://91toutiao.com/)

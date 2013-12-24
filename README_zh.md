# [http://beego.me/products](http://beego.me/products)

beego 产品案例展示.

## 提交你的产品案例

1. 拉取这个库到本地:

    git clone https://github.com/beego/products

2. 把你的图片文件放到 `images/<product name>/<filename>` 下，请注意图片长宽不要超过 800px。

3. 在 projects.json 里增加一段变量属性:

        {
        	"Name": "Beego Web", // 案例名称
        	"Thumb": "beeweb/thumb.jpg", // 图片路径 （可选）
        	"Desc": "Beego official website", // 案例描述
        	"Url": "http://beego.me", // 案例URL地址
        	"Src": "https://github.com/beego/beeweb", // 项目源码地址 （可选）
        	"Submitter": "slene", // 你的名字
        	"Date": "2013-12-22"
        }

4. 发起一个 Pull Request 操作。

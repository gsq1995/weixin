# pdjusers
持续更新中。。。
大家一起学习下
如有错误，希望大佬们指正
#### 介绍
门店管理系统
1.消费者小程序
2.店长小程序
3.javaweb后台

#### 软件架构
软件架构说明


#### 使用说明
    前端界面使用了微信官方提供的css/js文件设置的组件
1. 消费者小程序功能：
    1.1. 发送code到后台，然后后台获取openid进行注册/登录
    1.2. 登录后可生成专属二维码供店主扫码操作（可刷新二维码）
        
    1.3. 点击关注公众号（）





    ![输入图片说明](https://images.gitee.com/uploads/images/2019/0412/164519_949b5c07_4920738.png "QQ截图20190412164410.png")
    ![输入图片说明](https://images.gitee.com/uploads/images/2019/0412/164537_1dec50a1_4920738.png "QQ截图20190412164433.png")





2. 店长小程序功能：
    2.1. 扫码获得顾客的code
    2.2. 填写表单发送信息到后台进行充值/消费操作
    2.3. 设置会员福利（满*送*）
        注：在小程序内进行满*送*计算，直接将最终结果发送到后台
        相关问题：操作成功与否的界面还未完成



    ![输入图片说明](https://gitee.com/uploads/images/2019/0411/185401_c6422755_4920738.png "QQ截图20190411185307.png")
    ![输入图片说明](https://gitee.com/uploads/images/2019/0411/202406_6fdb1b07_4920738.png "QQ截图20190411185227.png")    
    ![输入图片说明](https://gitee.com/uploads/images/2019/0411/202342_92ceb05c_4920738.png "QQ截图20190411185250.png")
    
3. java后台
    基于原生java代码
    消费者、店长注册、充值、消费等功能

4.注意事项
    1.项目设置中设置为不校验网址，可以访问未认证的ip地址
    2.会员小程序（消费者）的二维码是code形成的二维码，仅一次有效（继续操作须刷新二维码）
    3.目前充值/消费后余额须刷新（再次登录）后才能同步到会员小程序首页



目标功能还有：
    小程序须扫码并关注公众号才能到后台注册
    后台设置须关注的公众号
    店长小程序的满送功能只能暂时修改

#### 参与贡献

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request


#### 码云特技

1. 使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2. 码云官方博客 [blog.gitee.com](https://blog.gitee.com)
3. 你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解码云上的优秀开源项目
4. [GVP](https://gitee.com/gvp) 全称是码云最有价值开源项目，是码云综合评定出的优秀开源项目
5. 码云官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6. 码云封面人物是一档用来展示码云会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
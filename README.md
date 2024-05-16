# 支付宝免挂免ck无敌不掉线

背景：v免签收款需要时时刻刻的在手机上运行App,只能解决收款的90%问题,有时候还会掉线,这样处理很麻烦,


支付宝免CK添加操作稍微繁琐点，请耐心观看，此通道必须关闭你的余额宝自动转入功能，否则可能造成不跳转

1.打开支付宝开放平台
点击打开【支付宝开放平台】，点击右上角**【登录】**
https://open.alipay.com/

![image](https://github.com/japhet99/pay/assets/38454934/ae8b8b11-cb31-4c89-9068-c49706660216)


用手机打开支付宝，【扫码登录】

扫码登录完成后，点击右上角**【控制台】**


2.创建网页/移动应用

登录后，【点击网页/移动应用】- 然后点击**【创建一个网页/移动应用】**（一般会有一个默认的应用，直接用就行）如果没有就创建一个。
![image](https://github.com/japhet99/pay/assets/38454934/d96ec4ae-bb9b-4d58-933b-ed3359cb0def)

按照支付宝命名规范填写**【应用名称】，选择【绑定商家账号】，上传【应用图标】，点击选择【网页应用】，点击【立即创建】**。
![image](https://github.com/japhet99/pay/assets/38454934/923b57cb-d069-4956-a613-55a63284b808)


3.绑定基础功能产品
创建完成以后，点击**【产品绑定】-【去绑定】**
![image](https://github.com/japhet99/pay/assets/38454934/bee5e627-2331-4df9-9c95-ed532789be43)

点击**【全部】-【点击第二页】-【勾选基础功能产品】-【点击确定】，注意下里面有二十个权限集**，**【账单数据查询及账单下载服务】**这个权限一定勾选上
![image](https://github.com/japhet99/pay/assets/38454934/b29fdaab-23bb-4c00-8f05-0df9c7b05887)
![image](https://github.com/japhet99/pay/assets/38454934/81ae3e50-528a-471b-80d6-bef046f80df7)

4.生成秘钥/证书并配置
下载密钥生成工具安装完成后软件后，我们直接点生成 https://opendocs.alipay.com/common/02kipk

![image](https://github.com/japhet99/pay/assets/38454934/56a7a49c-70db-456e-9219-2459bdc53393)

![image](https://github.com/japhet99/pay/assets/38454934/682f7307-e70e-49fc-84eb-4044f5389362)

 生成完成后，我们回到开发设置，设置一下【接口加签方式（密钥/证书）】

![image](https://github.com/japhet99/pay/assets/38454934/46785a31-8023-4323-80dd-54b4a1478450)

点击秘钥，然后下一步

![image](https://github.com/japhet99/pay/assets/38454934/f6b18beb-778d-4d10-8e5b-8890b4a5ea4d)
![image](https://github.com/japhet99/pay/assets/38454934/d332011c-d46d-426e-a318-c0c02cc37884)
![image](https://github.com/japhet99/pay/assets/38454934/1ec2febc-2153-4ca7-b36a-6d80de1b11f8)
![image](https://github.com/japhet99/pay/assets/38454934/3e231b0b-6543-4aff-8c32-c4c2788a390f)
![image](https://github.com/japhet99/pay/assets/38454934/7587ce0b-2e04-40a7-a81e-6ad591e2e42e)
![image](https://github.com/japhet99/pay/assets/38454934/45521bd6-7c41-4b49-89a6-061ba3a51bea)
需要保存这个应用的APPID

这一步算是完成，接下来继续一下步获取用户PID

5.获取支付宝用户PID

点击右上角头像，再点击账户中心

![image](https://github.com/japhet99/pay/assets/38454934/8c0f778f-2411-4bf8-aad7-b838b976430c)
复制账户ID，保存
![image](https://github.com/japhet99/pay/assets/38454934/4359a118-3678-4f50-9482-3c74697f8ab5)

至此已经完成一半了，

说明一下需要保存的信息

1.需要下载保存支付宝公钥

2.需要保存由软件生成的支付宝应用私钥

3.需要复制保存应用AppID

4.需要保存用户的支付宝账户ID，也就是支付宝PID
注意：应用需要提交审核，上线才能正常回调使用

![image](https://github.com/japhet99/pay/assets/38454934/ac8c0e4d-765f-4d97-adbd-de4482996206)


等待审核完成，然后注册 https://ypay.byabstudio.com/ 


6.添加无敌免挂通道
点击【通道管理】-【通道列表】-【新增】-【选择支付宝通道类型】-【选择支付宝商家账单 / 选择无敌免挂通道模式】-【填写支付宝账号ID】-【填写支付宝应用APPID】-【填写支付宝公钥】-【填写支付宝应用私钥】-【点击提交保存】

![image](https://github.com/japhet99/pay/assets/38454934/e7f6d52b-0615-4fe9-bd0a-fc6ce8d653ed)

点击测试即可支付了

# modifyPositioning
更改iOS定位 swift

使用须知: 需要Xcode 需要Xcode 需要Xcode xcode运行完之后不要断开数据线 打开苹果地图 产看当前位置是否已经变更 然后断开数据线 查看当前位置是否是坐标位置 当需要正确位置时 需要重启手机 下次打卡依旧需要在xcode 重新编译重复上述步骤 不重启手机定位会一直保持在坐标位置

将坐标修改为公司坐标
![Image text](https://raw.githubusercontent.com/yiruchujian/modifyPositioning/master/image-folder/2.jpeg)
![Image text](https://raw.githubusercontent.com/yiruchujian/modifyPositioning/master/image-folder/4.jpeg)

选择 Edit Scheme
![Image text](https://raw.githubusercontent.com/yiruchujian/modifyPositioning/master/image-folder/1.png)
选择Run -> Options -> Defailt Location 选择本地 Location 文件
![Image text](https://raw.githubusercontent.com/yiruchujian/modifyPositioning/master/image-folder/2.png)


定位改为永久定位 一次安装后定位一直在设置位置 当需要正确当前位置时需要 关机重启 

下次使用需要再次在xcode运行

# FacePinball
FacePinball
在人脸上玩桌面弹球，眨眼睛会操纵对应的棒子回击小球。目前还只实现了最基本的功能。
闭眼的判定是通过计算眼睛的histgram
小球碰撞到嘴，鼻梁，和脸部轮廓时会反弹。
操作方法

    运行
    选中一帧当做初始化帧（一定要选则正面睁眼的，俗话说：初始选得好，老公......呸，程序稳定跑），根据opencv的输出来决定，决定了就按‘Y’,重新选就‘N’
    开始游戏吧

非常脆弱，请保持您的脸正对着摄像头，不然会挂，真的会
（本来眼睛想做个左眼进右眼出的传送门的，下次，下次，下次一定）
（pygame现学现卖）
就凑合玩玩？

预览视频：
https://www.bilibili.com/video/BV1Fv41167XM/
更多资讯：
https://aistudio.baidu.com/aistudio/projectdetail/518861

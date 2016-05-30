# Wap-Dialog
由于wap的弹框是调用系统组件的，因此ios/android/各种浏览器的alert表现形式都不一致。
为了用户体验，被我重写了一遍

##usage
dialog.js 仅包含一个function，
目前弹框有3种样式
1:普通的一个按钮的弹框
2:普通的两个按钮的弹框
3:类似微信已完成自动消失的弹框

var type1 = {  
>	"head": "",  
>	"content": "请填写金额",  
>	"type": "2",  
>	"cancel":function(){},  
>	"confirm":function(){}  
};  

var type2 = {  
>	content:"2555",  
>	cancel:function(){}  
};  

var type3 = {  
>	"content": "已完成",  
>	"type": 3  
}  

dialog(type1);

[运行DEMO](http://www.luoyongjie.cn/mygit/Wap-Dialog)

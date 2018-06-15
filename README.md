# UIView-MixColor

运行时绑定属性的一个小分类，可以设定UIView子类两种状态的边框颜色，背景色，UIButton,UILabel的文字颜色

默认边框宽度1.0


self.button.normalBorderColor = [UIColor grayColor];

self.button.selectBorderColor = [UIColor blueColor];

self.button.normalTextColor = [UIColor lightGrayColor];

self.button.selectTextColor = [UIColor cyanColor];

self.button.normalBackColor = [UIColor whiteColor];

self.button.selectBackColor = [UIColor grayColor];


 - (IBAction)onButtonClick:(UIButton *)sender {
    
    sender.mixSelected = !sender.mixSelected;
}

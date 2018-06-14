# UIView-MixColor

self.button.normalBorderColor = [UIColor grayColor];
self.button.selectBorderColor = [UIColor blueColor];

self.button.normalTextColor = [UIColor lightGrayColor];
self.button.selectTextColor = [UIColor cyanColor];

self.button.normalBackColor = [UIColor whiteColor];
self.button.selectBackColor = [UIColor grayColor];


- (IBAction)onButtonClick:(UIButton *)sender {
    
    sender.mixSelected = !sender.mixSelected;
}

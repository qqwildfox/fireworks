# birthday
祝福html

部分源码fork自https://github.com/louislivi/fireworks
  
  https://qqwildfox.github.io/fireworks/ 仍可预览但没有图片
思路或注意如下
	52张jpg2张gif(Why?)，通过递归setTimeout更换body背景和遍历数组更换title,img对象是为了提前载入缓存而避免切换白屏
	验证身份时可以给不同或预设的人展示定制内容，例如隐藏版本，特殊原因我选择了跳转，亦可以通过函数实现
	prompt()因为在华为等部分手机上可能存在bug导致未经过输入即返回null，引入bootstrap采用了模态框的方式，引入jQuery则是因为下面有选择器当时没得时间删了
	如果记得没错的话，QQ上可以显示title10个字，微信可以15个字
	token是6个3位数组成的一维数组，18位数(Why?)，诸君可以删除
	预览时候别被吓到

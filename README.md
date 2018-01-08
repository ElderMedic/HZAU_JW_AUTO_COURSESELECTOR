#华农正方教务选课/评教工具
forked from xiaohuanshu/zhengfang-xuanke
1.8 update：修改了登陆url

# python2.7 required 


#original readme.md below

# zhengfang-xuanke
正方教务系统刷课/评价工具

# 自动刷课xuanke.py目前功能
* 自动刷课
* 验证码登录
* 课程信息查询
* 失败重试
* 是否选择教材

# 自动评价pingjia.py目前功能
* 自动评价
* 将一个评价设为『比较满意』其余为『非常满意』从而防止全部相同而无法保存
 
# 使用方法
* 安装pquery(pip install pquery)
* 验证码显示需要安装pillow,没安装jp2a的在根目录找二维码
* 编辑修改host为正方教务系统地址
* 如果登录时报错，尝试更改loginpage为default5.aspx或者default3.aspx

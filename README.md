# jsonToDart
 json快速转dart模型的一个html文件
 支持自定义类名
 对于复杂的json文件
 子类名为父类名+字类名的大写驼峰式
 

# 使用方法
  [在线地址](https://awagege.github.io/jsonToDart/)
  你也可以克隆index.html文件在本地使用
 ![演示](https://github.com/awagege/jsonToDart/blob/master/demo.png?raw=true)
 
# 已知问题
  转换功能由js提供，在js中，本人因才学疏浅，没有能够比较 0.00与 0 的对比方式
  因此0.00   10.00 等类似均会被转定义成 int型
  请避免出现类似等于整型的浮点型数字，或在转换成功后手动更改
  类似0.1   0.01  的浮点型正常

---
title: markdown语法 #文章标题
date: 2018-08-28 10:51:36
tags:   #文章标签
- markdown
- 教程
categories: #文章分类
- 语法
cover_picture: images/600.jpg #文章封面图
---
# 标题
-------------
标题分为一到六级，分别为1~6个#，#后面需要带上一个空格

# 引用
写法一：
> 书是人类进步的阶梯
别看了，其实只有上面这一句

写法二：
> 书是人类进步的阶梯
> 别看了，其实只有上面这一句

嵌套引用：
> 天王盖地虎
>> 宝塔镇河妖
>>> 小鸡炖蘑菇

# 代码块
下面是一段js代码：
```javascript
for(var i=0;i<10;i++){
    console.log(i);
}
```
下面是一段css代码:
```css
body{
    color:red;
    font-size:12px;
}

```

# 超链接
[点我](http://www.baidu.com)跳转到百度

# 图片
```
引入图片方法：    ！[图片名字](图片链接)
```
![表情包](http://f.hiphotos.baidu.com/image/pic/item/8435e5dde71190efebe14415c41b9d16fcfa60e6.jpg)
##图片超链接
```
[![图片名字](图片地址)](超链接地址)
```
[![表情包](http://f.hiphotos.baidu.com/image/pic/item/8435e5dde71190efebe14415c41b9d16fcfa60e6.jpg)](http://www.baidu.com)
# 列表
## 有序列表
1. 手机
2. 电脑
3. pad

## 无序列表
* 小米
* 华为
* 魅族

# 表格

姓名|排行|特长|
-|-|-
刘备|老大|哭
关羽|老二|打
张飞|老三|骂
# 前言

欢迎来到基于SSM的文学网站设计与开发项目！该项目旨在为广大文学爱好者提供一个便捷、高效的文学作品的阅读与分享平台。在本项目中，我们采用了Java语言及Spring、Springmvc、MyBatis等主流框架，结合前端技术如JS、Vue和CSS3，为您打造出一个功能丰富、界面美观的文学网站。

# 内容介绍

本项目主要包括以下几个模块：首页、作品列表、作品详情、用户中心等。用户可以在首页查看推荐作品，按分类或标签筛选感兴趣的作品，还可以在作品详情页进行阅读和评论。用户中心提供了个人信息管理、阅读记录、收藏等功能，让用户能够更好地管理自己的阅读体验。

# 技术介绍

- 语言：Java
- 使用框架：Spring、Springmvc、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下是项目中的一段核心代码，展示了如何使用MyBatis实现作品列表的查询：

```java
// WorkMapper.java
public interface WorkMapper {
    @Select("SELECT * FROM work WHERE category_id = #{categoryId}")
    List<Work> getWorksByCategoryId(@Param("categoryId") int categoryId);
}
```

```xml
<!-- work-mapper.xml -->
<mapper namespace="com.example.mapper.WorkMapper">
    <select id="getWorksByCategoryId" resultType="com.example.entity.Work">
        SELECT * FROM work WHERE category_id = #{categoryId}
    </select>
</mapper>
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/336586/11/7722/127319/68bbcfa5F253e3480/f3ea436eae7e078d.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/326314/16/16859/64957/68bbcf7cF99c67ab9/45d3ceacf65160fa.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/332326/7/10143/50020/68bbcf7cFdff32a37/4175b6b802ca35b5.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/329127/12/10202/69086/68bbcf7dFf2e35387/0bd1a2067461d6be.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/329078/39/10081/56900/68bbcf7dFed85d770/a71aa7db25b6b242.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/346916/27/216/54450/68bbcf7eFc8f74ae3/a3f9cb19b6b12fd3.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/323470/14/17058/30277/68bbcf7eF9985bcca/5ed000932465e746.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/326230/2/17147/34886/68bbcf7eF12b69af9/dca743ee4a1148e9.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/340349/12/7219/41580/68bbcf7fF4dab0230/96d2f931b70723c7.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/325145/6/16536/55792/68bbcf7fF7af3e077/6874ab9577b65e80.jpg)


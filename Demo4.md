# MarkDown 链接 图片 引用 和代码块的综合

## 链接
### 内嵌式链接
- 外部链接：[百度](http://www.baidu.com)  
- 内部链接:1,链接仓库的其他文件:[Demo1](Demo1.md)
- 内部链接:2,链接本文档的其他部分:[代码块](Demo4.md#代码块)

### 引用式链接

- 外部链接：[百度]  
- 使用百度别名:[baidu]
- 内部链接:1,链接仓库的其他文件:[Demo1]
- 内部链接:2,链接本文档的其他部分:[代码块]


## 图片


- 图片的 MarkDown 语法  
    ![alt](url text)  
- 外部图片  
![baidu log](https://www.baidu.com/img/bd_logo1.png "百度LOGO") 
- 内部图片  
![风景图](images/timg.jpg)  

- 外部图片  
![baidu log][baidu_logo]  
- 内部图片  
![风景图][open_png]  

## 引用

## 代码块

```` java

public static void main (string[] args){
    
    int i = 10;
    int j = 20;
    System.out.println (i + j);
    
}

````

```` html

<html>
<head><title>This is a html document</title></head>

<body>
    <div algin="center">
    Hello welcome HTML world!
    </div>
</body>

</html>

````

<html>
<head><title>This is a html document</title></head>

<body>
    <div algin="center">
    Hello welcome HTML world!
    </div>
</body>

</html>

<!--- 下面是本文档中用到的链接 -->
[百度]:http://www.baidu.com
[baidu]:http://www.baidu.com
[Demo1]:Demo1.md
[代码块]:Demo4.md#代码块
[baidu_logo]:https://www.baidu.com/img/bd_logo1.png
[open_png]:images/timg.jpg

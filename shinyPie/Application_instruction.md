---
title:
output: 
  html_document:
    keep_md: TRUE
---



<h1><center>使用说明</center></h1>
 

## **1.pie2D**

**1.1 点击Browse上传本地数据，数据的格式应符合下列要求。**

**数据应只有两列且两列生物顺序是固定的，列名是可以选择的。**.  
**第一列**: **数据种类。**
**第二列**: **百分比。**  
 

**数据的格式应该和下面一样。**  


```
 chr	percent
chr1	30
chr2	20
chr3	10
chr4	15
chr5	25
```

**1.2 点击Go运行这个应用，就会出来饼图。**

**1.3 数据颜色**

**数据颜色是让饼图之间数据不单调，变得明显。用于渲染数据的颜色，可以由应用程序随机分配，也可以由用户指定。默认情况下，将使用shinypie指定的颜色。若要自定义数据的一种颜色，用户应给每个数据选择颜色。** 

**1.4 标题**

**用户可根据自己的爱好命名饼图**

**1.5 列数**

**列数是数据有几列，用户可凭自己的爱好通过改变[1，10]中的一个整数，1为一个数值单位，来调整数据排成几列。**


## **2.pie3D**

**2.1 点击Browse上传本地数据，数据的格式应符合下列要求。**

**数据应只有两列且两列生物顺序是固定的，列名是可以选择的。**.  
**第一列**: **数据种类。**
**第二列**: **百分比。**  
 

**数据的格式应该和下面一样。**  


```
 chr	percent
chr1	30
chr2	20
chr3	10
chr4	15
chr5	25
```


**2.2 点击Go运行这个应用，就会出来饼图。**

**2.3 数据颜色**

**数据颜色是让饼图之间数据不单调，变得明显。用于渲染数据的颜色，可以由应用程序随机分配，也可以由用户指定。默认情况下，将使用shinypie指定的颜色。若要自定义数据的一种颜色，用户应给每个数据选择颜色。** 

**2.4 标题**

**用户可根据自己的爱好命名饼图**

**2.5 爆裂度**

**爆裂度是饼图之间饼块的距离，可通过改变[0，1]中的一个十进制数，0.2为一个数值单位，用于调整饼块之间的距离。**  


**2.6 半径**

**半径是控制饼图大小，可改变[0，1]中的一个十进制数，0.1为一个数值单位，用于调整饼图的半径。**  


**2.7 标签大小**

**标签大小是每个数据在饼图中呈现的大小，可通过改变[0，1.5]中的一个十进制数，0.1为一个数值单位，用于调整数据在图中的大小。**  


**2.8 倾斜度**

**倾斜度是改变饼图在背景中的倾斜情况，可通过改变[0，1]中的一个十进制数，0.1为一个数值单位，用于调整饼图的倾斜度。**  

**2.9 L列数**

**列数是数据有几列，用户可凭自己的爱好通过改变[1，10]中的一个整数，1为一个数值单位，来调整数据排成几列。**

## **3.下载**
**在完成饼图编辑之后，可以将饼图下载到本地，本应用程序提供了两种下载文件，分别是pdf和svg文件格式，用户可根据喜好选择下载。**

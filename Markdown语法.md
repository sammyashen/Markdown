# 一级标题

## 二级标题

### 三级标题

###### 六级标题（#号后要加空格）



## 有序列表

1. 打开冰箱（.后加空格）
   1. 开机（升级Tab，降级shift+Tab）
2. 把大象放进冰箱
3. 关闭冰箱



## 无序列表

* 水果（*或-后加空格）

  * 苹果（升级Tab，降级shift+Tab）

  * 梨子
  * 菠萝
    1. 国产菠萝
    2. 进口菠萝

* 肉类



## 任务列表

- [ ] 引导学生重新审视笔记的价值（-、[、]后面都要加空格）
- [x] 讲解笔记的正确定位
- [x] 讲解优秀笔记的标准
- [x] 笔记工具的选择



## 插入表格

1. 创建表头

   * （|学号|姓名|性别|，加回车）

     | 学号 | 姓名 | 性别 |
     | :--: | :--: | :--: |

2. 添加一行

   * 只需按下Ctrl+回车即可

     | 学号 | 姓名 | 性别 |
     | :--: | :--: | :--: |
     | 001  | 张三 |  男  |
     | 002  | 李四 |  女  |



## 文本

#### 斜体

*hello world*（两个*内包裹内容）

_hello world_（两个_内包裹内容）

#### 粗体

**hello world**（两个**内包裹内容）

__hello world__（两个_ _内包裹内容）

#### 删除线

~~hello world~~（两个~~内包裹内容）

#### 下划线

* Markdown没有原生的下划线语法，需要用html的语法

<u>**hello world**</u>

#### 空格

* 普通的空格，我们能可以使用space键即可，如果空格太多的话，就可以使用&nbsp；
* 是space空格，不换行，对于中文展示稳不稳定，比如行首空两格，也就是两个字用起来就不方便。
* &ensp；是半角空格，1/2个中文字符宽度。
* &emsp；是全角空格，1个中文字符宽度。

> &nbsp;&nbsp;&nbsp;&nbsp;李白。
> &ensp;&ensp;李白。
> &emsp;&emsp;李白。

#### 横线

* "---"在单独的一行即可，也可以<hr/>

---

<hr/



## 行内代码

`java`是一门优秀语言，`C++`也是一门优秀语言；



## 代码块

* 创建方式：```代码类型 或 ~~~代码类型

```java
public class helloworld{
    public static void main(String[] args){
        System.out.println("hello world");
    }
}
```

~~~c
void main(void)
{
	while(1)
    {
        Loop();
    }
}
~~~



## 元素类操作

#### 插入图片

![img](Markdown语法.assets/1112222-16325463259041.png)

#### 插入超链接

* [百度](www.baidu.com)，使用“[]()”，[]里面写要展示的名字，小括号里面写url。

#### 引用

* 使用“>”，如果有多行，可以将多个>放在每一块行的开头一起使用，可以嵌套使用。

* > ​			少年行
  >
  > > ​			李白
  >
  > 五陵年少金市东，银鞍白马度春风。
  >
  > 落花踏尽游何处，笑如胡姬酒肆中。

#### emoji

* 如果是win10系统，使用==win+.==就会弹出emoji表情，也可使用==:xx:==的方式，比如:smile:，:100:，:diamonds:，😁等等，这个需要系统和编辑器支持。

#### Video

* 直接使用==<video>==标签即可，其中的src写具体的视频的地址，绝对路径，相对路径，网络url都可以。
* 本地视频：

<video src="./测试.mp4"/>

* 网络视频：

<iframe src="//player.bilibili.com/player.html?aid=548183777&bvid=BV1Vq4y1P7pC&cid=413807573&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>


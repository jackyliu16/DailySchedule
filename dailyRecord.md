# Record information

> this file document record my learining in rust and rcore-os
> by my schedule, this study will be start in 22/7/5 which being impacted by my "software design implementation" in scnu

### day 0 - 2022/7/4
> 完成第零章的程序环境配置
> 
> 完成Rust环境本地搭建
> 
> 完成Rustling下载
> 
> 学习到Rust圣经2.2.1
> 
> finish all exercise in rustlings Variable chapter

### day 1 - 2022/7/5
> 由于要回学校搬东西占用了较长时间，因此没有太多时间（在车上看了圣经）
> 
> 圣经看到2.4
> 
> 圣经配套的联系完成到{4.1, 4.2}
> 
> rustlings finish { None }

##### the question in study

BY： https://zh.practice.rs/basic-types/numbers.html
```rust
fn main() {
    let x: i32 = 5;
    let mut y = 5;

    y = x;
    
    let z = 10; // 这里 z 的类型是? 
}
```
> 产生这种情况的原因在于x: i32 and y: u32 there is not the same so mut y will not been give the value of x;

2. 在Rust中如果出现强制类型转换则`as u16`
3. 发现在rust的学习中，是真的需要经常做笔记，以记录一些信息方便我们进行记忆（否则找文档实在太痛苦了）

1. 当 ！用作返回值的时候，表示该函数永不返回（ 往往用作可能导致panic的函数）
2. 可以用`loop{}`创建一个简单的无限循环，永不跳出
3. _ 代表匹配一个值，但是我们不关心具体的值是什么
4. ```rust
   for i in 1..5 {
    println!("{}", i);
   }
   // 与
   for i in 1..=5 {
    println!("{}", i);
   }
   ```
   的区别在于一个是[0, 5) 另外一个是[0, 5]
5. Unicode 的编码都是4B的，因此字符类型也是4B的

### day 2 - 2022/7/6

> 今天在深度体会到之前我对于很多事情都忘记的情况之后，决定重新开始学习（从头开始学习）
>
> 在飞书文档中对于我的学习进行记录https://e3vqhv9jh5.feishu.cn/docx/doxcnCSj3n6UnHJHThzhv07Dbbh
>
> 当天同时发现了rustlings 之前我所完成的测试机制不太正确，重新上传了这个测试中我已经做完的部分
>
> 完成了圣经配套练习中一直到borrowing的部分

### day 3 - 2022/7/7

> 今天通过测试驱动性学习方案，完成了rustlings一直到error的练习，目前已经push了较早版本，等待较晚时间再反过来复习圣经的内容

### day 4 - 2022/7/8

> 今天仍然采用测试驱动型学习方案，上班摸鱼了一天，现在完成到rustling的standard libary type 章节，准备明天继续向下完成其他的内容。
> 
> 同时今天还发现了一个非常好的，通过数据结构来解释rust中各种数据的构造的视频[https://b23.tv/WHZ1oS0], 也更深的理解到rust的所有权管理机制*对于所有保存于heap中的数据，都必须存在为于stack上的指针或者说所有者。*

### day 5 - 2022/7/9

> 完成rustlings 到conversion章节（大概是80左右的位置，忘记具体的位置了）
> 
> 阅读完成了rust course的基础章节（其实前面在做的时候也有兼着把其他的部分看完，只不过看的相对没有那么系统性

### day 6 - 2022/7/10
> 完成了rustlings
> 
> 安装完成lab的环境
> 
> 准备接下来通过跟着rust by example 的课程对于rust语言的使用有进一步的理解
> 
> 阅读完成计算机组成原理与设计【学习版链接：https://www.cnblogs.com/studyingzhang/p/14661692.html】第一章，以及第二章到2.5章为止的内容
> 
> 阅读，并参考代码实现了用户态的简易开发环境的配置[https://github.com/jackyliu16/MyRustOs-baseOnrCore-Tutorial-]

### day 7 - 2022/7/11

> 完成了较多内容，不知道从何说起【实际上也有点忘记了】
> 
> 首先，阅读了计算机组成原理的内容，阅读到2.7的样子
> 
> 然后，进一步的阅读了实验指导书中的内容，看到第二章批处理的样子

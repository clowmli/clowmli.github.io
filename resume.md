---
layout: page
title:哈喽
subtitle: An awesome person
---

<span style="float: right; "><a href="{{ '/assets/resume.pdf' | prepend: site.baseurl }}"><strong>> Download as PDF</strong></a> </span>
<br>

### css
   - 含义：（层叠式）样式表
   - 引入方式："link"标签  --- 外联（推荐使用）
   - 在head标签中书写<style> --- 内嵌（做测试使用）
   - styles属性值就是css代码 ----内联（一般不使用 除当你的属性需要临时添加外） 
 - 书写规范 
   -  选择器规范 你要为页面中的哪一块设置样式
   - 样式书写规范
     ````css
     *{
        属性名 ：属性值
     }
     div{
        属性名 ：属性值
     }
     .table{
        属性名 ； 属性值
     }
     #table{
        属性名 ： 属性值
     }
     ````
 - 基础选择器
  - <*>通配选择器
  - <tagName>标签选择器 直接使用标签名
  - <className>. class选择器 给标签添加一个class标签名
  - <idName># id选择器 给标签添加一个id属性  同一个id名在同一个页面中只可以出现一个 （css书写规范）
- 基础选择器优先级
id>class>tag>*

### 常见属性整理

- 文本属性

- 盒子模型
  - 内边距属性
  - 外边距属性
  - display属性

- 布局属性
    - 表格属性（最原始的属性）
        - 优点：宽度根据内容而定
        - 缺点：不能够适配
    - 定位布局 （使用于微小布局；运用在前端主键中）
       - 优点：最方便，最快捷的开发 /直观且游离于主文档流而布局
       - 缺点：适配难度较高
       - position属性
         - absolute 绝对定位（脱离文档流)
          - 参考点： 离当前最近的一个position属性不为normal（没设position属性 默认属性）的元素的左上角为参考点，如果当前元素父级元素都为normal时，则以body的左上角为参考点
          - 在文档流的位置会被占据
         - reletove 相对定位 (为绝对定位提供参照物 )
         - fixed 固定定位
      - 辅助属性 top - bottom - left - right 不设置 left top 都为0
    - 浮动布局 （适用于pc端网页）
       - 优点：可以实现简单的布局，脱离主文档流；（最适合pc端）
       - 缺点：手机端布局限制比较大
       - float属性
          - letf
          - right
    - 弹性盒子布局 （一般使用于手机端）
    - 优点：适用于手机端和pc端；自动控制一个元素的宽高
       - display: flex

- 边框属性

- 背景属性
### 11nux命令
- 下载软件命令
- apt-get(主命令)
   - 1.将网站中所有的软件基本信息下载下来
   - 2.安装过程中会从以上下载下来的基本信息中筛选
优点：节省时间，提高效率
- install nginx 
 - nginx -v(查看版本)
 - apt-get update更新本地软件信息
- 备份
- cp 复制
 - :w 保存  ：q退出
 # vim
 - yy复制
 -  dd删除
 -  p粘贴
 -  u撤回
- a/A I/i 编辑模式
- esc键退出编辑模式

- rm 删除目录
- service nginx start 启动 
- service nginx restart重启
- mkdir 创建文件夹
-  touch新建文件
-  pwd查看当前文件路径
- cd 切换 
- ls查看
- ll
- 权限
	- chmod -R 777 目录路径（访问网站需要将网站根目录设置为777权限）
	- 读 写 执行分别被安排的数字为4 ，2 ，1
 
### 
 - css
 -  css常见属性
 - llnux命令

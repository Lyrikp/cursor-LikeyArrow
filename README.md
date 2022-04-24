<p align="center">
  <img alt="LikeyArrow" src="/Arrow.png" width="128">
</p>
<p align="center">一款「简约」「透明」「泛用」的隐式可爱替换鼠标ฅ^. .^ฅ</p>
<p align="center">I think here should be some English but I forget how to spell fanyongxing</p>

为Lyrikp.art自建网站绘制的一款简单、不透明度、泛用性的替换鼠标  

> 所以不介意的话请时不时来关注一下我的网站 [lyrikp.art](lyrikp.art)

全部采用 `.cur` 标准 windows 光标格式进行绘制，有多种风格可以选择

<p align="center">
  <span>详细说明: </span>
  <a href="https://lyrikp.art/2021/07/23/Design-LikeyArrow/">LikeyArrow</a> [style-like]
</p>

<p align="center">
  <span>实际应用：</span>
  <a href="https://lyrikp.art/">Likey‘s blog</a> [style-like] |
  <a href="https://kuuhaku.top/">熊之记事本</a> [style-kuma]
</p>
<p align="center">
  <img alt="LikeyArrow" src="/Preview.png" width="400">
</p>

## 快速使用

**目前支持 链接引用图片/手动加载cur格式 的形式进行使用**

自建网站一般都通过调用图片的形式修改网站鼠标样式  
通过cdn生成的网络连接可以直接引入png格式的图片，添加进各种网站配置文件当中  

> - [x] 测试通过 Windows 光标样式配置
> - [x] 测试通过 [Hexo](https://hexo.io/) 驱动 [yun](https://github.com/YunYouJun/hexo-theme-yun) 主题
>
> - [x] 测试通过 [Hexo](https://hexo.io/) 驱动 [Volantis](https://github.com/volantis-x/hexo-theme-volantis) 主题

使用链接示例

```bash
# 默认大小 默认鼠标样式/Size normal Default
https://cdn.jsdelivr.net/gh/Lyrikp/cursor-LikeyArrow/LikeyArrow/LikeyArrow-default/Default.cur

# https://cdn.jsdelivr.net/gh/Lyrikp/cursor-LikeyArrow/LikeyArrow/风格样式/光标种类.cur
```

[cdn全部预览](https://www.jsdelivr.com/package/gh/Lyrikp/cursor-LikeyArrow)

[默认Deafult 样式预览](https://www.jsdelivr.com/package/gh/Lyrikp/cursor-LikeyArrow?path=LikeyArrow-default%2FPreview)

<p align="center">
  <img alt="LikeyArrow" src="/LikeyArrow-default/Preview/preview.png" width="400">
</p>

[Style-like 样式预览](https://www.jsdelivr.com/package/gh/Lyrikp/cursor-LikeyArrow?path=LikeyArrow-style-like%2FPreview)

<p align="center">
  <img alt="LikeyArrow" src="/LikeyArrow-style-like/Preview/preview.png" width="400">
</p>

[熊熊kuma 样式预览](https://www.jsdelivr.com/package/gh/Lyrikp/cursor-LikeyArrow?path=LikeyArrow-style-kuma%2FPreview)

<p align="center">
  <img alt="LikeyArrow" src="/LikeyArrow-style-kuma/Preview/preview.png" width="400">
</p>
## 光标样式

- [x] Default 默认
- [x] Link 点击链接
- [x] Unavailable 不可用
- [x] Zoomin 放大
- [x] Zoomout 缩小
- [x] Handwriting 手写
- [x] IBeam 选定文本

----

- [x] Resize 窗口拉伸
  - [x] Size1 上下拉伸
  - [x] Size2 左右拉伸
  - [x] Size3 左下右上
  - [x] Size4 左上右下
  - [x] Resize 全方位
- [ ] Copy 复制
- [ ] Cut 剪贴
- [ ] Help 帮助事项
- [ ] Wait 加载中
- [ ] Midroll 中间滚轮
  - [ ] Rollup 向上滚动
  - [ ] Rolldown 向下滚动
  - [ ] RollAll 自由滚动

## 待办事项

- [x] 基础网站搭建可用 `.png` 样式
- [x] `.cur` 格式绘制
- [x] 投影差分风格
- [x] 颜色差分风格
- [ ] 猫咪差分风格
- [ ] 动态样式绘制
- [ ] 切换动画设置
- [ ] `Windows` 安装脚本 `.inf` 编写
- [ ] 终极目标： `MacOS` 中更改鼠标样式

## 私人订制

#### style-kuma

> 阴影不透明度设置成60，祝你门门都及格 —— Like  
> 那我谢谢你 —— Kuuhaku

为Kuuhaku私人订制了属于他的风格配色指针方案  
全透明+阴影形式的default样式以及适应网站配色的 **<font color=#819ff7>蔓长春花蓝</font>** link样式  
前期因为**懒**，只添加了4项样式  
<font size=1>我可没说是谁懒</font>  

现在已经完成了基本样式的绘制了w

> **详情参见 [style-kuma](/LikeyArrow-style-kuma)**  

## 标准设计参数

- Size: 32×32 px
- 透明度规范: 90/80/74/50%
- 线条规范: 9/7/4px
- color: **<font color=#2C2C2C>#2c2c2c</font>**  **<font color=#ffffff>#ffffff </font>**  **<font color=#fc5555>#fc5555</font>**  **<font color=#f8a4a4>#f8a4a4</font>**
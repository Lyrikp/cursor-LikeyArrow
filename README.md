<p align="center">
  <img alt="LikeyArrow" src="/Arrow.png" width="128">
</p>

<p align="center">一款简约风格、不透明度、泛用的隐式可爱替换鼠标ฅ^. .^ฅ</p>
<p align="center">I think here should be some English but I forget how to spell fanyongxing</p>

为Lyrikp.art自建网站绘制的一款简单、不透明度、泛用性的替换鼠标
分别有不同的大小样式，以匹配不同环境下的需求。请按照自己的需求选择3种样式大小

> 所以不介意的话请时不时来关注一下我的网站 [lyrikp.art](lyrikp.art)

<p align="center">
  <span>实际应用：</span>
  <a href="https://lyrikp.art/">Like‘s blog</a> [style-like] |
  <a href="https://kuuhaku.top/">Kuuhaku'blog</a> [style-kuma]
</p>

## 快速使用

**目前仅支持链接引用图片的形式进行使用**

自建网站一般都通过调用图片的形式修改网站鼠标样式  通过cdn生成的网络连接可以直接引入png格式的图片，添加进各种网站配置文件当中

> 测试通过 [`Hexo`](https://hexo.io/) 驱动 [`yun`](https://github.com/YunYouJun/hexo-theme-yun) 主题配置

使用链接示例

```bash
# 默认大小 默认鼠标样式/Size normal Default
https://cdn.jsdelivr.net/gh/Lyrikp/cursor-LikeyArrow/LikeyArrow/Size-normal/Default.png
```

其他样式的链接格式

```bash
https://cdn.jsdelivr.net/gh/Lyrikp/cursor-LikeyArrow/LikeyArrow/Size-尺寸[light/normal/blod]/鼠标样式[Default/Link/Unavailable/...].png
```

## 指针样式

- [x] Default 默认
- [x] Link 点击链接
- [x] Unavailable 不可用
- [x] Zoomin 放大
- [x] Zoomout 缩小
- [x] Handwriting 手写
- [ ] IBeam 选定文本

----

- [ ] Resize 窗口拉伸
  - [ ] SizeNS 上下拉伸
  - [ ] SizeEW 左右拉伸
  - [ ] SizeNESW 左下右上
  - [ ] SizeNWSE 左上右下
  - [ ] SizeAll 全方位
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
- [ ] `.png` 全格式绘制
- [ ] `.cur` 格式绘制
- [ ] 投影差分风格
- [ ] 颜色差分风格
- [ ] 猫咪差分风格
- [ ] 动态样式绘制
- [ ] 切换动画设置
- [ ] `Windows` 安装脚本 `.inf` 编写
- [ ] 终极目标： `MacOS` 中更改鼠标样式

## 私人订制

#### style-kuma

为Kuuhaku私人订制了属于他的风格配色鼠标方案  全透明+阴影形式的default样式以及适应网站配色的黄绿色link样式  因为**懒**，只更改这两项  （我可没说到底是谁懒）

```bash
# default
https://cdn.jsdelivr.net/gh/Lyrikp/cursor-LikeyArrow/LikeyArrow-style-kuma/Default.png
# Link
https://cdn.jsdelivr.net/gh/Lyrikp/cursor-LikeyArrow/LikeyArrow-style-kuma/Link.png
# Handwriting
https://cdn.jsdelivr.net/gh/Lyrikp/cursor-LikeyArrow/LikeyArrow-style-kuma/Handwriting.png
```

> 阴影不透明度设置成60，祝你门门都及格 —— Like  那我谢谢你 —— Kuuhaku

## 标准设计参数

- Size: 
  - light 25×25px
  - normal 37×37px
  - blod 45×45px
- 透明度规范: 90/80/74/50%
- 线条规范: 9/7/4px
- color: #2c2c2c #fff #fc5555 #f8a4a4
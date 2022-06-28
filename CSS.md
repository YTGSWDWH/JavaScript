# CSS

## 内联模式：在HTML元素中使用"style"属性
## 内部样式表：在HTML文档头部head区域使用style元素
## 外部引用：使用外部CSS文件（推荐）

### 简单选择器
```css
  p {
    color: red;    其中p为选择器，color为属性，red为属性值
  }
```
### 类选择器
```css
  <p class = "paragraph extra-para">Hello world</p>
  
  .paragraph {
    color: brown;
  }
  .extra-para {
    font-size: 30px;
  }
```
### id选择器
```css
  <p id = "para">Hello world</p>
  
  #para {
    color: green;
  }
```

### 属性选择器
```css
  <img
    src = "img/123.jpg";
  />
  
  img[src] {
    width: 100px;
  }
```

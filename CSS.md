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

### 伪类选择器
```css
  <a href = "">点我跳转</a>
  
  a:hover {
    color: red;
  }
```

### 后代选择器
```css
  <div>
    <span>Span1
      <span>Span 2</span>
    </span>
  </div>
  <span>Span 3</span>
  
  span {
    background-color: white;
  }
  
  div span {
    background-color: blue;
  }
```

### CSS盒模型
* 内容区域content
* 内边距区域padding
* 边框区域border
* 外边距区域margin

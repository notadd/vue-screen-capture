# vue-screen-capture

基于[html2canvas](https://github.com/niklasvh/html2canvas)的Vue截图、标注组件。

## How to use
### step-1

#### 安装 `@notadd/vue-screen-capture`
+ `npm install @notadd/vue-screen-capture -S` 

#### step-2

+ 引入组件

```javascript
  import ScreenCapture from '@notadd/vue-screen-capture';
```

#### step-3

+ 声明component
```javascript
  export default {
  ...,
  components: {
    ScreenCapture
  },
  ...,
```

#### step-4

+ 使用组件

```html
<screen-capture ref="sc" :html="html"></screen-capture>
```

### 说明：

#### 组件属性
> `html`：要截图的dom元素

#### 组件方法
> `capture`：生成截图    
> `clear`：清空截图    
> `getCaptureImage`：返回截图File对象    

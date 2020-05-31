# All options

None of them are required, call `addBackToTop()` without params to get nice default looks

```js
addBackToTop({
  // 设置设置背景颜色
  backgroundColor: '#000',

  // 设置角偏移量，值越大离右边和下边越远，单位 px
  cornerOffset: 20,

  // 设置按钮的直径，单位 px
  diameter: 56,

  ease: inOutSine, // any one from https://www.npmjs.com/package/ease-component will do

  id: 'back-to-top',

  innerHTML: '<svg viewBox="0 0 24 24"><path d="M7.41 15.41L12 10.83l4.59 4.58L18 14l-6-6-6 6z"></path></svg>',

  // 设置点击后滚动到哪个位置，单位 px，
  // 结合 showWhenScrollTopIs 可以实现从顶部跳转到底部
  onClickScrollTo: 0,

  scrollContainer: document.body, // or a DOM element, e.g., document.getElementById('content')

  // 设置滚动速度，取值越大滚动速度越慢，单位 ms
  scrollDuration: 300,

  // 设置与屏幕顶端距离多少时显示按钮，单位 px
  showWhenScrollTopIs: 1,

  // diameter 的别名（alias for diameter），设置按钮的直径
  size: diameter,

  // 设置按钮上的文字的颜色
  textColor: '#fff',

  zIndex: 1
})
```

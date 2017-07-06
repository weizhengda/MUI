
1. MUI是什么？

* MUI，是一款可用开发高性能App的框架，也是目前最接近原生App效果的框架，可以有效解决HTML5原生开发中遇到的部分问题，同时体积也小


2. 为什么要用MUI开发APP项目？
 
 * 跨平台，一套代码搞定android,ios
 * 开发周期大大缩短
 * 开发成本比原生低很多
 * 开发效率高

3. MUI的缺点？

 * ui，适合在它这套ui中可以做出来的app，如果app有太多不同就没戏了
 * js，当真是画虎不成反类猫，坑很多

4. 使用MUI遇到过的坑？

* 使用了下拉刷新后  

```html
  <div class="mui-scroll"></div>
```

   这里面的内容，所有的a标签都的href都无法正常跳转，div，span，a ，i  等等这些标签里面的onlick 事件和 click 都无法执行。只有在button上面绑定click事件是可以执行的，或者绑定mui的tap事件。

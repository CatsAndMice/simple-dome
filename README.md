> 记录日常中有趣的前端效果

## 行星公转自转
> 效果展示:<a href="https://lihai-boop.github.io/simple-dome/%E8%A1%8C%E6%98%9F%E8%87%AA%E8%BD%AC%E4%B8%8E%E5%85%AC%E8%BD%AC/main.html">https://lihai-boop.github.io/simple-dome/%E8%A1%8C%E6%98%9F%E8%87%AA%E8%BD%AC%E4%B8%8E%E5%85%AC%E8%BD%AC/main.html</a>

行星自转与公转出现的3D效果主要是使用了css3`transform-style: preserve-3d;`属性，它将平面效果转化成3D效果
**注意：**
`transform-style: preserve-3d;`使用在父元素身上，而不是子元素本身。否则3D效果出不来

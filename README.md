## 实现功能
* 拓扑图的加载
* 工具栏、鼠标右键菜单
* 多种类型节点、连线的添加/删除
* 节点的图片的缩放与调整
* 鼠标经过节点显示相关属性信息
* 拓扑图节点命名

## 项目依赖
* [jQuery](https://jquery.com/)
* [jTopo.js](http://www.jtopo.cn/)
* [layui](http://www.layui.com/)
其中layui用于本项目的页面布局和组件，非必须。

## 项目结构
```
.
├── json                    // json数据
├── screenshots             // 项目截图(无用)
├── static
|   ├── font-awesome-4.7.0
|   ├── jquery-3.3.1
|   ├── jtopo-0.4.8
|       ├── jtopo-0.4.8-dev.js                 // jtopo源码,已经过修改
|       └── jtopo-0.4.8-dev(带注释版报错).js    // 本项目优化了一部分源码,故不要使用这个包,仅辅助解读源码用
|   ├── layui-2.3.0
|   └── public             // 本项目的静态文件
|       ├── css                                // 样式文件,根据实际项目修改
|       ├── img                                // 拓扑图引用图片,根据实际项目修改
|       └── js                                 // jtopo-editor.js为二次封装代码,如需在vue等框架中使用,可适当进行修改
|
├── network_topology.html // demo页面
├── 其它
|
```

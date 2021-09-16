# 心得

## ReactJS中初始化ECharts时，option不能为空null

否则会出现：

```bash
Error setOption should not be called during main process
```

详见：

【已解决】ReactJS中ECharts出错：util.js Uncaught in promise Error setOption should not be called during main process

## ReactJS中更新ECharts的option时，确保最开始初始化和后序更新时，都是同一种类型

不要出现，开始初始化为二维柱状图，后序更新设置的却是一维柱状图

否则会出现显示的异常，显示出多余的内容

详见：

【已解决】ReactJS中ECharts中水平柱状图中第一列的提示内容显示多余内容

## setState去更新值，立刻就去使用被改变的值，有时候会出现没有立刻获取到新值

想要确保获得更新后的值，可以使用setState的callback

详见：

[【已解决】ReactJS中setState去更改值但无效该值没有立刻改变](http://www.crifan.com/reactjs_setstate_value_not_work_not_right_now_immediately_changed)


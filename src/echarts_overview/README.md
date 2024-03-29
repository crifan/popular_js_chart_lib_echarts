# ECharts概览

* 一句话描述：`ECharts`是一个使用`JavaScript`实现的功能极其丰富的开源可视化库
* 最大特点：涵盖各行业图表，满足各种需求
* 历史：
  * 最早是百度开发的
    * 旧版是`v2`系列，后来升级到`v3`，以及之后的`v4`
      * 但现在旧版网页均已不在，都合并到Apache中了
  * 后来归入Apache组织
    * ECharts 遵循 Apache-2.0 开源协议，免费商用
      * 主页
        * Apache ECharts
          * https://echarts.apache.org/zh/index.html
      * GitHub
        * apache/incubator-echarts: A powerful, interactive charting and visualization library for browser
          * https://github.com/apache/incubator-echarts
* 浏览器支持
  * ECharts 兼容当前绝大部分浏览器（IE8/9/10/11，Chrome，Firefox，Safari等）及兼容多种设备
* 特性
  * 丰富的可视化类型
    * 提供了常规的折线图、柱状图、散点图、饼图、K线图，用于统计的盒形图，用于地理数据可视化的地图、热力图、线图，用于关系数据可视化的关系图、treemap、旭日图，多维数据可视化的平行坐标，还有用于 BI 的漏斗图，仪表盘，并且支持图与图之间的混搭。
  * 多种数据格式无需转换直接使用
    * 内置的 dataset 属性（4.0+）支持直接传入包括二维表，key-value 等多种格式的数据源，此外还支持输入 TypedArray 格式的数据。
  * 千万数据的前端展现
    * 通过增量渲染技术（4.0+），配合各种细致的优化，ECharts 能够展现千万级的数据量。
  * 移动端优化
    * 针对移动端交互做了细致的优化，例如移动端小屏上适于用手指在坐标系中进行缩放、平移。 PC 端也可以用鼠标在图中进行缩放（用鼠标滚轮）、平移等。
  * 多渲染方案，跨平台使用
    * 支持以 Canvas、SVG（4.0+）、VML 的形式渲染图表。
  * 深度的交互式数据探索
    * 提供了 图例、视觉映射、数据区域缩放、tooltip、数据刷选等开箱即用的交互组件，可以对数据进行多维度数据筛取、视图缩放、展示细节等交互操作。
  * 多维数据的支持以及丰富的视觉编码手段
    * 对于传统的散点图等，传入的数据也可以是多个维度的。
  * 动态数据
    * 数据的改变驱动图表展现的改变。
  * 绚丽的特效
    * 针对线数据，点数据等地理数据的可视化提供了吸引眼球的特效。
  * 通过 GL 实现更多更强大绚丽的三维可视化
    * 在 VR、大屏场景里实现三维的可视化效果。
  * 无障碍访问（4.0+）
    * 支持自动根据图表配置项智能生成描述，使得盲人可以在朗读设备的帮助下了解图表内容，让图表可以被更多人群访问

# 星状图 散列图 树状图

## sunburst-book

地址：

Examples - Apache ECharts (incubating)

https://echarts.apache.org/examples/zh/editor.html?c=sunburst-book

效果：

![echarts_demo_sunburst_book](../assets/img/echarts_demo_sunburst_book.png)

## 星状图 放射状 人物关系图

### 人物关系图

代码：

```js
option = {
    title: { text: '联系人图谱' },
    tooltip: {
        formatter: function (x) {
            return x.data.des;
        }
    },
    series: [
        {
            type: 'graph',
            layout: 'force',
            symbolSize: 80,
            roam: true,
            edgeSymbol: ['circle', 'arrow'],
            edgeSymbolSize: [4, 10],
            edgeLabel: {
                normal: {
                    textStyle: {
                        fontSize: 20
                    }
                }
            },
            force: {
                repulsion: 2500,
                edgeLength: [10, 50]
            },
            // draggable: true,
            draggable: false,
            itemStyle: {
                normal: {
                    color: '#4b565b'
                }
            },
            lineStyle: {
                normal: {
                    width: 2,
                    color: '#4b565b'

                }
            },
            edgeLabel: {
                normal: {
                    show: true,
                    formatter: function (x) {
                        return x.data.name;
                    }
                }
            },
            label: {
                normal: {
                    show: true,
                    textStyle: {
                    }
                }
            },
            data: [
                {
                    name: '我',
                    des: '',
                    symbolSize: 100,
                    itemStyle: {
                    normal: {
                        color: 'red',
                    }
                }
                }, 
                {
                    name: '侯亮平',
                    des: '',
                    symbolSize: 40,
                    itemStyle: {
                        normal: {
                            color: 'blue'
                        }
                    }
                },
                {
                    name: '祁同伟',
                    des: '',
                    symbolSize: 50,
                    itemStyle: {
                    normal: {
                        color: 'blue'
                    }
                }
                },
                {
                    name: '高小凤',
                    symbolSize: 50,
                    itemStyle: {
                    normal: {
                        color: 'blue'
                    }
                }
                }, 
                {
                    name: '吴惠芬',
                    des: '',
                    symbolSize: 70,
                    itemStyle: {
                        normal: {
                            color: 'blue'
                        }
                    }
                },
                {
                    name: '陈海',
                    des: '',
                    symbolSize: 60,
                    itemStyle: {
                        normal: {
                            color: 'blue'
                        }
                    }
                },
                {
                    name: '赵东来',
                    des: '',
                    symbolSize: 60,
                    itemStyle: {
                        normal: {
                            color: 'blue'
                        }
                    }
                },
                {
                    name: '梁璐',
                    des: '',
                    symbolSize: 60,
                    itemStyle: {
                        normal: {
                            color: 'blue'
                        }
                    }
                },
                {
                    name: '陈岩石',
                    des: '',
                    symbolSize: 70,
                    itemStyle: {
                        normal: {
                            color: 'blue'
                        }
                    }
                },
                {
                    name: '李达康',
                    des: '',
                    symbolSize: 60,
                    itemStyle: {
                        normal: {
                            color: 'blue'
                        }
                    }
                },
                {
                    name: '高小琴',
                    des: '',
                    symbolSize: 50,
                    itemStyle: {
                        normal: {
                            color: 'blue'
                        }
                    }
                },
                {
                    name: '陆亦可',
                    des: '',
                    symbolSize: 50,
                    itemStyle: {
                        normal: {
                            color: 'blue'
                        }
                    }
                },
                {
                    name: '吴心怡',
                    des: '',
                    symbolSize: 40,
                    itemStyle: {
                        normal: {
                            color: 'blue'
                        }
                    }
                },
            ],
            links: [
                {
                    source: '我',
                    target: '侯亮平',
                    name: '',
                    des: '侯亮平是我的得意门生'
                }, {
                    source: '我',
                    target: '祁同伟',
                    name: ''
                }, 
                {
                source: '我',
                target: '高小凤',
                name: ""
                },
                {
                source: '我',
                target: '吴惠芬',
                name: ""
                },
                {
                source: '我',
                target: '陈海',
                name: ""
                },
                {
                source: '我',
                target: '赵东来',
                name: ""
                },
                {
                source: '我',
                target: '梁璐',
                name: ""
                },
                {
                source: '我',
                target: '陈岩石',
                name: ""
                },
                {
                source: '我',
                target: '李达康',
                name: ""
                },
                {
                source: '我',
                target: '高小琴',
                name: ""
                },
                {
                source: '我',
                target: '陆亦可',
                name: ""
                },
                {
                source: '我',
                target: '吴心怡',
                name: ""
                },
            ]
        }
    ]
};
```

效果：

![echarts_demo_people_relation](../assets/img/echarts_demo_people_relation.png)

### graph-npm

Examples - Apache ECharts

https://echarts.apache.org/examples/zh/editor.html?c=graph-npm

效果：

![echarts_demo_graph_npm](../assets/img/echarts_demo_graph_npm.png)

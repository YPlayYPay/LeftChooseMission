# LeftChooseMission

![show gif](https://github.com/Luciahelloworld/LeftChooseMission/raw/master/chooseMenu.gif)  

展示的方式，将LeftChooseMission的整个文件下载到本机，然后直接打开index.html就可以显示了

完成这个mission用时12个小时。

以下这三个要求都完成了  

1. 点击清空:清空所有选项(所有选项都变成unchecked)

2. 点击部门左侧checkbox:toggle所有子目录下checkbox以及部门的checkbox  

3. 点击单个岗位checkbox:toggle点击的checkbox



动态计数功能在browserifyDemo中已经实现了

收获:  
1.react根据json的格式动态的生成DOM元素,文章发表在了https://segmentfault.com/a/1190000004189415
2.componetWillReceiveProps的用法  
    对于componentWillReceiveProps:function(props){  
          this.setState({  
            "checked":props.checked (注意这里不是this.props.checked)因为this.props.checked是旧值,而props.checked是新值  
                })  
          }

# SimulationData
## road_data
```
LKBH:           路口编号
JKDFX:          进口道方向
FNODE&TNODE:    路段起点路口编号&路段终点路口编号，相当于路段的索引
CDGN:           车道行驶方向
LDCD:           车道长度，m
```

## signal_data
```
LKBH:           路口编号
XWH:            相位号
JKDFX:          交叉口方向
FNODE&TNODE:    路段起点路口编号&路段终点路口编号，相当于路段的索引
CDZ:            车道行驶方向，和road_data中的CDGN一致
GREEN:          绿灯时长，秒
OFFSET:         绿灯相对信号灯周期的时间偏移，秒
CYCLE:          信号灯周期
```


## trip_input 
```
HPHM:           车辆编号
STIME:          车辆出发时间，格式hh:mm:ss
PATH:           车辆路径集合（路段索引,分隔符“->”）
FX:             车辆路径集合（路段转向序列, 分隔符“->”）
```
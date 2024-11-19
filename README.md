区别

LuckDraw_start.js
每次转动 起始位置都从Index= 0 开始

LuckDraw.js
每次转动 起始位置出于上一次的抽奖的结果的位置开始 index= lastStopIndex


// 使用示例

myLuckDraw = new LuckDraw(this.prizeList, 3, 15); 

myLuckDraw.run(index，runing, runend) 

index = 中奖下标 
runind 运行时回调 
runend 运行结束回调 

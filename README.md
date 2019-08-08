# CountDown
uni-ui 的 CountDown 倒计时组件 完善了动态赋值

倒计时组件，组件名：uni-countdown，代码块： uCountDown。

时间参数直接动态赋值即可
使用方法：
<uni-countdown :day="date.day" :hour="date.hour" :minute="date.minute" :second="date.second" :show-colon="false"  @timeup="timeup"></uni-countdown>

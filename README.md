<h1>PPPPL</h1>

<h3><LPP的web代码存放处啦></h3>

<h4><以下是总结啦></h4>

<TASK_1>
</TASK_1>

<TASK_2><br />
  1.可以在网页里调试。<br />
</TASK_2>

<TASK_3><br />
  1.具有相同属性的放在一个大括号里（如padding boder margin background等）。<br />
  2.float是浮在父元素框内（不是爷爷元素框内..更不是..）的左右，本次实验用到两次。<br />
  3.块状元素的margin是可以重合的！如果不是块状元素就用display:block！最上面和最下面的两个元素就单独设置margin:0px就好了！<br />
  4.用了float就相当于浮起来了，正常情况下父元素会随着子元素的延伸而伸长（不看隔代只看子）。但是浮起来的子元素并不包括在内，所以这时候就要用到   overflow:auto，使其超过（over）浮起来的元素（flow），而达到平面视觉上的延长。如本实验的tbody的使用。<br />
</TSASK_3>

<h2>LPPのweb代码存放处</h2>

<h4><以下是总结啦></h4>

<TASK_1>
</TASK_1>

<TASK_2><br />

  1.可以在网页里调试。
  
  2.line-height是行高，height就是高，通常height是对于某个框架或者图片来弄的，line-height用于文字。line-height和height组合到一块儿，有一种效果，就是如果把它们的值设置的一样了，文字就会在垂直方向居中，如本实验的footer。 
  
  3.没有必要对每一个box进行定位，因为其本来就默认是流动模型，顺着就下来了，又由于是块状元素，其margin本来就是重合的。
  
  4.本题中的百度logo和导航都是用padding margin float来进行定位。其中导航不是float li,而是float ul（整体）。
  
  5.新学到了box-shadow: 2px 2px 0.5px 1px rgb(160,160,160)(用于盒子);text-decoration: none（用于链接）;list-style-type:none（用于列表）;border-collapse: collapse（用于表格合并线框）;
  
</TASK_2>


<TASK_3><br />

  1.具有相同属性的放在一个大括号里（如padding boder margin background等）。
  
  2.float是浮在父元素框内（不是爷爷元素框内..更不是..）的左右，本次实验用到两次。
  
  3.块状元素的margin是可以重合的！如果不是块状元素就用display:block！最上面和最下面的两个元素就单独设置margin:0px就好了！
  
  4.用了float就相当于浮起来了，正常情况下父元素会随着子元素的延伸而伸长（不看隔代只看子）。但是浮起来的子元素并不包括在内，所以这时候就要用到   overflow:auto，使其超过（over）浮起来的元素（flow），而达到平面视觉上的延长。如本实验的tbody的使用。
  
  5.大多数的时候都用id选择器来取唯一的名字，但是当样式统一的时候，就用类选择器（class）统一编制。
  
</TASK_3>


<TASK_4><br />
  
  1.若是没有规定固定长度宽度，可以用规定上下左右都移动25%来实现居中（ top: 25%;left: 25%;bottom:25%;right: 25%;）。<br />
    但是本题规定了长宽，就只能用固定公式法：先让矩形移动到右下角区域（top:50%;left: 50%;），再移动其自身长度宽度的一半（	margin-top: -100px;	    margin-left: -200px; ），以实现居中。
    
  2.需要这里用到了圆的式子，与方形的唯一不同就是加了-radius。
  
<TASK_5>
<hr />
<h5>愿不负时光不负己</h5>

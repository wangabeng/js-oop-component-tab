# js-oop-component-tab
基于面向对象的组件开发，写tab切换。settings，events（包括自定义事件），methods（原型方法）三者配合使用来写常见的组件。

通过配置参数settings对象{
		idname:'',
		eachShowIndex:null,
		events:'click',
		delay:''
	}，设置不同组件的当前默认显示索引值，默认第一个是激活状态,tab1默认第二个是激活状态;
  
  通过events不同，设置通过鼠标点击还是鼠标移入切换选项卡，通过settings的delay设置是否延迟显示;
  
  通过原型方法为tab4添加显示内容并自动刷新内容的功能。
  
为第四个选项卡添加2个自定义事件，一是在选项卡切换之前添加beforeTab自定义事件，弹出当前的索引值，二是在切换后添加afterTab自定义事件弹出切换后的索引值。

备注：这个案例是妙味的面向对象组件开发的最后一任务，参考了原作者用jQuery的实现思路，我用原生的js自己实现的。



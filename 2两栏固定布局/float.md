### css float

#### 1、脱离文档流

当子级使用浮动时，子级脱离文档流，但是子级的内容依然给子级保留位置并紧贴着子级

*node：*
*这与position的absulate不一样，positon的absulate脱离文档流后，子级的内容不给子级保留位置直接占据子级位置。*

#### 2、float 副作用

##### 1)背景不再显示
背景颜色background-color与背景图片background-image由于该子元素不在他的包围之内，导致父级的背景不显示

##### 2)边框撑不开
同1，由于脱离父级包围，边框无法撑开

##### 3)margin padding不能正确显示



同1，由于脱离文档流。

#### 3、清除浮动的方式

##### 1)对浮动元素设置恰当宽高


##### 2)clear:both


##### 3).class:after,.class:befor{content:'';display:block}
.class{zoom:1}/*确保ie6、7一致*/



由于这不是代码，所以  css enjoy! ☋♉♈
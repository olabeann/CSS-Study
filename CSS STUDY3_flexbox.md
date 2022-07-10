<h1> CSS </h1>

<h3>1. diplay</h3>

![image-20220706152743049](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706152743049.png)

-> span 값이 안나오는 이유는, span에는 입력값이 있어야 결과가 나오기 때문

![image-20220706153021834](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706153021834.png)

-> span 태그에 값을 입력하고 css를 적용하면 화면에 표시가 된다.

원래 div는 한줄에 한칸씩 나오는데 display값을 inline-block으로 주게 되면 한줄에 블록이 여러개 표시된다.



![image-20220706153119215](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706153119215.png)

-> span은 기본이 inline인데, display값을 block으로 주면 div와 같이 표현된다.

![image-20220706153236069](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706153236069.png)

-> div display에 inline만 주게 되면 화면에 아무런 표시를 주지 않는데 이것은 <div></div> div 태그 안에 아무 값도 주지 않았기 때문

-> 값을 주게되면 값을 준 크기만큼 background 컬러가 표시되어 표현된다.



<h3>2. position</h3>

![image-20220706153605662](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706153605662.png)

-> position : relative로 변경하면 left와 top에 준 값이 적용됨.

![image-20220706153656649](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706153656649.png)

-> .box의 경우에도 position:relative; 적용하니까 원래 있던 자리에서 20px씩 옮겨감



* relative : 원래 있던 자리에서 적용한 px만큼 이동하는 position 



![image-20220706153829503](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706153829503.png)

-> position : absolute;



* absolute : 아이템이 담겨 있는 상자 안에서 적용한 px만큼 이동 

![image-20220706153945429](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706153945429.png)

-> position : fixed;



* fixed : 상자 안에서가 아니라 페이지 안에서 적용한 px만큼 이동 

![image-20220706154047668](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706154047668.png)

-> position : sticky



* sticky : 원래 있던 자리를 유지하되 스크롤링 했을 때에도 그 자리에 고정됨.




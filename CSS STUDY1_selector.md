<h1> CSS </h1>

<h3>1. 의미, 정의</h3>

CSS : Cascading Style Sheet

- Cascading : 영어의 정의로는 '작은 폭포', '폭포처럼 쏟아지는 물' 등으로 연속적으로 흐름이 생기는 의미
  1. Author style : css 기본으로 스타일을 지정하는 것 
  2. User style : 사용자의 스타일에 맞게 브라우저에 스타일을 바꾸는 것 (다크모드 등)
  3. Browser : 브라우저상에서 지정한 스타일

-> 위에서부터 우선순위를 가지고 사용자에게 디자인을 보여준다.

💥 !important : 위 디자인의 연결고리를 끊어버리고, 무조건 자신의 디자인이 중요하다고 선언하는 것 

 -> 현업에서는 bad smell 이라고 말함. 보통의 경우는 important는 사용 x



<h3>2. 선택자 selectors</h3>

* **Universal ***  전체를 다 선택하는 것 
* **type Tag**   Tag를 선택한다는 것. ex) div
* **ID**  #id
* **Class**  .class
* **State ** :
* **Attribute** []

[실습]

![image-20220706143758581](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706143758581.png)

CSS를 작성할 때 기본적으로 아래처럼 작성

```css
selector {

property : value;

}
```



1. 전체 컬러 green으로 표현

   ![image-20220706144042156](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706144042156.png)

2. li태그는 blue로 표현

   ![image-20220706144128363](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706144128363.png)

3. special 이라는 id를 가진 값을 핑크로 표현

![image-20220706144235772](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706144235772.png) 

+추가적으로 h1 hello라는 태그를 만들어 id를 special로 지정하면 함께 pink로 표현

![image-20220706144343191](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706144343191.png)

4. red 클래스 yellow로 표현

![image-20220706144522486](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706144522486.png)

- div가 red인데, div에는 아무 값도 없으므로 아무 변화가 없다. 이럴 때 변화를 주기 위해서는 width와 height값 지정

![image-20220706144641563](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706144641563.png)



5. button에 마우스를 올렸을 때 색상 효과 주는 것 (hover)

![image-20220706144859265](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706144859265.png)



6. link 있는 값 purple로 표현

   ![image-20220706145117622](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706145117622.png)

+추가적으로 link중 naver.com link만 purple 표현

![image-20220706145420546](C:\Users\DABIN2\AppData\Roaming\Typora\typora-user-images\image-20220706145420546.png)

+ naver로 시작하는 href에 표현하려면 [href ^= "naver"]
+ .com로 끝나는 href에 표현하려면 [href $= ".com"]



8. id가 special인 것들 중에서 li 태그에 있는 것만 핑크색으로 표현하고 싶다면 #special에 앞에 li를 붙여서 li #special

9. padding은 박스 안쪽에 굵기를 넓혀 주는 것 

   padding-top / pdding-right 등으로 위 아래 오른쪽 왼쪽을 설정할 수 있음

   이렇게 하면 너무 많기 때문에 한줄에 처리가 가능

   padding : 시계 방향으로 적을 수 있음 top right bottom left

   -> padding : 20px 20px 20px 20px;

   -> padding : 20px 20px; 는 padding을 위아래만 주는 것 

   10. margin : 박스 바깥에 여백 크기를 주는 것 

   11. border-width : 2px;

       border-style : solid;

       border-color: pink;

       -> border : 2px solid pink; 

   12. CSS reference로 효과 같은 것을 확인할 수 있음 

       [CSS Reference - A free visual guide to CSS](https://cssreference.io/)

       

   13. 실습 해볼 수 있는 사이트

       https://flukeout.github.io/

   

   

   

   
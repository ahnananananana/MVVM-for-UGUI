#사용법

1. UIViewModel을 상속받아 원하는 데이터의 ViewModel Class를 만든다. 
  * 데이터가 바뀌지 않는다면 기본 변수형을 써도 되지만 그렇지 않다면 Event형식 변수로 선언해야한다. 
  * Monobehaviour이므로 적절히 Canvas같은 UI 중앙에 붙힌다.
![2](https://user-images.githubusercontent.com/65099451/107627046-0b98d800-6ca2-11eb-99d0-d34f431bf7bf.PNG)
![캡처](https://user-images.githubusercontent.com/65099451/107626924-da200c80-6ca1-11eb-8947-62e17fbc975c.PNG)

2. 원하는 UI에 해당 UIViewBinder를 추가하고 UIViewModel을 할당한다. (e.g. 숫자 변수를 Text에 붙이고 싶다면 TextIntViewBinder를 추가한다.) 
![5](https://user-images.githubusercontent.com/65099451/107627202-4f8bdd00-6ca2-11eb-9f24-42462bc9f710.PNG)

3. Model에 원하는 변수를 타이핑한다.

4. 제대로 연결이 되었는지 확인한다.
![6](https://user-images.githubusercontent.com/65099451/107627229-561a5480-6ca2-11eb-91f1-b5fc99d5b700.PNG)

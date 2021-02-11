#사용법

1. UIViewModel을 상속받아 원하는 데이터의 ViewModel Class를 만든다. Monobehaviour이므로 적절히 Canvas같은 UI중앙에 붙힌다.

2. 원하는 UI에 해당 UIViewBinder를 추가한다. (e.g. 숫자 변수를 Text에 붙이고 싶다면 TextIntViewBinder를 추가한다.)

3. UIViewBinder에 UIViewModel을 할당하고 원하는 변수를 타이핑한다.

4. 제대로 연결이 되었는지 확인한다.

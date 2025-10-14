## 1장, 2장
``` <body> </body> ``` 안에 인라인 스크립트 선언이 가능

``` <script> </script> ``` 를 ``` <body> </body> ```에 보통 씀(헤더에 써도 상관은 없지만 DOM다룰때 오류 가능성 있음)

``` <script src = "path">  </script> ```으로 외부 스크립트 연결 가능
***

1. __입출력 함수들__

    ```alert()```
    ```prompt()```
    ```confirm()```

    ```console.log()```
    ```document.write()```

2. __변수__

    ```let a``` 
    ```const a```
    ```var a```

3. __자료형__

    ```typeof()```
    string 하고 number(int, float, ...)

    템플릿 리터럴
    
    - 문자열과 변수, 식을 섞어서 하나의 문자열을 만드는 표현 방식, 백팃 사용, 변수나 식이 들어가면 ${}를 이용해서 묶어서 사용이 가능

    논리형 
   
    - 기본적으로 true, false
    - truety, falsy
    
        falsy 값들: NaN, undefined, null, 0, ""
    - undefine(할당하지 않음, 선언만 한거임)
    - null(주로 의도적으로 할당임

    배열
    - ```arr = []```
    - ```arr = [1, 2, 3, "19"]```

    심볼
    - ```Symbol()```
    - 심볼은 한 번 만들면 변경할 수 없다.

4. __자료형 변환__
    - 기본적으로 자동으로 형이 결정
    - \+ 의 경우 
        - 문자열이 앞이나 뒤 중 하나라도 있으면 연결
        - 둘 다 숫자면 더하기
    - 프롬프트 창에서 입력 받은 값은 항상 문자열
    - 숫자형으로 변환하기
        - ```Number()```
        - ```pareseInt()```, ```parseFloat()```
    - 문자열로 변환하기
        - ```toString()```
        - ```String()```
    - 논리형으로 변환하기
        - ```Boolean()```
    - ```toFixed(n)```을 이용해서 float의 소숫점 자릿수를 고정이 가능




    


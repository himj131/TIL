## 알아두면 편리한 intelliJ 단축키 

- 디렉토리, 패키지, 클래스, 파일 등을 생성 하기

    MAC         | WINDOWS       
    :---:       | :----:        
    <b>Command + N</b> | <b>Alt + Insert</b>

- 메인메소드 생성  
    <b>`psvm`  </b>

- System.out.println()  
  <b> `sout`</b>

- 메소드,클래스등 인자값들 확인하기

    MAC         | WINDOWS       
    :---:       | :----:        
    <b>Command + P</b> | <b>Ctrl + P</b>

- 세부 코드내용 확인하기
    - 메소드에서 사용하면 메소드 구현부 확인 가능 
    - 클래스에 사용하면 해당 클래스 전체소스 확인 가능 

   MAC         | WINDOWS       
    :---:       | :----:        
    <b> Option + Space </b> | <b> Shift + Ctrl + I </b>


- 실행하기(Run)

    |               |   MAC       | WINDOWS       
    |      :---:    |:---:        | :----:        
    현재 포커스에서 실행 |<b>Ctrl + Shift + R</b> | <b>Ctrl + Shift + +F10</b>
    이전 실행을 재실행  |<b>Ctrl + R</b> | <b>Shift + F10</b>

- 한줄 복사(후 다음줄에 추가)

    MAC         | WINDOWS       
    :---:       | :----:        
    <b>Command + D</b> | <b>Ctrl + D</b>

- 한줄 삭제  

    MAC         | WINDOWS       
    :---:       | :----:        
    <b>Command + backspace</b> | <b>Ctrl + Y</b>

- 한줄씩 합치기   
 
    <b>Ctrl + Shift + J</b>
  
    예) System.out.printf("hello world"); 세 줄 합치기
    ```java
    1.     System.out.printf("hello world");
    2.     System.out.printf("hello world");
    3.     System.out.printf("hello world");
    ```

    위 구문 1번 줄에서 ctrl + shift + j 실행시,  
    바로 다음줄이 1번줄 뒤에 <u>문법적 오류 없이</u> 연결된다.  
     
    결과는 다음과 같다.

    ```java
    1.   System.out.printf("hello world").printf("hello world").printf("hello world").printf("hello world");
    ```
    
- 한줄 이동 시키기
  
    |                    |              MAC             |          WINDOWS          |
    |--------------------|:----------------------------:|:-------------------------:|
    | 메소드 내에서 이동 | Command + Shift + 방향키(↑↓) | Ctrl + Shift + 방향키(↑↓) |
    | 문법 상관없이 이동 |  Shift + Option + 방향키(↑↓) |  Shift + Alt + 방향키(↑↓) |  

- 요소 이동  
    
    |           MAC              |     WINDOWS           |
    |:--------------------------:|:---------------------:|
    | Shift + Option + Command + 방향키(←→) | Ctrl + Alt + Shift + 방향키(←→) |
    
    예) id요소와 name 요소의 위치변경 예
    ```html
        <body>
            <form id="id" name="name">
        </body>
              
        <!-- Shift + Option + Command + 방향키(←→) 이용 후-->
        <body>
            <form name="name" id="id">
        </body>
    ```
    
- 문서(Doc) 보기

    MAC         | WINDOWS       
    :---:       | :----:        
    <b> F1 </b> | <b>Ctrl + Q</b>
    
- 포커스 이동 관련 (포커스 이동시 shift 사용하면 블럭으로 선택됨)
    - 단어 단위로 포커스 이동시키기
    
        |       MAC         |     WINDOWS           |
        |:-----------------:|:---------------------:|
        | Option + 방향키(←→) | Ctrl + 방향키(←→)      |
     
    - 라인 단위로 포커스 이동시키기  
    
        |       MAC         |     WINDOWS           |
        |:-----------------:|:---------------------:|
        |   fn + 방향키(←→)   |     Home, End         |
    
    - 페이지 up/down
    
        |       MAC         |     WINDOWS           |
        |:-----------------:|:---------------------:|
        |   fn + 방향키(↑↓))  |  Page up, Page Down   |

    - 여러범위가 섞여있을때 괄호포함 각단위별로 포커스 이동  
        (괄호 많은 문장의 포커스 범위 정할때 유용)
        |       MAC         |     WINDOWS           |
        |:-----------------:|:---------------------:|
        | Option + 방향키(↑↓))|     Ctrl + w (위)     |
        |                   | Shift + Ctrl + w (아래)|

    - 이전 포커스, 이후포커스 이동 (클래스 단위로도 가능)
        |       MAC         |     WINDOWS           |
        |:-----------------:|:---------------------:|
        | Command + 괄호([]) | Ctrl + Alt + 방향키(←→) |    

    - 다중 범위
        |       MAC                |     WINDOWS            |
        |:------------------------:|:----------------------:|
        |Option + Option + 방향키(↑↓)| Ctrl + Ctrl + 방향키(↑↓)|
        
    - 오류 지점으로 바로 이동
        |  MAC  |  WINDOWS |
        |:-----:|:--------:|
        |   F2  |     F2   |    


## intelliJ 단축키

- 디렉토리, 패키지, 클래스, 파일 등을 생성 하기

    MAC         | WINDOWS       
    :---:       | :----:        
    <b>Command + N</b> | <b>Alt + Insert</b>

- 메인메소드 생성  
    <b>`psvm`  </b>

- System.out.println()  
  <b> `sout`</b>

- 실행하기(Run)

    |               |   MAC       | WINDOWS       
    |      :---:    |:---:        | :----:        
    현재 포커스에서 실행 |<b>Ctrl + Shift + R</b> | <b>Ctrl + Shift + +F10</b>
    이전 실행을 재실행  |<b>Ctrl + R</b> | <b>Shift + F10</b>

- 한줄 복사  

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
    바로 다음줄이 1번 구문뒤에 문법적 오류 없이 연결된다.  
    연결하면 다음과 같은 결과를 얻는다.

    ```java
    1.      Syste m.out.printf("hello world").printf("hello world").printf("hello world").printf("hello world");
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
    
    예)
      
    ```html  
        <body>
            <form id="id" name="name">
        </body>
    ```  
    **Shift + Option + Command + 방향키(←→)** 를 이용하여 id요소와 name 요소의 위치를 자유 롭게 변경 가능
    
    ```html
        <body>
            <form name="name" id="id">
        </body>
    ```
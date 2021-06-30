# 로그인 기능 : 키워드를 입력하여 해당하는 블로그들을 보여준다. 

![blog](/docs/image/Login.png)

**[page address]** : /login

<br/>

**[condition]**

&nbsp;&ndash; 없음

<br/>

**[Function Flow]**

&nbsp;&nbsp;&nbsp;1\) Email Address와 Password를 입력한다.

<br/>

&ndash; **[로그인이 성공한 경우]**

&nbsp;&nbsp;&nbsp;2\) 환영 메시지를 띄우고, [MainPage](docs/Main.md)로 이동한다.

<br/>

&ndash; **[Email Address가 등록되어있지 않거나 Password가 틀린 경우]**

&nbsp;&nbsp;&nbsp;2\) "등록되지않은 이메일이거나 비밀번호가 틀립니다" 메시지를 띄운다.

<br/>

&ndash; **[이미 로그인된 상태인 경우]**    

&nbsp;&nbsp;&nbsp;2\) "이미 로그인되어있습니다." 메시지를 띄우고, [MainPage](docs/Main.md)로 이동한다.

<br/>

[**← 메인으로**](/readme.md)
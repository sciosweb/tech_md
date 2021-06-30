# 회원가입 : 페이지의 회원으로 가입한다.

![Signup](/docs/image/Signup.png)

**[page address]** : /signup

<br/>

**[condition]**

&nbsp;&ndash; 없음

<br/>

**[Function Flow]**

&nbsp;&nbsp;&nbsp;1\) UserName, Email, Password, Verify-Password를 입력한다.

<br/>

&ndash; **[회원가입이 성공한 경우]**

&nbsp;&nbsp;&nbsp;2\) "we send confirm email, check mailbox" 메시지를 띄우고, [MainPage](docs/Main.md)로 이동한다.

&nbsp;&nbsp;&nbsp;3\) 가입한 메일주소로 보낸 확인메일을 통해 confirm한다.

<br/>

&ndash; **[Email Address가 이미 등록되어있는 경우]**

&nbsp;&nbsp;&nbsp;2\) "등록되어있는 이메일입니다" 메시지를 띄운다.

<br/>

&ndash; **[Password와 Verify-Password가 일치하지 않는 경우]**

&nbsp;&nbsp;&nbsp;2\) "비밀번호와 비밀번호확인이 일치하지 않습니다." 메시지를 띄운다.

<br/>

[**← 메인으로**](/readme.md)
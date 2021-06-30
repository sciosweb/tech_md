# 비밀번호 초기화 : 사용자의 비밀번호를 초기화해준다.

![Find your password](/docs/image/ResetPassword_a.png)

**[page address]** : /reset_pw

<br/>

**[condition]**

&nbsp;&ndash; 비밀번호가 기억에서 없어졌다.

<br/>

**[Function Flow]**

&nbsp;&nbsp;&nbsp;1\) 찾고자하는 Email Address를 입력한다.

<br/>

&ndash; **[Email Address의 형식이 아니거나, Email Address가 존재하지 않는 경우]**

&nbsp;&nbsp;&nbsp;2\) "Email Address가 존재하지 않습니다." 메시지를 띄운다.

<br/>

&ndash; **[Email Address가 존재하는 경우]**    

&nbsp;&nbsp;&nbsp;2\) "비밀번호 변경을 위한 메일을 보냈습니다" 메시지를 띄우고, [MainPage](/docs/Main.md)로 이동한다.

<br/>

![fill out the password to change](/docs/image/ResetPassword_b.png)

<br/>

&nbsp;&nbsp;&nbsp;3\) "위 페이지에서 Password와 Confirm Password를 입력한다.

&ndash; **[Password와 Confirm Password가 불일치하는 경우]**    

&nbsp;&nbsp;&nbsp;4\) "두 비밀번호가 일치하지 않습니다." 메시지를 띄우고, Confirm Password를 초기화한다.

<br/>

&ndash; **[Password와 Confirm Password가 일치하는 경우]**    

&nbsp;&nbsp;&nbsp;4\) "비밀번호 변경을 완료했습니다." 메시지를 띄우고, [LoginPage](/docs/Login.md)로 이동한다.

<br/>


[**← 메인으로**](/readme.md)
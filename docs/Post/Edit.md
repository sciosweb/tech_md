# 자유게시판 글 수정 / 삭제 : 사용자의 글을 수정하여 올린다. / 글을 삭제 한다.

**[page address]** : /post/edit/:PostId

<br/>

**[condition]**

&nbsp;&ndash; 로그인된 유저와 자유게시판 글의 글쓴이가 일치함

<br/>

**[Function Flow]**


![PostEdit](/docs/image/PostWrite.png)

- 수정버튼을 눌렀을 때


    &nbsp;&nbsp;&nbsp;1\) 입력된 PostID의 글내용들(제목, 태그, 내용)을 불러온다.

    &nbsp;&nbsp;&nbsp;2\) 수정사항을 입력한다.

    <br/>

    &ndash; **[변경사항이 존재하는 경우]**

    &nbsp;&nbsp;&nbsp;3-1\) "수정하였습니다."를 보여준다.

    &nbsp;&nbsp;&nbsp;3-2\)  [게시글 내용보기](/docs/Post/Detail.md)로 이동한다.

    <br/>

    &ndash; **[변경사항이 존재하지 않는 경우]**

    &nbsp;&nbsp;&nbsp;3-1\) "변경사항이 없습니다."를 보여준다.

    &nbsp;&nbsp;&nbsp;3-2\) 이전페이지로 이동한다.

<br/>

<br/>

[**← 뒤로**](/docs/Post.md)
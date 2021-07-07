# 자유게시판 내용보기 : 보고싶은 게시글을 클릭하여 해당 게시글을 보여준다.

![PostDetail](/docs/image/PostDetail.png)

**[page address]** : /post/:PostId

<br/>

**[condition]**

&nbsp;&ndash; 없음

<br/>

**[Function Flow]**

- 주소를 직접 입력하여 접근하거나  리스트에서 클릭하여 접근한 경우

    &ndash; **[글이 존재하는 경우]**

    &nbsp;&nbsp;&nbsp;2\) 입력된 PostID의 글을 불러온다. (글 내용, [댓글](/docs/GNB/Reply.md))

    <br/>

    &ndash; **[글이 존재하지 않는 경우]**

    &nbsp;&nbsp;&nbsp;2\) "글이 존재하지않습니다" 페이지를 보여준다.

<br/>

[**← 뒤로**](/docs/Post.md)
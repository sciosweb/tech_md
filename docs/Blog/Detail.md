# 블로그 내용보기 : 블로그의 내용을 보여준다.

![blog](/docs/image/BlogDetail.png)

**[page address]** : /blog/:PostId

<br/>

**[condition]**

&nbsp;&ndash; 없음

<br/>

**[Function Flow]**

- 주소를 직접 입력하여 접근하거나 블로그 리스트에서 클릭하여 접근한 경우

    &ndash; **[글이 존재하는 경우]**

    &nbsp;&nbsp;&nbsp;2-1\) 입력된 PostID의 글을 불러온다. (글 내용, [댓글](/docs/GNB/Reply.md))

    &nbsp;&nbsp;&nbsp;2-2\) PostID의 작성자의 글들을 불러와 [페이지네이션](/docs/GNB/Pagination.md)을 이용해 보여준다.

    <br/>

    &ndash; **[글이 존재하지 않는 경우]**

    &nbsp;&nbsp;&nbsp;2\) "글이 존재하지않습니다" 페이지를 보여준다.

<br/>

[**← 뒤로**](/docs/Blog.md)
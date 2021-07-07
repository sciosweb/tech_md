# 검색 기능 : 키워드를 입력하여 해당하는 게시글들을 보여준다. 

![Post](/docs/image/Post.png)

**[page address]** : /post, /post/best/:keyword, /post/newest/:keyword...

<br/>

**[condition]**

&nbsp;&ndash; 없음

<br/>

**[Function Flow]**

- 키워드를 입력하는 경우

    &nbsp;&nbsp;&nbsp;1\) 키워드를 입력한다.

    &ndash; **[결과값이 존재하는 경우]**

    &nbsp;&nbsp;&nbsp;2-1\) 입력된 키워드와 일치하는 글들을 목록으로 보여준다. (항상 먼저 최신순으로 보여준다.)

    &nbsp;&nbsp;&nbsp;2-2\) 베스트, 최신순을 눌렀을 때 결과가 정렬된다.

    <br/>

    &ndash; **[결과값이 존재하지 않는 경우]**

    &nbsp;&nbsp;&nbsp;2\) "결과값이 존재하지않습니다" 페이지를 보여준다.


<br/>

- 키워드를 입력하지 않는 경우

    &nbsp;&nbsp;&nbsp;1\) 종류별(Issue, Post), 베스트, 최신순을 눌렀을 때 전체글이 정렬돼서 보여준다.

<br/>

[**← 뒤로**](/docs/Post.md)
# 페이지네이션 : 데이터를 페이지리스트 형식으로 보여준다.

**[page address]** : -

<br/>

**[condition]**

&nbsp;&ndash; 페이지네이션이 필요한 구간

<br/>

**[Function Flow]**

1\) PostPerPage, TotalPost, SetPageNumber를 파라미터로 받는다.

&ndash; **[TotalPost가 0인 경우]**

&nbsp;&nbsp;&nbsp;2\) "존재하지않습니다", < [0] > 로 보여준다.

<br/>

&ndash; **[PostPerPage가 0인 경우]**

&nbsp;&nbsp;&nbsp;2\) 초기 PostPerPage(5)의 값으로 설정한다.

<br/>

&ndash; **[SetPageNumber가 Null인 경우]**

&nbsp;&nbsp;&nbsp;2\) SetPageNumber가 지정되어 있지 않다면 생성불가.

&ndash; **[모든 파라미터가 적절한 값이 존재하는 경우]**

&nbsp;&nbsp;&nbsp;2\) Page에 보여줄 Post 개수, 전체 Post 개수의 비율로 페이지네이션을 진행한다.

&nbsp;&nbsp;&nbsp;3\) SetPageNumber를 통해 PageNumber를 변경하여, 페이지네이션을 클릭할 때 다음 리스트를 보여준다.

<br/>

<br/>

[**← 메인으로**](/readme.md)
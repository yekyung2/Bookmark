# 🔖 Bookmark
### 📌북마크 앱의 기본적인 로직을 통해, Django의 기본적인 MVT패턴 - 모델, 뷰, 템플릿의 개발 로직 과정을 이해하기
### 📌북마크 앱 -  테이블 설계(Model Class)
<table>
<tr>
  <td>필드명 </td>
  <td>타입</td>
  <td>제약조건</td>
  <td>설명 </td>
</tr>

<tr>
  <td>id</td>
  <td>Integer</td>
  <td>PK, Auto Increment</td>
  <td>기본키(Primary Key</td>
</tr>

<tr>
  <td>title</td>
  <td>CharField(100)</td>
  <td>Blank</td>
  <td>북마크 제목</td>
</tr>

<tr>
  <td>url</td>
  <td>URLField</td>
  <td>Unique</td>
  <td>북마크 URL</td>
</tr>

</table>

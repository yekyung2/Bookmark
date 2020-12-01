# 🔖 Bookmark
*Using Django <br>
*북마크 앱의 기본적인 로직을 통해, Django의 기본적인 MVT패턴 - 모델, 뷰, 템플릿의 개발 로직 과정을 이해한다. <br>
*북마크 앱 -  테이블 설계(Model Class)

|필드명|타입|제약조건|설명|
|------|---|---|
|id|Integer|PK, Auto Increment|기본키(Primary Key)|
|title|CharField(100)|Blank|북마크 제목|
|url|URLField|Unique|북마크 URL|

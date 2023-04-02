# RBoard 요구사항 및 설계

---
## 사용자(User)
* 사용자는 가입하고 조회 할 수 있다.
* 사용자는 관리자와 기본 사용자로 나뉜다.
* 사용자 데이터는 Mysql로 연동한다. ( 추후 연동도 가능하다. )

---
## 게시글(Article)
* 글은 작성, 삭제, 수정, 조회 할 수 있다.
* 글은 공지, 일반, 비밀 글로 나뉜다.
* 공지글은 모두 조회 가능하며, 관리자만 작성, 삭제, 수정 가능하다.
* 일반 글은 모두 작성, 조회 가능하다.
* 일반글의 작성자는 작성한 일반글을 수정, 삭제 가능하다.
* 비밀글은 작성자만 수정, 삭제, 조회 가능하다.
---
# K-Digital Training Information Security 3rd Assignment 2

### Overview

**Subject: 간단한 로그인 기능이 포함된 PHP 페이지 작성**

**Environment**

```
OS: Ubuntu 18.04 LTS(Goorm IDE - PHP Project Form)
    -> Kali Linux 6.3.0(VMware)
Language: PHP, HTML
Server: Apache
DB: MySQL
```

1. Source Code Link<a href="#1-source-code-link"><sup>[1]</sup></a>

2. Idea<a href="#2-idea"><sup>[2]</sup></a>

3. Sign In, Sign Up, Sign Out<a href="#3-sign-in-sign-up-sign-out"><sup>[3]</sup></a>

4. Create post(**_C_**)<a href="#4-create-postc"><sup>[4]</sup></a>

5. Read board list(**_R_**)<a href="#5-read-board-listr"><sup>[5]</sup></a>

6. Update post(**_U_**)<a href="#6-update-postu"><sup>[6]</sup></a>

7. Delete post(**_D_**)<a href="#7-delete-postd"><sup>[7]</sup></a>

8. Database<a href="#8-database"><sup>[8]</sup></a>

9. <a href=""><sup>[9]</sup></a>

10. Ref Links<a href="#9-ref-links"><sup>[10]</sup></a>

---

#### 1. Source Code Link

[Link - KDT_IS3_Assignment2](https://github.com/ymiwm/KDT_IS3_Assignment2)
![Index](/img/index/Index.png)

---

#### 2. Idea

앞서 수행한 [Assignment1](https://github.com/ymiwm/KDT_IS3_Assignment1)의 계정 기능을 기반으로 PHP와 MySQL을 연동하여 CRUD 사용을 중점적으로 수행.

<!--Create post-->

- 게시판 글쓰기(**_C_**\_reate) - MySQL의 `auto_increment`를 이용하여 문서 번호 자동화.
<!--Read board and post-->
- 게시판 및 게시글 출력(**_R_**\_ead) - 게시판 출력에 더해 게시글 내부의 기능을 권한에 따라 부여.(Modify / Delete)
<!--Update post-->
- 게시글 수정(**_U_**\_pdate) - 기본적인 수정. DB에 변경된 내용을 덮어씀.
<!--Delete post-->
- 게시판 글 삭제(**_D_**\_elete) - 실수로 삭제되는 것을 방지하기 위해 확인 메세지 추가.
<!--Comment function-->
- ~~댓글 기능~~(WIP)
<!--Feedback-->

---

#### 3. Sign In, Sign Up, Sign Out

- [Link - KDT_IS3_Assignment1](https://github.com/ymiwm/KDT_IS3_Assignment1)
  ![Index](/img/index/Index.png)

---

#### 4. Create post(**_C_**)

![C - List](/img/crud/c/C%20-%20List.png)
![C - Login](/img/crud/c/C%20-%20Login.png)
![C - Create Post](/img/crud/c/C%20-%20Create%20Post.png)
![C - Submit](/img/crud/c/C%20-%20Submit.png)
![C - Complete](/img/crud/c/C%20-%20Complete.png)

---

#### 5. Read board list(**_R_**)

![R - Read Post](/img/crud/r/R%20-%20Read%20Post.png)
![R - Hit](/img/crud/r/R%20-%20Hit.png)
![R - Functions](/img/crud/r/R%20-%20Functions.png)
![R - List](/img/crud/r/R%20-%20List.png)

---

#### 6. Update post(**_U_**)

![U - Modify Post](/img/crud/u/U%20-%20Modify%20Post.png)
![U - Complete](/img/crud/u/U%20-%20Complete.png)
![U - Check](/img/crud/u/U%20-%20Check.png)

---

#### 7. Delete post(**_D_**)

![D - List](/img/crud/d/D%20-%20List.png)
![D - Click](/img/crud/d/D%20-%20Click.png)
![D - Message](/img/crud/d/D%20-%20Message.png)
![D - Complete](/img/crud/d/D%20-%20Complete.png)

---

#### 8. Database

![DB - Tables](/img/db/DB%20-%20Tables.png)
![DB - Columns](/img/db/DB%20-%20Columns.png)
![DB - Records](/img/db/DB%20-%20Records.png)

---

#### 9. Review - Assignment 1
- 로그인 성공/실패/예외에 대한것들을 뷰로 따로 두고 개발하였으면 더 좋았을 것(유지보수 용이성)
- 실패나 예외 상황 발생 시 html과 exit을 활용하는것이 아닌 하나의 단일 페이지에서 ajax로 요청 후 그 결과값에 따라 페이지 이동 없이 띄워주는 것이 베스트

---

#### 10. _Ref Links_

---

[_Go to top_ ↑](#k-digital-training-information-security-3rd-assignment-2)

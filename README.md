<h2>회원 서비스 프로젝트</h2>

참여자: 이승택, 한다현

<img src="https://github.com/seungtoctoc/java-user-practice/assets/102455571/41430222-f7fa-454c-bb79-e4a373883755"/>

* 기능
    - 회원가입
    - 로그인
    - 회원정보 수정
    - 탈퇴
    - 로그아웃
    - 종료
    - 각종 예외처리 구현 (패스워드 오류 등)

* 클래스
    - View, DAO로 분리
    - DAO는 HashMap을 사용해 DB를 대체한다.
 
* 실행 예제
 
```
   
--------------------------MENU--------------------------
1-회원가입, 2-로그인, 3-회원정보 수정, 4-회원탈퇴, 5-로그아웃, 0-종료
--------------------------------------------------------
메뉴를 입력해주세요.
1

* 회원가입
아이디를 입력해주세요.
hi
비밀번호를 입력해주세요.
pw

* 회원가입 완료.

--------------------------MENU--------------------------
1-회원가입, 2-로그인, 3-회원정보 수정, 4-회원탈퇴, 5-로그아웃, 0-종료
--------------------------------------------------------
메뉴를 입력해주세요.
3
로그인부터 하세요

--------------------------MENU--------------------------
1-회원가입, 2-로그인, 3-회원정보 수정, 4-회원탈퇴, 5-로그아웃, 0-종료
--------------------------------------------------------
메뉴를 입력해주세요.
7
다시 입력

--------------------------MENU--------------------------
1-회원가입, 2-로그인, 3-회원정보 수정, 4-회원탈퇴, 5-로그아웃, 0-종료
--------------------------------------------------------
메뉴를 입력해주세요.
2

* 로그인
아이디를 입력해주세요.
hi
비밀번호를 입력해주세요.
pw
로그인 완

현재 로그인중인 아이디: hi
--------------------------MENU--------------------------
1-회원가입, 2-로그인, 3-회원정보 수정, 4-회원탈퇴, 5-로그아웃, 0-종료
--------------------------------------------------------
메뉴를 입력해주세요.
3

* 회원정보 수정
새로운 비밀번호를 입력해주세요.
pwpw
수정 완~

현재 로그인중인 아이디: hi
--------------------------MENU--------------------------
1-회원가입, 2-로그인, 3-회원정보 수정, 4-회원탈퇴, 5-로그아웃, 0-종료
--------------------------------------------------------
메뉴를 입력해주세요.
5

* 로그아웃

--------------------------MENU--------------------------
1-회원가입, 2-로그인, 3-회원정보 수정, 4-회원탈퇴, 5-로그아웃, 0-종료
--------------------------------------------------------
메뉴를 입력해주세요.
2

* 로그인
아이디를 입력해주세요.
hi
비밀번호를 입력해주세요.
pwpw
로그인 완

현재 로그인중인 아이디: hi
--------------------------MENU--------------------------
1-회원가입, 2-로그인, 3-회원정보 수정, 4-회원탈퇴, 5-로그아웃, 0-종료
--------------------------------------------------------
메뉴를 입력해주세요.
4

* 회원 탈퇴
비밀번호를 입력해주세요.
pwpw
삭제 완~

--------------------------MENU--------------------------
1-회원가입, 2-로그인, 3-회원정보 수정, 4-회원탈퇴, 5-로그아웃, 0-종료
--------------------------------------------------------
메뉴를 입력해주세요.
2

* 로그인
아이디를 입력해주세요.
hi
아이디 틀
```

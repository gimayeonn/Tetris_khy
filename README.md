# Tetris_khy
오픈소스프로그래밍 고효율 팀입니다.

1. 목적

   기존의 테트리스 게임에 추가적인 기능을 구현하여, 더 발전된 테트리스 게임을 만들기 위함이다.

     <추가 기능>
     - AWS의 RDS와 MySQL을 이용한 회원가입/로그인 기능 구현
     - 모드별 랭킹 구현 및 랭킹 실시간 업데이트 기능 구현

3. 게임 실행 방식
   1. 현재 repository의 소스 코드를 모두 다운 또는 clone을 통해 local에 저장한다.
   2. 추가 모듈에 표기한 모듈들을 다운 받고 run.py에서 실행한다.

4. 조작 방식

   a, 왼쪽 방향키 : 블럭을 왼쪽으로 한칸 이동시킨다   
   
   d, 오른쪽 방향키 : 블럭을 오른쪽으로 한칸 이동시킨다 
   
   w, 위쪽 방향키 : 블럭을 오른쪽으로 90도 회전시킨다
   
   s, 아래쪽 방향키 : 블럭을 아래쪽으로 한칸 이동시킨다
   
   e, 스페이스바 : 블럭을 아래쪽으로 떨군다
   
   p : 게임을 일시정지한다
   
   m : 배경음악을 키고 끈다
   
   
   -기본, AI, MINI 모드에서는 방향키와 a,w,s,d, space로 블럭 조작
   
   -two hands 모드에서는 awsd와 e, 방향키와 space를 통해 각각의 블럭을 조작
   
5. 게임 실행

  	  a.메뉴
  
  <img src="https://user-images.githubusercontent.com/70746658/101520898-6e32d680-39c8-11eb-8ecb-25a9c4d5ab6e.png"  width="400" height="400">
  <img src="https://user-images.githubusercontent.com/70746658/101518585-75a4b080-39c5-11eb-8898-95ccdd3f057e.png"  width="400" height="400">
  <img src="https://user-images.githubusercontent.com/70746658/101518593-78070a80-39c5-11eb-8ee3-3cfa8adecab1.png"  width="400" height="400">
  
  
 	  b.키 조작 help
  
  <img src="https://user-images.githubusercontent.com/70746658/101520904-712dc700-39c8-11eb-9077-b177bd618369.png"  width="400" height="400">
  
	  c.일반 게임
  
  <img src="https://user-images.githubusercontent.com/70746658/101518483-50b03d80-39c5-11eb-9d60-9a196822fabc.png"  width="300" height="400">
  
	  d. Two Hands 모드
  
  <img src="https://user-images.githubusercontent.com/70746658/101518615-805f4580-39c5-11eb-818d-2332e4d1ef1b.png"  width="700" height="400">

	  e. AI 모드
  
  <img src="https://user-images.githubusercontent.com/70746658/101518622-835a3600-39c5-11eb-9e1c-75350c192d1e.png"  width="700" height="400">
  
 	  f. MINI 모드
   <img src="https://user-images.githubusercontent.com/70746658/101523674-3ded3700-39cc-11eb-9928-5e925e259cdd.png"  width="280" height="400">  
 
	  g. ID 입력
  
  <img src="https://user-images.githubusercontent.com/70746658/101522098-1f863c00-39ca-11eb-929d-e1f983a3ec81.png"  width="400" height="400">  
  
	  h. RANK 확인
  
  <img src="https://user-images.githubusercontent.com/70746658/101518501-586fe200-39c5-11eb-9aa2-4eb0ed0c77c7.png"  width="400" height="400">  
  
  	- 게임 종료 후, ID를 입력하면 aws에 만들어둔 데이터 베이스에 자동 저장
  <img src="https://user-images.githubusercontent.com/70746658/101523466-fbc3f580-39cb-11eb-82d3-21fcdcd5d0f7.png"  width="300" height="150">  








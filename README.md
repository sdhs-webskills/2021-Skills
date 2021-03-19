#

### A-Module

``` markdown

# 페이지 구성

- 메인페이지
    - PC버전
    - 반응형 480px 

- 서브페이지
    - 무형문화재 현황
    - 월간 공연 일정

```

``` markdown
# Main page

- header
    - menu
        - 1depth hover effect
        - 2,3 depth animation 
- visual
    - 3초 이내 전환
    - 1 > 2 > 3 > 1
- 새 소식
    - (`공지사항`, `보도자료`, `채용공고`, `입찰정보`) 탭 분리
- 팝업 존
- 행사
    - `상세내용 보기` 버튼
- 유네스코 인류 무형유산
    - 알아서 해석 
- banner
    - 오른쪽에서 왼쪽 
    - 끝까지 가면 다시 왼쪽으로 돌아가는 슬라이드 인거 같음
    - 3초 이내 전환, 1초 stop 
    - 
- footer
```

``` markdown
# Sub page

- 현재 메뉴 위치를 알수 있는 네비게이터
 예시 : 학교 > 기능반 

 - 월간 공연 일정 페이지는 grid 써서 하면 될 거 같음

```

#

### B-Module 

xml 과 json 데이터를 가져와서 띄우고 수정 삭제만 하는 정도

``` markdown 

# 연혁 및 관리

- localStorage 
    - 저장된 년도 Tab 
    - Tab 클릭 시 해당 연도 연혁 보임 ( Tab Click localStorage 저장 )
    - 연혁 등록, 수정, 삭제 기능

```
``` markdown

# 전화번호 - 목록

php 파일에 요청을 보내면 json 데이터로 넘어옴

이건 현재 2학년이 풀고 있는 music 에 menu 랑 유사한 기능
status 관리만 잘해주면 될 거 같음
```

``` markdown
# 무형문화재 목록 조회 

작년 전국 광주문제랑 유사함 
광주문제 B 모듈만 구현해보면 될 거 같음

상세보기시 rest 데이터 가져와서 팝업에 뿌려주는 형식

```


#

### C-Module 

``` markdown
# 기초 셋팅
 
 작년 광주 문제랑 유사함 
 

```
``` markdown
# 무형문화재 현황
 menu 가져와서 데이터 filter 해줘야됨 
 기초 셋팅 데이터 기반으로 다시 띄우라는 소리임
 등록, 수정, 삭제 
 page nation 이건 B모듈때 짠거 우려먹으면 됨

```
``` markdown 
# 월간/ 연간 공연 일정

 작년 전국 대구 문제랑 유사한거 같음 ( 이건 나중에 알려줌 )
  rest 로 조회함 ( 거의 JS 로만 으로 짤 수 있음)
```
#


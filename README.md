# filter-kr

**uBlock** filter for websites (mainly Korean) which has ad but didn't erase.

- [Discord 서버에서 업데이트 받기](https://discordapp.com/invite/vAEBXWY)

## 목차

- [설치하기](#설치하기)
- [FAQ](#FAQ)
- [필터](#필터), 현재 제공하는 필터 목록입니다.

----

# 설치하기

아래 방법 중 한 가지를 선택하시거나 필터 목록에서 원하는 필터의 이름을 눌러주세요.

## 직접 URL로 설치하기

1. 웹 브라우저에서 uBlock 확장 프로그램 팝업을 열고 대시보드를 엽니다.

2. 보조 필터 탭을 끝까지 내려 사용자 지정 보조 필터의 불러오기 체크박스를 클릭하고 올바른 필터 URL(아래의 필터 섹션을 참조)을 추가합니다.

3. 우측 상단의 '변경 사항 적용' 버튼을 클릭하고 스크롤을 가장 위로 올려 '지금 업데이트' 버튼을 클릭합니다.

# FAQ

## 지워지지 않은 광고

지워지지 않은 광고가 있다면 이슈 탭에 간단히 자신의 웹 브라우징 환경(웹 브라우저, 특정 필터 사용 여부 등)과 해당 웹 페이지의 URL을 첨부해주시면 빠른 시일 내에 처리하도록 하겠습니다.

## 필터 버저닝

필터의 버전은 JavaScript의 UTC Timestamp를 사용하고 있습니다. 이는 꼭 커밋 시간과 같을 필요는 없습니다.

## 직접 업데이트하기

> 기본적으로 1일에 한 번 업데이트하도록 설정되어 있습니다.

1. 웹 브라우저에서 uBlock 확장 프로그램 팝업을 열고 대시보드를 엽니다.

2. 보조 필터 탭에서 Seia-Soto/filter-kr 필터를 찾은 다음 옆의 시계 아이콘을 클릭하고 스크롤을 가장 위로 올려 '지금 업데이트' 버튼을 클릭합니다.

# 필터

원하는 필터를 선택하고 필터 설명의 하단에 있는 필터 URL을 사용하세요.

## [`base`](filter.txt)

기본으로 제공하는 필터입니다. 사용하면서 주기적으로 제거되지 않은 광고가 있다면 필터에 추가합니다.

> https://github.com/Seia-Soto/filter-kr/raw/master/filter.txt

## `extra`

추가 필터입니다. 특정 목적에 따라 따로 만듭니다.

### [`twitterTrends.txt`](extra/twitterTrends.txt)

트위터 웹 앱 우측에 표시되는 트랜드를 제거합니다.

> https://github.com/Seia-Soto/filter-kr/raw/master/extra/twitterTrends.txt

### [`ebsocPopup.txt`](extra/ebsocPopup.txt)

EBS 온라인클래스에서 표시되는 팝업과 로그인 페이지의 간접 광고를 제거합니다.

> https://github.com/Seia-Soto/filter-kr/raw/master/extra/ebsocPopup.txt

### [`twitterWhoToFollow.txt`](extra/twitterWhoToFollow.txt)

트위터 웹 앱에 표시되는 팔로우 추천을 제거합니다.

> https://github.com/Seia-Soto/filter-kr/raw/master/extra/twitterWhoToFollow.txt

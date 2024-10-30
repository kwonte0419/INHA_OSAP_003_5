# INHA_OSAP_003_5
👋 인하대학교 컴퓨터공학과 오픈소스응용프로그래밍 강의에서 진행되는 팀프로젝트 레포입니다.

<br>

## 📚 과제 개요
본 과제에서는 AVL 트리를 이용하여 오픈소스인 STL set과 관련된 함수(연산) 및 추가 함수 구현하도록 한다.<br>
- AVL 트리는 정수 타입 (32-bit integer) 의 key를 저장<br>
- 기본 기능: Find, Insert, Empty, Size, Height, Ancestor, Average<br>
- 고급 기능: Rank, Erase<br>

<br>

## 👨‍👨‍👦‍👦 팀원 및 역할
- 민경: 기능 구현(Height, Rank, Erase), 코드 리뷰 진행, 테스트 진행 <br>
- 민규: 기능 구현(Ancestor, Average), 코드 리뷰 진행, 테스트 진행 <br> 
- 태은: 기능 구현(Insert, Empty), 코드 리뷰 진행, 테스트 진행 <br>
- 민재: 기능 구현(Find, Size), 코드 리뷰 진행, 테스트 진행 <br>

<br>

## 🎨 코딩 스타일
🖌 'CSE3210 스타일 가이드'를 반드시 준수하도록 한다.<br>
🖌 코드는 한줄에 80자를 넘어가지 않도록 한다.<br>
🖌 파일 별로 라이선스 주석은 반드시 작성되어야 한다.<br>
🖌 설명이 필요한 기능의 경우, 주석을 작성하되 두 줄이 넘어가지 않도록 한다.<br>
🖌 주석 작성 시, 모호한 표현은 최대한 삼가하며 경어체로 작성하도록 한다.<br>
🖌 기능 설명은 /** */, 코드 내의 짧은 주석은 //로 작성한다.<br>

<br>

## 🌿 브랜치 전략
- 별도의 브랜치 전략을 사용하지 않으며, fork와 PR을 통해 메인 저장소와 각 팀별 저장소를 구분하도록 한다.

<br>

## 🎁 커밋 Convention
커밋 컨벤션은 Google/Angular 커밋 컨벤션의 제목 부분만 사용하도록 하며, 내용은 한글로 작성하도록 한다.<br>
*ex. feat : insert 기능 구현* <br>
- feat : 새로운 기능 추가 <br>
- fix : 버그 수정 <br>
- docs : 문서 변경 <br>
- style : 코드 스타일 변경 (포매팅 수정, 세미콜론 추가 등) <br>
- refactor : 코드 리팩토링 <br>
- test : 테스트 코드 추가, 수정 <br>
- chore : 빌드 프로세스, 도구 설정 변경 등 기타 작업 <br>

<br>


## 🧩 PR Template
💡 PR은 아래의 템플릿을 복사하거나 깃허브 템플릿 자동 설정을 해두어 반드시 PR을 열때 양식에 맞추어 작성하도록 한다.
<br>
### 1. PR 제목
PR 제목은 커밋 메세지의 내용과 동일하게 작성하되 아래의 양식에 맞추어 작성한다.<br>
*ex. [Feat] insert 기능 구현*
<br>

### 2. 작업 내용 요약
작업한 내용에 대하여 간결하게 작성해주세요!
<br>
### 3. PR 유형
어떤 변경 사항이 있나요?
- [ ] 새로운 기능 추가
- [ ] 버그 수정
- [ ] CSS 등 사용자 UI 디자인 변경
- [ ] 코드에 영향을 주지 않는 변경사항(오타 수정, 탭 사이즈 변경, 변수명 변경)
- [ ] 코드 리팩토링
- [ ] 주석 추가 및 수정
- [ ] 문서 수정
- [ ] 테스트 추가, 테스트 리팩토링
- [ ] 빌드 부분 혹은 패키지 매니저 수정
- [ ] 파일 혹은 폴더명 수정
- [ ] 파일 혹은 폴더 삭제
- [ ] 기타

### 4. PR Checklist
PR을 열기 전 점검해보세요!
- [ ] 기능이 정확하게 동작합니다.
- [ ] 더 나은 코드에 대해서 고민해보았습니다.
- [ ] 구현한 기능에 대한 테스트를 진행했습니다.
- [ ] CSE3210 스타일 가이드에 준수하여 코드를 작성했습니다.
- [ ] 커밋 메시지 컨벤션에 맞게 작성했습니다.
- [ ] 라벨과 리뷰어를 설정했습니다.


### 5. 관련 이슈
관련하여 논의하고자 하는 이슈가 있으면 작성해주세요.
<br>

### 6. 참고자료
참고한 자료가 있으면 작성해주세요.
<br>
<br>

## 📑 코드리뷰
📌 본 팀에서는 한 사람당 한 명의 리뷰어가 지정되어 있다. (요청자 - 리뷰어)<br>
- 태은 - 민재<br>
- 민재 - 민경<br>
- 민경 - 민규<br>
- 민규 - 태은<br>

📌 강의 시간에 학습한 'Chromium Docs의 Respectful Code Reviews(2-4. 코드리뷰)' 내용을 반드시 숙지한다.<br>
📌 특히 리뷰어는 상대방을 비난하는 내용은 절대로 하지 않는다.(상처..😥)<br>
📌 코드 스타일에 대한 기준은 'CSE3210 스타일 가이드'를 바탕으로 한다. <br>
📌 코드 리뷰의 내용은 칭찬과 수정사항의 내용을 적절하게 반영하여 자유롭게 작성한다.<br>
📌 리뷰어는 더이상의 의견이 없을 시, LGTM을 남겨주고 반드시 Approve 해주도록 한다. <br>
📌 리뷰 요청자는 리뷰어의 LGTM과 Approve를 확인 후에 직접 merge하도록 한다.<br>

<br>

## 🛠 테스트
(추후 작성예정)

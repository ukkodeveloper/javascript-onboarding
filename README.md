# 미션 - 온보딩

## 🚀 기능 구현

### 🔍 문제1

- [x] 책의 페이지가 1부터 400이 아니면 예외처리 한다.
- [x] 포비가 가질 수 있는 최대 점수를 구한다.
- [x] 크롱이 가질 수 있는 최대 점수를 구한다.
- [x] 포비와 크롱의 최대 점수를 비교하여 값을 도출한다.

### 🔍 문제2

- [x] cryptogram은 길이가 1 이상 1000 이하가 아니면 예외처리.
- [x] cryptogram은 알파벳 소문자로가 아니면 예외처리.
- [x] 중복문자 제거하기
  - [x] 문자열을 순회하면서 연속된 문자는 소거
  - [x] 소거할 문자가 없으면 문자열 반환

### 🔍 문제3

- [x] number는 1 이상 10,000 이하인 자연수이다.
- [x] 1부터 number까지 1씩 증가하면서 3,6,9 숫자를 체크한다.
  - [x] number을 문자열로 변환한다.
  - [x] 1이 증가할때마다 3, 6, 9가 있는지 확인한다.

### 🔍 문제4

- [x] 문자열이어야 한다.
  - [x] 문자열의 길이가 1이상 1000이하이여야 한다.
- [x] 주어진 문자열을 배열로 변환한다.
- [x] 알파벳 하나씩 순회하여 답을 반환한다.
  - [x] 소문자, 대문자, 그 외의 그룹으로 나눈다.
  - [x] 아스키 코드를 이용하여 알파벳 반대에 있는 문자를 반환한다.
  - [x] 뒤집은 문자를 엮어 문자열로 반환한다.

### 🔍 문제5

- [x] money값이 1 이상 1,000,000 이하인 자연수이 아닌 경우 예외처리한다.
- [x] 화폐 종류별로 순회하여 화폐 별로 result에 개수를 추가한다.

### 🔍 문제6

- [x] 각종 경우에 따라 예외처리 한다.
  - [x] forms길이가 1이상 1000이하가 아닌 경우
  - [x] email 길이가 11자 이상 20자 미만이 아닌 경우
  - [x] '@email' 형식이 아닌 경우
  - [x] 닉네임 길이가 1자 이상 20자 미만이 아닌 경우
  - [x] 닉네임이 한글이 아닌 경우
- [x] forms를 순회하며 크루와 같은 글자가 연속적으로 포함되어 있는 크루의 메일을 추린다.
  - [x] 순회하며 크루마다 닉네임에서 두글자씩 선택하여 다른 크루에게도 같은 글자가 없는지 확인한다.
- [x] 추려진 이메일의 중복을 제거한다.
- [x] 추려진 이메일을 오름차순으로 정렬한다.

### 🔍 문제7

- [x] 각종 경우에 따라 예외처리 한다.
  - [x] user길이가 1이상 30이하인 문자열이 아닌 경우
  - [x] friends길이가 1이상 10,000 이하가 아닌 경우
  - [x] friends 내부 요소가 길이가 2인 배열이 아닌 경우
  - [x] friends 아이디의 길이가 1이상 30이하인 문자열이 아닌 경우
  - [x] visitors의 길이가 0 이상 10,000 이하가 아닌 경우
  - [x] visitors 아이디 길이가 1이상 30이하인 문자열이 아닌 경우
- [x] friends를 순회하면서 필요한 데이터 구조를 형성한다.
  - [x] 추천예외항목을 만들어 user자신, user와 친구인 이용자를 추가한다.
  - [x] 친구별로 포인트와 친구목록을 담고 있는 자료구조를 만든다.
- [x] user의 친구를 순회하면서 user와 함께 아는 친구에게 10점을 준다.
  - [x] 추천예외항목에게는 해당되지 않는다.
- [x] visitors를 반복하면서 3점을 준다
  - [x] 추천예외항목에게는 해당되지 않는다.
- [x] 점수를 비교하여 결과값을 도출한다.
  - [x] 포인트가 0인 이용자는 제외한다.
  - [x] 이름순으로 정렬한다
  - [x] 점수순으로 정렬한다.
  - [x] 상위 5사람의 배열을 반환한다.

## 📜 회고

| 일자 | 링크                                      | 키워드                                               |
| ---- | ----------------------------------------- | ---------------------------------------------------- |
| 1️⃣   | [🧩 1일차 TIL](docs/til/DAY01_221026.md)  | `오리엔테이션`, `Node.js`, `아스키코드`, `배열`      |
| 2️⃣   | [🧩 2일차 TIL](docs/til/DAY02_221027.md)  | `변수네이밍`, `git`, `고차함수(reduce, some, every)` |
| 3️⃣   | [🧩 3일차 TIL](docs/til/DAY03_221028.md)  | `OOP SOLID`, `Map객체`, `Set객체`                    |
| 4️⃣   | [🧩 4일차 TIL](docs/til/DAY04_221029.md)  | `git커밋 수정`, `sort`, `정규표현식`                 |
| 5️⃣   | [🧩 5일차 TIL](docs/til/DAY05_221030.md)  | `클린코드`, `자바스크립트 컨벤션`                    |
| 6️⃣   | [🧩 6일차 TIL](docs/til/DAY06_221031.md)  | `클래스 리팩터링`, `반복문 리팩터링`                 |
| 7️⃣   | [🌠 1주차 회고](docs/til/DAY07_REVIEW.md) | `회고`                                               |

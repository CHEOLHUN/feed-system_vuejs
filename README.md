# feed-system_vue

## 요구사항 분석

### 반응형 웹

- [x] 반응형 웹 (Max-with:480px)

### 피드 컨텐츠

- [x] 글자 수가 많으면 자르고 생략기호 ... 표시
- [x] 컨텐츠 불러오기(infinite-loading)
- [x] 처음에는 10개만 불러오기
- [x] 스크롤이 최하단에 닿을 때마다 10개씩 추가

### 피드 디테일

- [x] 클릭하면 디테일 페이지로 이동("/:id") - 동적 라우터

### 정렬

- [x] 기본값:오름차순
- [x] 선택된 정렬기준 css 강조
- [x] 선택된 정렬 기준으로 실제 정렬

### 필터

- [x] 별도 컴포넌트로 분리 개발
- [x] 모달
- [x] input type="checkbox"
- [x] 기본값:모두 선택
- [x] 저장을 클릭하면 저장되고 모달 종료
- [x] 모달 CSS
- [x] 실제 필터로 검색 결과 필터링

### 광고

- [x] 4번째 index 마다 광고 1개 삽입 피드/피드/피드/광고/피드/피드/피드/광고 ...
- [x] 광고 이미지 비율 유지(반응형)
- [x] 글자수가 많으면 자르고 생략기호 ...표시

### 추가요구사항

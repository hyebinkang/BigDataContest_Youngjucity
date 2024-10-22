# 💻2024 영주시 빅데이터 데이터 분석·활용 공모전💻
- 팀명: 선비의 밤 고백(4명)
- 주체: [영주시청](https://www.yeongju.go.kr/open_content/main/page.do?pageNo=1&pagePrvNxt=1&pageRef=0&pageOrder=0&step=258&parm_bod_uid=1143205&srchVoteType=-1&srchBgpUid=-1&srchKeyword=%EA%B3%B5%EB%AA%A8%EC%A0%84&srchEnable=-1&srchSDate=1990-01-01&srchColumn=bod_title&srchEDate=2100-01-01&mnu_uid=1521&)
- 공모주제: 영주시 도시 현안 관련 자유주제(문화/관광)
- 공모부문: 데이터 분석
- 수상: 장려상
-----
## 프로젝트 배경
- 영주시의 매력대비 인지도 부족
- 영주시의 전반적 문제 탐색
- 방문자 유입 증가 필요성을 파악

## 사용 데이터
- [한국관광 데이터랩](https://datalab.visitkorea.or.kr/datalab/portal/main/getMainForm.do)
  - 2021~2024
    - 방문자 수(연인원) 추이
    - 여행 유형 별 언급량
    - 목적지 유형별 검색량
    - 네비게이션 검색 유형 분포
    - 숙박일수별 방문자 추이
    - SNS 언급량 
  - 2023 ~ 2024
    - 내국인 관심 관광지
    - 중심관광지
    - 인기관광지_현지인, 외지인, 전체
    - 관심지점 비교_현지인, 외지인
    - 주요 유료관광지점 입장객 수_전체
    - 지역 맛집 전체
- 영주시청
  - 영주시 카드내역 소비
- 통계청
    - 영주시 주민등록인구 기타 현황(지역별 아동, 출생등록, 고령 인구 현황, 인구증감)
    - 연령별인구현황_월간
    
## 분석 방법
- target: 영주시 총 방문자 수
- 머신러닝: Linear Regression, Lasso, Ridge
- 평가: MAE, MSE, R2-Score
  
## 분석 결과
- 영주시를 방문하는 사람들의 목적지 유형순위를 보았을 때 체험관광이 가장 높음
- 여행 유형별 상관계수를 보았을 때 휴식,힐링, 레포츠 분야에서 음의 상관계수를 나타냄
- 검색량과 방문자 수를 보았을 때 숙박의 중요도가 가장 낮음
- 검색량과 언급 건수를 보았을 때 SNS언급량이 음의 상관계수를 나타냄
  
## 프로젝트 목적
- 젊은 세대에게 영주시를 알리고 숙박으로 이어질 수 있는 콘텐츠 기획
  
## 기대효과
- 거시적 관점: 관광산업 발전, 지역 홍보 효과, 지역경제 활성화
- 미시적 관점: 일자리 창출, 지역 상권 활성화, 지역 문화 유산 보존

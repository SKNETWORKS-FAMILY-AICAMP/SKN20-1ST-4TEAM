"# SKN20-1ST-4TEAM" 

# 1차 프로젝트
### SK 네트웍스 AI과정 1차 프로젝트

## 1. 팀 소개
팀명: 쿼드코어 (QuadCore)

팀원

<table align="center">
  <tr>
    <td align="center" valign="top" style="padding: 10px;">
      <img width="200" height="480" alt="image" src="https://github.com/user-attachments/assets/19ce06ea-d792-4cbf-bee7-6541a0c1c96d" alt="김나현"/>
    </td>
    <td align="center" valign="top" style="padding: 10px;">
      <img width="200" height="480" alt="image" src="https://github.com/user-attachments/assets/f362d7a2-f3fe-43f6-aec4-7def1ad1c56f" width="150" alt="김도윤"/>
    </td>
    <td align="center" valign="top" style="padding: 10px;">
      <img width="200" height="480" alt="image" src="https://github.com/user-attachments/assets/01cecff6-8b63-41b3-85bf-950123506abf" alt="박다정"/>
    </td>
    <td align="center" valign="top" style="padding: 10px;">
      <img width="200" height="480" alt="image" src="https://github.com/user-attachments/assets/b71b8632-964d-4135-9e2f-2f057035b2d4" alt="안채연"/>
    </td>
  </tr>
  <tr>
    <td align="center"> <strong>김나현</strong></td>
    <td align="center"> <strong>김도윤</strong></td>
    <td align="center"> <strong>박다정</strong></td>
    <td align="center"> <strong>안채연</strong></td>
  </tr>
</table>





## 2. 프로젝트 개요
### 2.1. 프로젝트 명
- 차량 정보 조회 시스템 및 FAQ 시스템
  
### 2.2. 프로젝트 소개
- 본 프로젝트는 **2015년부터 2024년까지 10년간의 데이터를 기반으로 연료별 차량 현황을 조회**할 수 있는 시스템입니다.
사용자는 **연도, 차종, 연료 종류**에 따라 차량 수를 조회하고, 이를 **시각화된 그래프**로 확인할 수 있습니다.

- **차량 관련 FAQ 기능**을 제공하여, 자주 묻는 질문을 쉽게 확인하고 정보를 얻을 수 있습니다.
  
### 2.3. 프로젝트 필요성 (배경)
- 연료별 차량 데이터는 시장 트렌드 분석 및 환경 정책 수립에 활용 가능
- 자동차 제조사 및 관련 기관은 연료별 차량 수 변화를 통해 전기차, 하이브리드 등 친환경 차량 보급 현황을 파악
- 소비자에게는 연료 선택에 따른 차량 현황을 제공하여 구매 결정 시 참고 자료로 활용
- 명료하고 직관적인 데이터 제공으로 분산되어 있는 정보를 빠르게 필터링하고, 정책, 마케팅, 구매 전략 수립에 활용 가능
  
### 2.4. 프로젝트 목표
- 사용자로 하여금 시간의 흐름에 따라 연료&차종별로 그 숫자가 어떻게 변화해왔는지를 그래프로 시각화하여 파악하기 쉽게 합니다.
- 차량 운전자들이 궁금해하는 질문들을 전기차, 하이브리드차, 그리고 통합 TOP10 질문까지 3개의 카테고리로 나누어서 제공합니다.

## 3. 기술 스택
- **Python**: 3.10+  
- **Web**: Streamlit  
- **DB**: MySQL 8.x  
- **ETL**: Selenium, BeautifulSoup, pandas
### 3.1. 프론트엔드
: 웹 대시보드 프레임워크 (데이터 시각화 및 조회 시스템)

### 3.2. 백엔드
: 데이터 처리 및 비즈니스 로직 구현

: 데이터베이스 관리 및 저장

: 데이터 분석 및 필터링 처리

## 4. WBS (Work Breakdown Structure)
### 4.1. 프로젝트 기획
- 기획 방향 회의

### 4.2. 크롤링
-

### 4.3. SQL 연결
- CSV 데이터베이스 입력
- 자동차 연료별 차량 현황 SQL 쿼리 연결 및 구현
- FAQ SQL 연결


### 4.4. STREAMLIT 구현
- Streamlit 대시보드 구축
- 통계 데이터 제공 화면 구현 : 연료별 차량 현황, 연도별 연료 순위
- FAQ 화면 구현 : TOP10, 전기차, 하이브리드

### 4.5. 프로젝트 완료

## 5. 요구사항 명세서
### 5.1. 사용자 요구사항

### 5.2. 시스템 요구사항

## 6. ERD (Entity-Relationship Diagram)
### 6.1.1 주요 테이블 구조I
- fuel_tbl: 연료정보 (휘발유, 경유, LPG, 전기, CNG, 하이브리드, 수소)
- cartype_tbl: 차량종류 (승용차, 승합차, 화물차, 특수차)

### 6.1.2 ERD 다이어그램 I





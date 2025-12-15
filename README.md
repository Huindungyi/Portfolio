# Database Engineer Portfolio

**Database Engineer | PostgreSQL | MES · APS Operations**  
Operational Stability · Data Integrity · Manufacturing Systems

Manufacturing systems–focused Database Engineer with hands-on experience  
operating MES and APS environments across multiple production sites.

- PostgreSQL-based DB operations ensuring stability, integrity, and performance
- Root-cause analysis of production incidents from a data-first perspective
- Hands-on experience with large-scale manufacturing data and BI workloads
- Strong understanding of MES application logic (C#) and DB integration
- Proven incident response in high-load, mission-critical environments

I focus on preventing operational failures by controlling data state, structure,  
and lifecycle.

---

## Table of Contents
1. [About Me](#i-about-me)
2. [Core Strengths](#ii-core-strengths)
3. [Technical Stack](#iii-technical-stack)
4. [Operating Environment Overview](#iv-operating-environment-overview)
5. [Project Overview](#v-project-overview)
6. [Incident Response & Troubleshooting](#vi-incident-response--troubleshooting)
7. [DBA Mindset & Career Direction](#vii-dba-mindset--career-direction)
8. [Project Management & Documentation](#viii-project-management--documentation)

---

## I. About Me

제조업 환경에서 MES·APS 시스템을 운영하며  
PostgreSQL 기반 데이터베이스의 안정성, 정합성, 성능을 중심으로 문제를 해결해 온 DB 엔지니어입니다.

현장 공정과 데이터 흐름의 불일치로 인해 발생하는 다양한 장애를 경험하며,  
단순 증상 대응이 아닌 데이터 상태와 구조를 기준으로 한 근본 원인 분석을 수행해 왔습니다.

애플리케이션(C#)과 DB를 함께 이해하는 시야를 바탕으로  
운영 환경에서 신뢰할 수 있는 데이터를 유지하는 실전형 DBA로 성장하고자 합니다.

---

## II. Core Strengths

- PostgreSQL 기반 MES·APS 운영 경험
- 대용량 데이터 환경에서의 장애 대응 및 원인 분석
- SQL 중심의 데이터 정합성 및 성능 문제 해결
- MES 유지보수(C#)를 통한 DB 연계 로직 이해
- 현장·IT·협력사 간 커뮤니케이션 기반 문제 조율

---

## III. Technical Stack

### DBMS
**PostgreSQL**

- MES / APS / BI 전반 단일 DBMS 운영
- 대용량 데이터 환경에서 성능 저하 및 장애 대응
- 불필요 데이터 정리 및 데이터 정합성 점검
- 복잡한 제조·경영 데이터 조회 쿼리 작성
- 조건 기반 데이터 추적을 통한 장애 원인 분석
- BI 조회를 고려한 구조 검토 및 MV 설계·운영

### Application (MES Maintenance)
**C#**

- 운영 중인 MES 애플리케이션 유지보수 및 기능 개선
- DB 연계 로직 수정 및 SQL 호출 구조 개선
- 장애 발생 시 코드 레벨 원인 분석 및 대응
- DB 구조 변경 시 애플리케이션 영향도 검토 및 반영

### Automation & Operations
**Batch / Python**

- MV 갱신 및 데이터 정리 작업 자동화
- 운영 로그 확보 및 주기적 데이터 관리
- 반복 작업의 안정적 수행을 위한 스크립트 활용

### BI & Data Flow Understanding

- MotionBoard 중심 BI 환경
- MES · APS · BI 간 데이터 흐름 전반 이해

---

## IV. Operating Environment Overview

### 1. Manufacturing Sites
총 4개 제조 거점의 MES 및 DB 운영 담당

**K 거점**
- 데이터 규모: 소
- 이용자 수: 적음
- 시스템 부하: 낮음
- 특이사항: 테스트 및 안정성 검증에 유리한 경량 거점

**L 거점**
- 데이터 규모: 중
- 이용자 수: 다수
- 시스템 부하: 중간 수준
- 특이사항: 일상 운영 및 BI 활용 빈도 높음

**B 거점**
- 데이터 규모: 대
- 이용자 수: 최다
- 시스템 부하: 매우 높음
- 특이사항: 성능 이슈 및 장애 대응 빈도가 가장 높은 핵심 거점

**M2 거점**
- 데이터 규모: 최대
- 이용자 수: 많음
- 시스템 부하: 매우 높음
- 특이사항: 타 거점과 상이한 MES 구조를 사용하는 특수 거점

### 2. System Structure
- K / L / B : 동일한 MES · APS 구조
- M2 : 별도 구조의 MES · APS 운영

### 3. BI Environment
- AppSheet
- Python 기반 자체 BI
- Looker Studio  
- **Main BI: MotionBoard (실시간 연계성 및 운영 안정성 중시)**

---

## V. Project Overview

### Project 1. 신규 MES 도입 (M1)
**목적**
- MES 미도입 제조 거점에 신규 MES 구축
- 업무 표준화 및 시스템 기반 운영 체계 확립

**주요 수행 내용**
- 현장 워크플로우 분석 및 문서화
- 기존 시스템과 신규 MES 병행 운영 가능성 검토
- 관리 필요 데이터 항목 도출
- MES·APS 공통 활용 데이터 구조 초안 정의

**역할**
- 현장 인터뷰 기반 프로세스 분석
- 핵심 관리 데이터 정의 참여
- 데이터 흐름 관점의 시스템 구조 검토

---

### Project 2. BI 조회 구조 개선 및 MV 구축
**배경**
- 실시간 쿼리 기반 BI 구조로 인한 DB 부하 증가

**개선 방향**
- 조회 빈도 높은 BI 대상 MV 도입
- 실시간성보다 안정성과 성능 중시

**효과**
- DB 부하 감소
- BI 응답 속도 개선
- 운영 안정성 확보

---

### Project 3. MES 시스템 유지보수 및 운영 안정화
- C# · SQL 기반 기능 수정 및 로직 개선
- 데이터 오류 및 비정상 동작 원인 분석
- 재발 방지를 고려한 데이터 처리 구조 개선

**효과**
- 반복 발생하던 운영 오류 감소
- 현장 업무 흐름과 시스템 간 정합성 개선

---

### Project 4. BI 정보 추출 및 운영 데이터 제공
- PostgreSQL 기반 운영·경영 지표 데이터 설계
- BI 요구사항 기반 SQL 작성
- MES·APS·BI 데이터 흐름 정리

---

## VI. Incident Response & Troubleshooting

(이하 Case 1~4 내용은 **지금 원문 그대로 유지**)

---

## VII. DBA Mindset & Career Direction

저는 장애나 성능 저하를 마주했을 때  
증상이 아닌 데이터의 상태, 흐름, 기준부터 점검하는 방식으로 문제를 해결해 왔습니다.

MES·APS 운영 환경에서 반복적으로 확인한 사실은  
문제의 대부분이 애플리케이션이 아닌 데이터 구조와 정합성 관리 부재에서 비롯된다는 점이었습니다.

앞으로는 문제가 발생하기 전에 예방할 수 있는 구조와 운영 체계를 설계하는  
**신뢰 중심 DBA**로 성장하고자 합니다.

---

## VIII. Project Management & Documentation

### Git
- SQL, 배치 스크립트, 애플리케이션 연계 로직 변경 이력 관리
- 장애 대응 시 수정 내역을 커밋 단위로 추적
- 운영 영향이 있는 변경 사항의 명확한 기록 유지

### Google Drive
- 현장 워크플로우 문서
- 데이터 구조 정의 및 운영 기준 문서
- 협력사·현장 담당자 공유 자료 관리

운영 환경에서는 **누가, 언제, 왜 변경했는지**를 추적할 수 있어야 한다고 생각합니다.  
변경 이력을 남기는 문서화와 형상 관리를 통해 운영 안정성을 유지했습니다.

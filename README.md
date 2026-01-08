# PickIt 🗳️  
AWS 기반 실시간 투표 웹 서비스 (Team Project)

PickIt은 클라우드 컴퓨팅 수업에서 진행한 **팀 프로젝트**로,  
AWS 서버리스 아키텍처를 활용해 간단한 **투표 생성 및 집계 기능**을 구현한 웹 서비스입니다.

---[PickIt 최종발표.pdf](https://github.com/user-attachments/files/24488696/PickIt.pdf)

---

## 📌 Project Overview
- **프로젝트 유형**: 팀 프로젝트 (Cloud Computing 수업)
- **개발 목적**:  
  클라우드 환경에서의 **서버리스 구조**, 데이터 흐름, API 연동 방식을 이해하고  
로컬 환경과의 차이를 경험하는 것
- **개발 기간**: (학기 중 프로젝트)

---

## 🧩 Architecture
- **AWS Lambda**: 서버리스 백엔드 로직 처리
- **Amazon API Gateway**: 클라이언트 ↔ 서버 API 연결
- **Amazon DynamoDB**: 투표 데이터 저장
- **Amazon S3**: 정적 리소스 저장
- **CloudWatch**: 로그 확인 및 동작 모니터링

> 서버를 직접 운영하지 않고, AWS 관리형 서비스를 조합하여  
> 기능 단위로 동작하는 구조를 경험하는 데 초점을 두었습니다.


## 🙋 My Role
- 팀 프로젝트에서 **Backend 일부 담당**
- DynamoDB를 이용한 데이터 저장 구조 이해 및 적용
- S3를 활용한 정적 리소스 관리 흐름 학습
- 서버리스 환경에서의 **데이터 처리 흐름과 구조 이해**

> 세부 기능 구현보다는 **클라우드 환경에서 데이터가 저장·처리되는 전체 흐름을 이해**하는 데 중점을 두었습니다.

## ⚠️ Notes
- 본 프로젝트는 **학습 목적의 팀 프로젝트**입니다.
- 일부 기능 및 코드 구조는 수업 범위와 팀 구성에 따라 단순화되어 있습니다.

---

## 📎 Related
- Course: Cloud Computing
- Type: Team Project / Study Purpose

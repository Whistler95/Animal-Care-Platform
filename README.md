# 🐾 Animal Care Platform
> **Spring 기반 유기동물 보호·입양·봉사·후원 통합 관리 플랫폼**

![MainBanner](이미지URL_나중에추가)  

---

## 📌 프로젝트 소개
유기동물 보호소, 입양 희망자, 봉사자를 연결하여  
**회원가입 → 활동 참여 → 후원/포인트 지급까지** 전 과정을 통합 관리할 수 있는 플랫폼입니다.  

이 프로젝트는 **Spring Legacy 기반 MVC 구조와 REST API 개발**을 학습하기 위해 진행한 프로젝트로,  
**이메일 인증, 계정 잠금, 포인트 지급** 등 실제 서비스에서 사용되는 주요 기능을 직접 구현했습니다.

---

## 🛠 Tech Stack
| Backend | Frontend | Database | Infra | Tools |
|---------|----------|----------|-------|-------|
| Java 11 | JSP / JSTL / JavaScript | MySQL | AWS EC2 (WAR 배포) | Git / GitHub |
| Spring 5.3.33 | HTML / CSS | MyBatis | Maven | Postman |

---

## ✨ 구현 기능
- ✅ 회원가입 / 로그인 (이메일 인증, 계정 잠금, 포인트 지급)  
- ✅ 아이디 / 비밀번호 찾기 (이메일 인증, 새 비밀번호 변경)  
- ✅ 마이페이지 (회원 정보 수정, 포인트 내역, 활동 내역)  
- ✅ 봉사 / 입양 / 후원 기능 (신청, 후기 작성, 포인트 지급)  
- ✅ 관리자 페이지 (회원 관리, 포인트 설정)  
- ✅ 메인 페이지 (카드형 UI, 지역별 보호소, 최신 게시글/후원 캠페인)  

---

## 📂 프로젝트 구조
> **Spring Legacy (MVC, JSP 기반)**  
> MyBatis + MySQL + Maven + AWS EC2 (WAR 배포)

📌 **ERD & 구조**  
- [ERD 전체 보기](ERD_URL_추가)  
- 핵심 테이블 : `USERS`, `SHELTERS`, `VOLUNTEERS`, `DONATIONS` ...

---

```markdown
## 📥 Clone Repository
```bash
git clone https://github.com/Whistler95/Animal-Care-Platform.git
```
> Import to STS (Spring Tool Suite) as Maven Project  
> DB 계정 및 URL 설정 후 실행

---

## 🎥 시연 영상
📌 [유튜브 시연 영상 보기](#)  

📌 [포트폴리오 PPT 보기](#)

---

## 📌 담당 역할
- 전체 기획 및 설계, DB 모델링  
- Spring Legacy(5.3.33) 기반 프로젝트 구조 사전설계 및 환경 구성  
  - Boot처럼 사용할 수 있도록 디렉터리 구조 설계 및 기술 선정  
  - Maven 기반 의존성 설정, XML 기반 설정파일 구성 및 라이브러리 통합  
  - WAR 패키징 및 배포 환경 대응 (contextPath 활용 포함)  
- 회원가입 / 로그인 / 마이페이지 흐름 전반 구현  
- 이메일 인증, 계정 잠금, 포인트 지급 기능 구현  
- 메인 페이지 전체 기획 및 카드형 UI 구조 설계/구현 담당  
- 아이템 리서치부터 최종 발표 및 전체 PPT 작성/발표까지 전 과정 직접 수행  

---

## 📎 추가 링크
- 📄 [포트폴리오 PPT 보기](#)  
- 🌐 [Notion 프로젝트 정리](#)  
- 🚀 **배포된 사이트 바로가기 (추가 예정)**  
```

# 학과 통계 열람기

---

## 프로젝트 소개

성적표 한 장으로 졸업 요건, 이수 현황, 누락 과목까지 자동으로 정리해주는 웹 대시보드 서비스입니다.

---

## 주요 기능

📸 성적표 이미지 업로드 (캡처 기준)

🔍 OCR로 교과목명, 학점, 학기 추출

📊 전공/교양 이수율 계산 + 졸업요건 자동 체크

🎯 현재는 25학번 컴퓨터공학과만 지원, 이후 확장 예정

---

## 🗓️ 프로젝트 일정

| 기간 | 내용 | 진행 상황 |
|------|------|------------|
| ~ 6/29 (일) | 개인 과제 제출 | ✅ 완료 |
| 6/30 (월) | 팀 및 멘토 배정 | ✅ 완료 |
| 7/3 (목) | OT (오리엔테이션) | ✅ 완료 |
| 7/4 (금) ~ 7/10 (목) | 주제 선정 및 기획 | ✅ 완료 |
| 7/8 (화) ~ 7/12 (토) | 기능 명세서 작성 + DB 설계 | 🔄 진행 중 |
| 7/11 (금) | 1주차 과제 발표 (비대면) | ✅ 완료 |
| 7/13 (일) ~ 7/19 (토) | 백엔드/프론트 기본 구조 구현 | 🛠️ 예정 |
| 7/18 (금) | 2주차 과제 제출 (README + 기능 명세서) | 🗓 예정 |
| 7/20 (일) ~ 7/26 (토) | OCR 연동 + 데이터 처리 로직 구현 | ⏳ 예정 |
| 7/27 (일) ~ 8/2 (토) | UI 완성 및 프론트/백 연동 테스트 | ⏳ 예정 |
| 8/3 (일) | 중간 발표 (비대면) | 🗓 예정 |
| 8/3 ~ 8/9 (토) | 코드 리팩토링 + 사용자 피드백 반영 | ⏳ 예정 |
| 8/10 ~ 8/15 (금) | 배포 준비 + 테스트 마무리 | ⏳ 예정 |
| 8/16 (토) | 최종 발표 (대면) | 🗓 예정 |

---

## 📁 시작 가이드

### Requirements

#### 🖥️ Backend
- [Python 3.10 이상](https://www.python.org/downloads/release/python-3100/)
- [Django 4.0](https://www.djangoproject.com/)
- [Django REST Framework](https://www.django-rest-framework.org/)
- [PostgreSQL](https://www.postgresql.org/)
- Kakao OCR API

#### 💻 Frontend
- [Node.js 14.19.3](https://nodejs.org/en)
- [Npm 9.2.0](https://docs.npmjs.com/cli/v9/commands/npm)  
- [React.js](https://react.dev/)
- [Axios](https://axios-http.com/)
- [Chart.js](https://www.chartjs.org/)

#### 🎨 Design
- [Figma](https://www.figma.com)
- [Notion](https://www.notion.com/) (플로우 차트 및 명세 관리용)

---


## 팀 구성

<table style="width:100%; border-collapse: collapse;">
  <tr>
    <th style"border:1px solid #ddd; padding:8px; text-align:center;">팀장 신성현</th>
    <th style"border:1px solid #ddd; padding:8px; text-align:center;">이나나</th>
    <th style"border:1px solid #ddd; padding:8px; text-align:center;">강 산</th>
    <th style"border:1px solid #ddd; padding:8px; text-align:center;">김의림</th>
    <th style"border:1px solid #ddd; padding:8px; text-align:center;">곽유나</th>
  </tr>
  <tr>
    <td style="border:1px solid #ddd; padding:8px; text-align:center;">
      <img width="160px" src="https://avatars.githubusercontent.com/u/188848771?v=4" />
    </td>
    <td style="border:1px solid #ddd; padding:8px; text-align:center;">
       <img width="160px" src="https://github.com/user-attachments/assets/3471d8d4-b25d-49b1-8980-a23f877fbbc8" />
    </td>
    <td style="border:1px solid #ddd; padding:8px; text-align:center;">
      <img width="160px" src="https://avatars.githubusercontent.com/u/139611910?s=400&u=c3c4a6eb05429b73e109293cac9ad11680365b1a&v=4" /> 
    </td>
    <td style="border:1px solid #ddd; padding:8px; text-align:center;">
      d
    </td>
    <td style="border:1px solid #ddd; padding:8px; text-align:center;">
      <img width="160px" src="https://avatars.githubusercontent.com/u/195542716?s=400&u=42372de0252734a071646c6136a851f9c088cf62&v=4" />
    </td>
  </tr>
  <tr>
    <td style="border:1px solid #ddd; padding:8px; text-align:center;"><strong>21학번 백엔드</strong></td>
    <td style="border:1px solid #ddd; padding:8px; text-align:center;"><strong>23학번 백엔드</strong></td>
    <td style="border:1px solid #ddd; padding:8px; text-align:center;"><strong>23학번 프론트엔드</strong></td>
    <td style="border:1px solid #ddd; padding:8px; text-align:center;"><strong>23학번 프론트엔드</strong></td>
    <td style="border:1px solid #ddd; padding:8px; text-align:center;"><strong>24학번 디자이너</strong></td>
  </tr>
</table>

---

## 기술 스택

### Backend
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Django REST Framework](https://img.shields.io/badge/Django%20REST%20Framework-009688?style=for-the-badge&logo=django&logoColor=white)

### Database
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

### OCR 처리
![Kakao OCR](https://img.shields.io/badge/Kakao%20OCR-FEE500?style=for-the-badge&logo=kakaotalk&logoColor=black)
![Tesseract](https://img.shields.io/badge/Tesseract-0099FF?style=for-the-badge&logo=tesseract&logoColor=white)

### Visualization
![Chart.js](https://img.shields.io/badge/Chart.js-100000?style=for-the-badge&logo=chartdotjs&logoColor=F7931E)


---

## 아키택쳐

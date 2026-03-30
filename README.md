<img src="https://avatars.githubusercontent.com/u/213369098?s=200&v=4" width="100"/> <br/>
# 🎯 프로젝트 개요
### "교통사고 해결의 새로운 길, DOROLAW가 여러분과 함께합니다."
AI 기반 교통사고 과실 비율 분석 및 변호사 상담 매칭 플랫폼

### 📆 프로젝트 정보
삼성 청년 SW 아카데미 12기 특화 프로젝트 A501 <br/>

주제: AI 영상처리 <br/>
기간: 2025.02 ~ 2025.04 (7주) <br/>
인원: 6명 (FE 2명, BE 2명, AI 2명) <br/>
<br/>

### ⭐ 프로젝트 기획 배경
손해보험협회 조사 결과에 따르면, <br/>
교통사고 당사자들은 서로가 피해자이면서 무과실을 주장하고, 서로 다른 관점에서 사고를 바라보고 있습니다. <br/>
분쟁심의위원회의 최초 과실 비율 판정까지 평균 75일, 법원 민사 소액 1심 확정까지는 평균 137일이 소요됩니다. <br/>

DOROLAW는 AI 모델을 활용하여 교통사고 영상을 약 20초 간 분석하여 객관적인 과실 비율과 분석 결과를 제공합니다. <br/>
분석 결과에 대한 추가 상담을 원할 경우, 교통사고 전문 변호사와의 상담 매칭 서비스를 이용할 수 있습니다. <br/>
<br/>

### 🖥️ 기술 스택
|분류|사용 기술|
|:---:|:---:|
|**Backend**|Spring Boot 3.4.2, JDK 17, IntelliJ|
|**Frontend**|React 19.0.0, TypeScript, Tailwind CSS, Vite, VS Code|
|**AI**|Python, Pytorch, TSN, YOLOv8|
|**데이터베이스**|MySQL 8.0.41|
|**인프라**|AWS EC2, Docker|
|**기타 설정**|Nginx, RabbitMQ, Prometheus|
|**CI/CD**|Jenkins|
<br/>

# 🚀 주요 기능
<div align="center">
  <video src="https://github.com/user-attachments/assets/78db5c2d-a840-49b9-8ea3-a3a5785af26d" controls></video>
</div>

### 1. AI 기반 교통사고 과실 비율 분석 서비스
* 블랙박스 영상 업로드 시 공개/비공개 여부를 설정할 수 있습니다.
* 약 20초 후 분석 완료 알림과 함께 과실 비율 분석 결과 확인이 가능합니다.

### 2. 과실 비율 분석 결과 게시판
* 영상 업로드 시 공개 허용한 게시글만 조회할 수 있습니다.
* 본인 외 다른 이용자의 사고 영상과 분석 결과를 참조할 수 있습니다.
* 추가 상담을 원할 시 변호사 상담 신청 게시판에 게시글을 작성하여 상담을 신청할 수 있습니다.
* 교통사고 분석 결과는 PDF 파일로 저장하여 언제 어디서나 열람할 수 있습니다.

### 3. 변호사 상담 신청 서비스
* 15분/30분 단위의 전화 상담, 화상 상담, 방문 상담 중 원하는 방식을 선택할 수 있습니다.
* 변호사가 등록한 상담 가능 일자에 상담을 신청할 수 있습니다.
* 상담 접수 및 상담 신청 완료 알림이 사용자와 변호사 회원 모두에게 전송됩니다.

### 4. 마이페이지 (나의 분석 결과, 상담 신청 내역)
* 회원 정보를 관리할 수 있습니다.
* 비공개 영상 분석 결과를 조회할 수 있습니다.
* 상담 신청 내역을 조회할 수 있습니다.
<br/>

# 📈 성과
* <strong>"7주"</strong>라는 제한된 시간 안에 프로젝트 기획과 MVP 기능 구현을 성공적으로 완료하였습니다.
* AI가 분석한 교통사고 분석 결과를 <strong>영상 업로드 20초 후 즉시 확인 가능</strong>합니다.
* <strong>Jira Automation</strong>을 통해 팀원 간 실시간 업무 진행 상황 파악 및 역할 분담을 통해 <strong>원활한 협업</strong>을 이루었습니다. <br/>
<br/>

---
## 👨‍👩‍👧‍👦 팀원 소개
|팀장 / AI|FE 리드|FE|BE 리드|BE|AI 리드|
|:---:|:---:|:---:|:---:|:---:|:---:|
|<img src="https://avatars.githubusercontent.com/u/154123905?v=4" width="150"/>|<img src="https://avatars.githubusercontent.com/u/125232426?v=4" width="150"/>|<img src="https://avatars.githubusercontent.com/u/175284278?v=4" width="150"/>|<img src="https://avatars.githubusercontent.com/u/177285499?v=4" width="150"/>|<img src="https://avatars.githubusercontent.com/u/113077033?v=4" width="150"/>|<img src="https://avatars.githubusercontent.com/u/66278677?v=4" width="150"/>|
|[정도영](https://github.com/SorrowAddict)|[유준선](https://github.com/steepheno)|[여현승](https://github.com/hyvnsevng)|[김용국](https://github.com/dragonsoup1)|[한동민](https://github.com/mins-git)|[정은아](https://github.com/eunah320)|

<br/>

## ⚙️ 아키텍처
<div align="center">
  <img src="https://jsundev.vercel.app/images/dorolaw/architecture.png"/>
</div>
<br/>

## 📅 Jira 일정 관리
<div align="center">
  <img src="https://github.com/user-attachments/assets/a501c593-cb37-47e7-9aed-3ec1d66e8895"/>
</div>

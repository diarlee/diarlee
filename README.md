# 안녕하세요😇<br> 새로운 경험을 즐기는 백엔드 개발자 이병수입니다

 <!-- jd보고 회사가 원하는 keyword뽑아서 슬로건 작성 -->

## 💫 About me
### "Action cures fear"
두려운건 해보지 않아서다. 먼저 두려움을 가지지 말자. 의심하지말고 실천해보자! 

## ⚒️ Skills
<!-- 기술 역량에 대한 근거 적기
- 문제풀이, or 프레임워크에 대한 개념 등을 근거로 제시 -->
<!-- 그룹 묶기 -->
|<b>Hard</b>|<b>Soft</b>|
|-------------|-----------------|
| Java / Spring &nbsp; ⭐⭐⭐ &nbsp;&nbsp; <br> Spring Data JPA &nbsp; ⭐⭐ <br> SQL &nbsp; ⭐⭐⭐ <br> Python / FastAPI &nbsp; ⭐⭐ <br> Tableau &nbsp; ⭐⭐  | 책임감 &nbsp; 🌟🌟🌟🌟 <br> 커뮤니케이션 &nbsp; 🌟🌟🌟🌟 <br> 리더쉽 &nbsp; 🌟🌟🌟 <br> -- <br> --|

## 👩🏻‍💻 Projects
<!-- 프로젝트 요약 *****
- 프로젝트 설명
- 기획 의도(하게된 이유),,, 데이터 기반!
- 내 기여
- 도전적인 부분들 (중요)
- 해결 과정 (중요)
=> 이 과정에서의 사고과정 + 방향, 기술 등 선택에 대한 근거를 어필하는게 포인트 -->

<!-- 하기 싫었던 일을 하게된 상황에 대해서도 설명해주면 좋음 -->
|    Name     |    Descrption   |
|-------------|-----------------|
| [weSync](https://github.com/diarlee/WeSync) <br> 2024.04 <br> ~ 2024.05 | 🎙️ 온라인 아카펠라 팀 연습 플랫폼 <br><br> ❓ 배경 <br> &nbsp; (대학교 아카펠라 동아리에서 활동했던 팀장의 경험 기반) <br> &nbsp; 1. 포지션별 반주를 따로 구해야 해서 개인 연습이 어려움 <br> &nbsp; 2. 모든 팀원의 스케줄을 맞춰야 해서 팀 연습이 어려움 <br> &nbsp; 3. 연습을 기록으로 남기기 번거로움 <br><br> 💡 목표 <br> &nbsp; Ⅰ. PDF 형태의 아카펠라 악보를 음원화하여 파트별 반주 제공 <br> &nbsp; Ⅱ. 반주 개별 재생 및 동시 재생 기능으로 개인 연습 환경 제공 <br> &nbsp; Ⅲ. 팀 스페이스 제공 및 개인 녹음본 공유로 팀 관리 기능 제공 <br><br> ✅ 맡은 역할 <br> &nbsp; [Java 백엔드 개발 및 인프라] <br> &nbsp; a. ERD 설계 <br> &nbsp; b. 팀 공지글, 녹음, 피드백 도메인 개발 <br> &nbsp; c. Jenkins로 CI/CD 파이프라인 구축 <br> &nbsp; d. EC2, S3 기반에서 Docker를 사용하여 서비스 배포 <br><br> 💥 이슈 <br> &nbsp; ㄱ. 녹음 API 개발에서 조회가 여러 종류가 있는데 각 조회 Response의 필드들이 중복되는 부분이 많음 + 빌더 패턴 적용 <br> &nbsp; ➡️ ResponseDto 추상클래스를 정의하고 각 조회마다 상속받아 사용하여 중복을 줄임 + SuperBuilder를 적용하여 상속 관계에서도 빌더 패턴 그대로 적용 <br> &nbsp; ㄴ. 각 도메인 API 개발에서 조회 구현시에 JPA 쿼리메서드를 사용. 연관관계 조회시 쿼리가 중복으로 생성되는 문제 발생 (N + 1 문제) <br> &nbsp; ➡️ JPQL Fetch Join을 사용. 한 번의 쿼리로 연관관계까지 모두 조회하도록 최적화 <br> &nbsp; ㄷ. 배포 후 프론트엔드의 static 파일 요청경로 에러 발생 <br> &nbsp; ➡️ Nginx를 static 서버로 사용하여 해결. 빌드된 static 파일들을 Nginx 내부로 복사하도록 Jenkins 스크립트 구성 + Nginx location 블록으로 static 파일 요청을 Nginx 내부로 돌림
| [AI BaseBall Clips(ABC)](https://github.com/diarlee/ABC) <br> 2024.01 <br> ~ 2024.02 | ⚾ 야구 하이라이트 자동생성 프로그램 <br><br> ❓ 배경 <br> &nbsp; - 하이라이트의 정의 : 스포츠 등에서, 가장 중요하거나 흥미 있는 장면 <br> &nbsp; - 사람마다 하이라이트의 기준이 다를 수 있음 <br> &nbsp; - 야구팀을 응원하는 이유 중 '특정 선수의 팬이여서' 16.5% <br><br> 💡 목표 <br> &nbsp; Ⅰ. 중계영상에서 자동으로 선수별 하이라이트를 제공 <br> &nbsp; Ⅱ. 이닝별 경기정보를 함께 제공 <br><br> ✅ 맡은 역할 <br> &nbsp; [Python 백엔드 개발 및 팀장] <br> &nbsp; a. OCR을 활용하여 동영상에서 장면별 선수를 구분 <br> &nbsp; b. Python 라이브러리로 동영상을 타석별로 편집 <br> &nbsp; c. Redis 메세지 통신 구현 <br> &nbsp; d. Jira로 팀 작업 관리 주도 <br><br> 💥 이슈 <br> &nbsp; ㄱ. 설계과정에서 AI 얼굴인식모델을 사용하여 장면별로 선수를 인식하는 방식을 선택 <br> &nbsp; But 동영상의 특성(동적, 조명 변화, 배경 변화)과 <br> &nbsp; 야구 경기의 특성(모자 착용, 투구 자세와 타격 자세로 인해 측면 얼굴만 보임)으로 <br> &nbsp; 선수 구분 실패 <br> &nbsp; ➡️ AI 텍스트 인식(OCR)을 사용하여 중계화면 스코어보드에서 선수 이름을  인식하는 방향으로 선회 <br> &nbsp; ㄴ. 스코어보드의 선수 이름 외에도 필요치 않은 텍스트(광고판 등)까지 인식하여 동영상 처리가 늦어지는 문제 발생 <br> &nbsp; ➡️ 화면을 4분할하여 스코어보드가 있는 지역만 OCR을 적용하는 로직을 개발하여 동영상 처리 시간 단축 <br> &nbsp; ㄷ. OCR의 정확도 문제 발생(이병수를 이벼ㅇ수로 인식) <br> &nbsp;  ➡️ LCS알고리즘이 구현된 라이브러리를 사용, 텍스트를 자모 단위로 비교하여 정확도 향상|
| [물어바종](https://github.com/diarlee/FishFinder) <br> 2024.02 <br> ~ 2024.03 <br> | 🐟 수산시장 이용 도우미 <br><br> ❓ 배경 <br> &nbsp; 1. 흥정에 대한 부정적 인식 - 보통▪부정적 60% 이상 <br> &nbsp; 2. 수산물 가격에 대한 낮은 신뢰 수준 - 보통▪부정적 80% 이상 <br><br> 💡 목표 <br> &nbsp; Ⅰ. 수산시장 이용이 익숙하지 않은 사람들의 어종 및 시세 파악 어려움을 해소 <br> &nbsp; Ⅱ. 정보를 교환하는 편의를 제공 <br><br> ✅ 맡은 역할 <br> &nbsp; [Java 백엔드 개발] <br> &nbsp; a. JPA 상속관계 매핑을 적용한 Entity 개발 <br> &nbsp; b. 어노테이션을 활용한 JPA Soft Delete 구현 <br> &nbsp; c. 카카오 Oauth 로그인 구현 <br> &nbsp; d. 회원 도메인 개발 <br><br> 💥 이슈 <br> &nbsp; ㄱ. Kakao redirectUrl 수정 과정에서 배포 서버의 프런트 환경 변수만 변경하고 <br> &nbsp; 백엔드 환경 변수를 변경하지 않아 에러 발생 <br> &nbsp; ➡️ 프론트, 백엔드 각각 로컬에서 재테스트 후 문제없자 배포서버의 로그 확인하여 디버깅


## 🔎 Profile
🎓 인하대학교 경제학/소프트웨어융합공학 &nbsp; 2017.02 - 2023.08

📖 삼성 청년 SW 아카데미(SSAFY) &nbsp; 2023.07 - 2024.06

## 🏅 Awards
🎖️ SSAFY 2학기 공통 프로젝트 우수상

🎖️ SSAFY 2학기 특화 프로젝트 우수상
<!--
**diarlee/diarlee** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

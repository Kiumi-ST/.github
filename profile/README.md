### 2024 Corner 정규 프로젝트

<p align="center">
<img width="329" alt="Kiumi 키움이 로고" src="https://github.com/user-attachments/assets/5946505c-fd48-4d9b-9728-95b503fbf3f9" />
</p>

---

## **Kiumi 키움이**

> **덕성여자대학교 개발 소모임 _'코너'_ 팀 '에스티(ST)'**  
>
> ⚡ **키오스크의 빠른 확산**  
> 키오스크는 현대 생활 속 필수 요소가 되었으나, **매장마다 전혀 다른 UI/UX**로 인해 많은 사용자가 **혼란**을 겪고 있습니다.
>
> 💡 **해결책**  
> 저희는 사용자가 다양한 업체의 키오스크 **인터페이스를 미리 경험**할 수 있는 **서비스**를 제공합니다.

### 📅 개발 기간  
2024년 3월 ~ 2024년 10월

---

## **배포 주소**

- **개발 버전**: [https://www.duksung.ac.kr/main.do](https://www.duksung.ac.kr/main.do)  
- **프론트 서버**: [https://www.duksung.ac.kr/main.do](https://www.duksung.ac.kr/main.do)  
- **백엔드 서버**: [http://13.125.162.28:8080](http://13.125.162.28:8080)  
- **플라스크 서버**: [https://kiumi-ef992.du.r.appspot.com](https://kiumi-ef992.du.r.appspot.com)

---

## **팀 소개**

|       박유정       |       김다빈        |      조소윤        |       정지민       |                                                                                                               
| :-----------------: | :-----------------: | :----------------: | :----------------: | 
| <img width="160px" src="https://github.com/user-attachments/assets/e664eee2-7231-47d7-9c49-0950a1a6eca1" /> | <img width="160px" src="https://github.com/user-attachments/assets/e6222b60-85a0-4971-81c1-eaf7ab8b36a6" /> | <img width="160px" src="https://github.com/user-attachments/assets/889efc14-d2df-4fef-996b-8f263fedad92"/> | <img width="160px" src="https://github.com/user-attachments/assets/8b631400-fd68-4b60-8e15-43398522105a"/> |
| 프론트엔드 | 프론트엔드 | 프론트엔드<br>백엔드 | 프론트엔드<br>백엔드 | 
| [@qkrdbwjd](https://github.com/qkrdbwjd) | [@dalpaeng6](https://github.com/dalpaeng6) | [@soyoon1](https://github.com/soyoon1) | [@sunflwwer](https://github.com/sunflwwer) |
| 덕성여자대학교 <br> 컴퓨터공학과 3학년 (휴학) | 덕성여자대학교 <br> 컴퓨터공학과 3학년 | 덕성여자대학교 <br> 컴퓨터공학과 3학년 (휴학) | 덕성여자대학교 <br> 컴퓨터공학과 3학년 |

---

## **프로젝트 소개**
**키움이(키오스크 배움이)**는 사용자가 실제 키오스크와 유사한 **인터페이스를 체험하고 학습**할 수 있는 애플리케이션입니다.

- **사용자의 경험 개선**: 키오스크에 익숙하지 않은 사용자도 쉽고 빠르게 학습할 수 있습니다.
- **비회원제 지원**: 디지털 소외계층을 위해 비회원제로 편리하게 접근할 수 있습니다.
- **트래킹 데이터 및 설문 조사**: 사용자 데이터와 설문 조사 결과를 통해 서비스의 확장성과 수익 창출 가능성을 확보하였습니다.

---

## **시작 가이드**

### Requirements
- **MySQL 8.0**
- **Android SDK**
- **JDK 17**
- **Python 3.12.4**

### Installation and Running

#### **Spring Boot Server (IntelliJ IDEA 사용)**
1. 레포지토리 클론:
   ```bash
   $ git clone https://github.com/Kiumi-ST/back-end.git
   $ cd back-end
   ```
2. IntelliJ IDEA에서 `build.gradle` 파일을 열어 프로젝트 로드.
3. 초록색 `Run` 버튼을 눌러 서버 시작.

#### **Flask Server**
1. 레포지토리 클론:
   ```bash
   $ git clone https://github.com/Kiumi-ST/back-end-flask.git
   $ cd back-end-flask
   ```
2. 가상 환경 설정:
   ```bash
   $ python -m venv venv 
   $ venv\Scripts\activate 
   ```
3. 의존성 설치 및 서버 실행:
   ```bash
   $ pip install -r requirements.txt
   $ flask --app app run --host=0.0.0.0 --port=8000
   ```

#### **Client (Android Studio 사용)**
1. 레포지토리 클론:
   ```bash
   $ git clone https://github.com/Kiumi-ST/front-end.git
   $ cd front-end
   ```
2. Android Studio에서 `front-end` 폴더 열기.
3. `Run` 버튼을 눌러 앱 실행.

---

## **주요 기능**
- **키오스크 연습 기능**: 실제 키오스크와 유사한 UI/UX 연습 가능.
- **순서 지침**: 키오스크 사용법을 익히기 위한 조작 유도.
- **사용자 반응 추적**: 얼굴 인식 및 화면별 체류 시간 분석을 통해 어려움을 추적.

---

## **기술 스택**

| **분류**              | **기술**                                                                                                        |
|-----------------------|----------------------------------------------------------------------------------------------------------------|
| **개발 환경**          | Android Studio, IntelliJ IDEA, Visual Studio Code, Windows                                                     |
| **프로그래밍 언어**    | Java, Kotlin, Python, SQL                                                                                      |
| **백엔드 프레임워크**   | Spring Boot, Flask                                                                                            |
| **데이터베이스 & 클라우드** | MySQL, Google Cloud, Firebase                                                                                  |
| **버전 관리 & 빌드 도구** | Git, Gradle                                                                                                   |
| **협업 & 커뮤니케이션** | GitHub, Discord, Notion, Google Drive, Figma, ERDCloud                                                       |

---

## **API**

| Description        | Method | API URI                        | Request                                                                                                                                                                     | Response (예시)                                                                                                                                   |
|--------------------|--------|-------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| 개선점 설문          | POST   | http://localhost:8080/survey   | { "q1": 4.5, "q2": "매우 편리하다", "q3": "원하는 상품을 찾기 어렵다", "q4": "없다", "q5": "좋아요" }                                                                             | { "isSuccess": true, "msg": "개선점 설문 결과 저장 완료" }                                                                                         |
| 개선안 투표          | POST   | http://localhost:8080/votingresult | { "question1": "기존안", "question2": "매우 편리하다", "question3": "좋아요" }                                                                                                   | { "isSuccess": true, "msg": "개선안 원본 투표 결과 저장 완료" }                                                                                     |
| 사용자 감정 인식     | POST   | http://localhost:8000/analyze-deepface | Content-Type: multipart/form-data Body: - file: 이미지 파일 - screen_name: 화면 이름                                                                                          | 코드: 200 OK { "dominantEmotion": "angry", "isDifficult": true } { "dominantEmotion": "happy", "isDifficult": false } <br> 400 BAD REQUEST: 여러 케이스 |

---

## **아키텍처**
![image01.png](./image1.png)

---

## **UI Preview**
프로젝트의 주요 화면을 확인하고 싶다면, 아래의 영상을 클릭해 주세요!

[![UI Preview](http://img.youtube.com/vi/FJjB-nzOKT0/0.jpg)](https://youtu.be/FJjB-nzOKT0)

프로젝트의 사용자 인터페이스(UI)와 기능 시연을 영상으로 제공합니다. 
영상에서는 각 화면의 구성과 기능 동작을 자세히 설명합니다.

---

**🔗 참고**: UI/UX 디자인은 Figma로 제작되었습니다.

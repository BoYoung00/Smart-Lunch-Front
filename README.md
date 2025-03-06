## 점심 어때 (앱)


'점심 어때'는 스마트 메뉴 추천 및 관리 기능을 제공하는 모바일 서비스입니다. 사용자는 메뉴를 추천 받아 주문할 수 있으며, 점심시간 혼잡도 확인 및 미리 주문 기능을 통해 대기 시간을 줄일 수 있습니다. 또한, 캘린터를 통한 영양소와 칼로리 섭취량을 조회하여 건강한 식단 관리를 지원합니다. 식당 관리자의 경우 본인 식당의 메뉴를 관리할 수 있으며, 새로운 주문 알림 기능 등을 제공 받을 수 있습니다.

---

### 📅 개발 기간
- 설계 : 2024년 09월 ~ 2024년 12월 (약 3개월)
- 구현 : 2024년 11월 (약 3주)

---

### 📌 주요 기능

#### 1. 메뉴 추천
   -  고객에게 메뉴를 추천하는 기능


#### 2. 주문하기
   - 카카오페이 결제를 통해 고객이 메뉴를 주문하는 기능


#### 4. 식단 관리
   - 고객이 주문했던 메뉴의 영양소를 캘린더로 조회하는 기능

    
#### 5. 메뉴 관리
  - 식당 관리자가 식당 메뉴를 관리하는 기능

---

## 🔧 기술 스택
- Frontend: Android, Kotlin
- Backend: Spring Boot, Java
- Database: MySQL
- Deployment: AWS
- Tool: StarUML, Figma, IntelliJ IDEA, Android Studio

---

## 🖥️ 주요 화면

#### 1. 메뉴 추천 및 식당 목록 화면
![image](https://github.com/user-attachments/assets/e9983732-f321-4ebe-b89d-be8bd599a761)

#### 2. 고객 주문 상세 내역 화면
![image](https://github.com/user-attachments/assets/3b0dd28c-22a2-4ade-94b1-6873e8f42ed3)

#### 3. 식단 조회 및 분석 화면
![image](https://github.com/user-attachments/assets/ae98e393-6ae2-4e51-9d18-e58e0575c227)
![image](https://github.com/user-attachments/assets/ea7bf079-1e5d-49ed-8fdf-873877d5e83e)

#### 4. 식당 관리자 주문 접수 조회 화면
![image](https://github.com/user-attachments/assets/053ff61e-e84e-41c0-a0ea-0de9506c55e0)
![image](https://github.com/user-attachments/assets/a92b1480-a6f1-4f94-a335-d9defb2b53c2)

#### 5. 식당 관리자 메뉴 관리 화면
![image](https://github.com/user-attachments/assets/73221720-a421-46f7-870f-60b3f7dc021f)

  
---

## 💥 기술적 도전

|            기술적 도전            | Why | How | Result |
|:------------:|-----|---|------|
| **Jetpack Compose 기반 UI 구현** | 기존 XML 기반 UI보다 효율적인 UI 구성 필요 | Compose의 선언형 UI 방식을 도입하여 레이아웃을 간결하게 구현 | 코드량 30% 감소 및 유지보수 용이성 향상 |
| **Retrofit + Coroutine을 활용한 API 통신 최적화** | 네트워크 요청 시 UI 프리징 방지 및 응답 속도 개선 필요 | Retrofit과 Coroutine을 활용하여 비동기 통신 및 예외 처리 구현 | API 응답 속도 40% 향상 및 사용자 경험 개선 |
| **SharedPreferences 를 통한 로컬 데이터 저장** | 네트워크 연결 없이 데이터 유지 필요 | SharedPreferences를 활용하여 오프라인 데이터 저장 및 조회 기능 추가 | 네트워크 불안정 상황에서도 데이터 유지 가능 |
| **StarUML을 활용한 ERD 및 시스템 설계** | 프로젝트 설계 단계에서 명확한 구조 필요 | ERD, 유스케이스 다이어그램 등을 작성하여 시스템 구조 시각화 | 협업 시 개발 방향성 명확화 |
| **MVVM 패턴 적용 및 모듈화** | UI/비즈니스 로직 분리를 통한 유지보수성 개선 필요 | ViewModel과 Repository 패턴을 활용하여 코드 모듈화 진행 | 코드 재사용성 증가 및 유지보수 편의성 확보 |
| **일정 및 문서 관리** | 체계적인 소프트웨어 개발 프로세스 및 문서화 필요 | SDLC(Software Development Life Cycle)를 적용하여 프로젝트를 설계하고, 각 단계별 산출물(요구사항 명세서, 시스템 설계서, 테스트 계획서 등)을 작성 | 개발 프로세스의 구조화 및 협업 효율성 향상 |


---

## 🎉 산출물 통합 PDF 파일
- https://drive.google.com/file/d/1u8hBSg6m91oSaJsgm5_5_zOqNBtH6cMS/view?usp=drive_link

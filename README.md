# CGEIT 자격증 도우미

이 프로젝트는 **Certified in the Governance of Enterprise IT (CGEIT)** 자격증을 준비하는 데 필요한 도구와 자료를 제공합니다. CGEIT는 IT 거버넌스의 전문성을 인증하는 국제적으로 인정받는 자격증입니다.

---

## **목차**

1. [주요 기능](#주요-기능)
2. [설치 방법](#설치-방법)
3. [사용법](#사용법)
4. [폴더 구조](#폴더-구조)
5. [기여 방법](#기여-방법)
6. [라이선스](#라이선스)
7. [문의](#문의)

---

## **주요 기능**

### 1. 학습 자료
- 5개 CGEIT 도메인별 요약 학습 자료:
  1. **IT 거버넌스 프레임워크 설정**
  2. **IT 자원 전략적 관리**
  3. **이익 실현**
  4. **위험 최적화**
  5. **자원 최적화**
- 사용자 맞춤형 학습 일정 제공.

### 2. 연습 문제 생성기
- 각 도메인별 학습을 강화하기 위한 연습 문제 제공.
- 예제:
  ```python
  print(generate_practice_question("2"))
  # 출력: "조직의 IT 자원 전략을 효과적으로 관리하기 위한 주요 요소는 무엇인가요?"
  ```

### 3. 실습 가이드
- IT 거버넌스 및 위험 관리 시뮬레이션 안내:
  - COBIT 2019 활용 방법.
  - ITIL 프레임워크 구성.
  - IT 자산 및 포트폴리오 관리.

### 4. 학습 요약 생성기
- IT 거버넌스 주제에 대한 간단한 요약 생성:
  ```python
  print(generate_summary("Risk Optimization"))
  # 출력: "위험 최적화는 조직이 IT 위험을 비즈니스 목표와 정렬시키는 과정입니다."
  ```

### 5. 시험 시뮬레이션
- CGEIT 시험 조건을 반영한 모의시험 제공.
- 성과 추적 및 피드백 기능.

### 6. CPE(Certified Professional Education) 추적기
- CGEIT 자격증 유지에 필요한 연간 CPE 포인트 활동을 기록.

---

## **설치 방법**
1. 저장소 복제:
   ```bash
   git clone https://github.com/your-repo/cgeit-helper.git
   cd cgeit-helper
   ```
2. 의존성 설치:
   ```bash
   pip install -r requirements.txt
   ```
3. 헬퍼 애플리케이션 실행:
   ```bash
   python app.py
   ```

---

## **사용법**
### 연습 문제 생성
```bash
python helper.py --generate-question 2
```

### 학습 요약 생성
```bash
python helper.py --summary "Risk Optimization"
```

### 시험 시뮬레이션 실행
```bash
python helper.py --simulate-exam
```

---

## **폴더 구조**
```
/
|-- helper.py               # 메인 스크립트
|-- resources/              # 학습 자료 및 연습 문제
|   |-- domain1_summary.txt
|   |-- domain2_summary.txt
|-- labs/                   # 실습 가이드
|-- mock_exams/             # 시험 시뮬레이션 파일
|-- requirements.txt        # 의존성 파일
```

---

## **기여 방법**
1. 저장소를 포크:
   ```bash
   git checkout -b feature-name
   ```
2. 새로운 브랜치 생성 후 수정:
   ```bash
   git commit -m "새로운 기능 추가"
   ```
3. 브랜치 푸시:
   ```bash
   git push origin feature-name
   ```
4. 풀 리퀘스트 열기.

---

## **라이선스**
이 프로젝트는 MIT 라이선스에 따라 배포됩니다.

---

## **문의**
질문이나 피드백은 **[your-email@example.com](mailto:your-email@example.com)**으로 연락주세요.


# 25-Winter-CS-Study-Session : Bit By Bit

Bit By Bit 은,
2025년 1월 13일부터 2월 28일까지 총 6주간 진행되는 컴퓨터 과학 기본 지식(CS) 스터디입니다.  
이번 스터디의 주요 목표는 [CS 지식의 정석 강의](https://www.inflearn.com/course/%EA%B0%9C%EB%B0%9C%EC%9E%90-%EB%A9%B4%EC%A0%91-cs-%ED%8A%B9%EA%B0%95) 를 기반으로 디자인패턴, 운영체제, 네트워크, 데이터베이스 등 CS 지식 전반을 습득하고 정리하는 것입니다.

---

## 📅 스터디 일정

- **진행 기간**: 2025년 1월 13일 ~ 2025년 2월 28일 (총 6주)
- **진행 시간**: 
  - 월, 수, 금 오후 1시 ~ 오후 3시 (2시간 30분)
  - 구정 등 기존 일정이 있는 관계로 일부 시간은 변경될 수 있음.
- **참여자**:
  <table style="border: 0.5px solid gray; width: 100%; border-collapse: collapse; text-align: center;">
  <tr>
    <td style="border: 0.5px solid gray;">
      <a href="https://github.com/donginLee">
        <img src="https://avatars.githubusercontent.com/donginLee" width="130px;" alt="">
        <br><b>이동인</b>
      </a>
    </td>
    <td style="border: 0.5px solid gray;">
      <a href="https://github.com/kimgs888">
        <img src="https://avatars.githubusercontent.com/kimgs888" width="130px;" alt="">
        <br><b>김광수</b>
      </a>
    </td>
        <td style="border: 0.5px solid gray;">
      <a href="https://github.com/snow9802">
        <img src="https://avatars.githubusercontent.com/snow9802" width="130px;" alt="">
        <br><b>박설진</b>
      </a>
    </td>
  </tr>
  <tr>
    <td colspan="3" style="border: 0.5px solid gray;"><b>Bit By Bit Members</b></td>
  </tr>
</table>


---

## 📝 스터디 진행 방식

### 1. 스터디 세션
- **10분 (오프닝)**:
  - 숙제 여부와 공부 내용 난이도, 컨디션에 대해 간단하게 스크럼을 진행한다.
    
- **1시간 30분 (공유 세션)**:
  - 세션 담당자가 준비한 발표 자료를 바탕으로 모든 스터디원이 주제에 대해 토의합니다.  
  - 다른 스터디 원이 준비한 추가 발표 자료를 기반으로 토의합니다.
    
- **20분 (마무리)** :
  - 공부 범위, 세션 담당자, 진행 여부 등 다음 스터디 세션에 대해 이야기합니다.   
  
### 2. 세션 준비
- **스터디장**:
  - record.txt, 디렉토리를 스터디 진행에 맞게 세팅합니다.
  - pull request를 수시로 확인합니다.
- **세션담당자**:  
  - 메인 발표 자료, 시험 문제를 만들어 스터디 세션 시작 1시간 전까지 레포지토리에 머지합니다.
    - 메인 발표 자료 가이드
      - 파일 이름 및 확장자
        - (폴더이름)_(담당자이름).pdf
        - ex. api_data_exchange_formats_이동인.pdf
      - 아래 내용을 포함해야합니다.
        - 발표자 이름, 발표 주제, 날짜를 포함한 표지
        - 목차
      - 방향성
        - **단순 지식 공유**가 아니라 **토의**를 유도할 수 있도록 발표를 준비합니다.
        - ex. 꼬리 질문으로 이루어진 슬라이드 등
  - 세션 전날 추가 발표를 원하는 스터디원이 있는지 카카오 채팅방에서 확인하여, 추가 발표를 포함 총 1시간 30분의 진행이 되도록 준비합니다.
- **스터디원 공통**:
  - 숙제로 지정된 모든 범위의 강의를 듣고 공부합니다.
  - 공부 내용을 바탕으로 공유하고 싶은 내용이 있다면 스터디 세션 전날 담당자에게 아래 두 내용을 공유합니다.
    - 발표 주제
    - 발표 소요 시간
  - 추가 발표 자료 가이드
     - 파일 이름 및 확장자
        - (폴더이름)_(발표자이름)_추가발표.pdf
        - ex. cloud_oop_이동인_추가발표.pdf
      - 발표 양식은 자율이나, 발표를 준비하게 된 동기를 발표 처음에 언급합니다.
        - ex. 이론의 실무 적용 예시 공유, 강의 내용 이해 잘되도록 설명 재구성 등

---


## 📂 디렉토리 구조

- 날짜 단위가 아닌, 내용 단위로 파일을 나눕니다.

```plaintext
📦 25-Winter-CS-Study/
├── README.md               # 최상단 설명 파일, 지금 이 파일
├── records.txt       # 스터디 기록
├── common # 섹션 1
│   ├── api_data exchange formats # 1일차 발표 내용
│   ...   
│   └── cloud_oop # 2일차 발표 내용
│       ├── cloud_oop_김동규.pdf
│       ├── cloud_oop_이동인_추가발표.pdf
│       └── test
│              ├── problems.txt
│              └── solutions.txt
...
├── operating_system # 섹션 4
...
└── data_structures
```

## 👨‍💻 commit message & pull request message
- session(숫자), (내용)
  - ex. "session1, 메인 발표 자료 업로드", "session2, 문제 수정" 
- cf. 세션 무관 공통 내용은 공통, (내용)
  - ex. "공통, 디렉토리 구조 수정"

# shuttleplay-fullstack

🎮 ShuttlePlay는 배드민턴 경기 매칭 및 MMR 기록 시스템입니다.  
이 레포지토리는 Frontend (React) + Backend (Spring Boot) 통합 프로젝트입니다.

## 🛠️ 프로젝트 실행 방법

1. 루트 디렉토리에서 `./gradlew bootRun` 실행  
2. 브라우저에서 [http://localhost:8080](http://localhost:8080) 접속 시 landing 페이지 실행됨
3. 프로젝트 종료 `ctrl + C`

## 🗃️ H2 Database 접속 방법

1. 브라우저에서 [http://localhost:8080/h2-console](http://localhost:8080/h2-console) 접속
2. 각 필드에 아래와 같이 입력 후 connect <br>
![image](https://github.com/user-attachments/assets/61d128f5-c65b-424a-9ef5-54ae97f502b7)

## 커밋 메세지 작성 규칙
작성 방법 : ```[카테고리]``` 작업 내용 요약

|카테고리	|설명|
|--|--|
|추가|	새로운 기능 추가
|수정|	기존 기능 수정, 버그 수정
|삭제|	불필요한 내용 삭제, 기능 삭제
|문서|	코드 편집X, 관련 문서 업로드 할 때
|테스트|	테스트 코드 작업 시
|환경|	빌드, 설정 파일 등 수정, DB 연결 작업

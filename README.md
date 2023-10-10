# Movie-Service-With-MSA-And-Kotlin
코틀린으로 작성한 MSA 영화 서비스 입니다.

# Movie & Review Project

## 1. Project Team Name
- **Movie & Review**

## 2. Team Composition
- 박세열 20172894 경영정보학부 4학년

## 3. Software System Target Purpose

### Vision
- 영화 정보와 리뷰 열람 시스템을 Micro Service Architecture를 이용해서 3 티어로 노드를 배치하여 서버 다운에 안정적인 시스템을 구축하려 한다.
- Monolithic Architecture의 경우 한 서버 노드 내에 기능들을 전부 넣기 때문에 노드가 죽으면 그 즉시 서비스 전체가 다운될 가능성이 크다. 반면 Micro Service Architecture는 기능마다 서버를 분리하여 티어 간 서버들은 서로 네트워크를 통해 json 형식으로 데이터를 주고 받아 서비스 자체의 안전성을 늘릴 수 있다.

### Scope
- 이번 학기 내의 목표는 DB부터 중계 서버까지 설계하는 것으로 생각한다. 테스트의 경우 단위테스트를 통해 클래스 로직을 확인하고 통합테스트로 전체 시퀀스를 테스트한 다음 실제 서버를 띄워 postman으로 json 파일 객체를 직접 검증할 예정이다. 추후 클라이언트 언어와 라이브러리, 프레임워크를 공부하여 서비스를 추가할 예정이다.


## 4.	Project System Overview and Characteristics

### Use Case Diagram
<img width="305" alt="image" src="https://github.com/SeYeol00/Movie-Service-With-MSA-And-Kotlin/assets/79959576/6108043b-8150-4dd5-9d2c-e0d9f72e0b5c">

### Architecture Diagram
![MSA draw (1)](https://github.com/SeYeol00/Movie-Service-With-MSA-And-Kotlin/assets/79959576/aa790645-badf-4f32-882f-23d025630f66)


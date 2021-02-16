# MediaLab
미디어 커뮤니케이션학부 랩실의 명부 관리 앱<br>
## 소개

### 개발 동기

미디어 커뮤니케이션 학부의 편집 랩실에 방문하였을 때, 명부 관리를 여전히 수기로 하고 있는 것을 발견하였습니다.<br><br>
매일 조교들이 명부를 타이핑하여 엑셀로 옮기는 것은 매우 비효율적이라고 판단하였고, 이러한 시간을 줄이기 위해 명부 관리 앱을 제작하게 되었습니다.<br>
  
### 앱 소개
  
- 미디어 커뮤니케이션학부 랩실의 명부 관리 앱<br>
  - 크게 일반 모드와 관리자 모드로 나눠져있고, 일반 모드에서는 **QR을 통한 입장, 회원 정보 등록 및 수정의 기능**을 구현하였습니다.<br>
  - 여기서 QR 코드는 따로 제작하는 것이 아닌, 기존의 모든 학생들이 간편하게 사용할 수 있도록 **모바일 학생증의 QR 코드를 파싱**하는 방식으로 진행되었습니다.<br>
  - 관리자 모드는 정해진 비밀번호를 통해 접근 가능하며, **명부 엑셀 파일 다운로드, 경고 기능, 현재 입실 중인 학생 조회** 등의 기능을 지원합니다.<br><br>
  
### MediaLab을 통한 기대점

  - 1. 수기로 작성된 명부를 엑셀로 옮기는 시간을 크게 단축시킬 수 있다.<br>
  - 2. 모바일 학생증을 활용하였기 때문에, 외부인의 입장을 방지할 수 있다. <br>
  - 3. 경고 기능을 통해, 모든 학생들이 랩실에서의 규칙을 잘 지킬 수 있게 된다.<br>
  - 4. 다른 학생들과 직접적인 접촉을 줄임으로써, 코로나19 바이러스 전파를 방지한다.<br>
  
## 사용 기술

### Client

- Android

### Database

- SQLite

### OpenSource

- QR스캔 : zxing
- 엑셀 생성 : POI

### Language

- Java

### Tools

- Android studio
- Window 10
- Git


## 시연 영상

> [영상 바로가기](https://www.youtube.com/watch?v=An2NhZydOII&feature=youtu.be)

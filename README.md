# smartfarm-esp32s3-v3-overview

ESP32-S3 Smart Farm Control Node 03의 정적 오버뷰 페이지입니다.

이 저장소는 GitHub Pages 같은 정적 호스팅에 바로 올릴 수 있도록 구성되어 있습니다.
공개 저장소에는 실제 SSID, 비밀번호, 토큰 같은 값 대신 "여기에 기입" 형태의 자리표시자를 사용합니다.

## 구성

- `index.html`: 메인 오버뷰 페이지
- `css/style.css`: 스타일
- `js/main.js`: 스크롤 reveal, 복사 버튼, 배경 효과
- `LICENSE`: MIT 라이선스

## 주요 내용

- ESP32-S3 N8R8 기반 제어 노드 소개
- Soft-AP 전용 HTTP 서버 정보
- `X-API-Token` 기반 인증 안내
- 모터, LED, LCD, 버튼 핀맵
- `GET /api/ping`, `GET /api/state`, `POST /api/command` API 요약
- 실제 접속 정보는 배포 환경에 맞게 별도로 설정

## 사용 방법

1. 저장소 루트의 `index.html`을 브라우저로 열면 바로 확인할 수 있습니다.
2. GitHub Pages를 쓰는 경우 저장소 루트를 배포 대상으로 지정하면 됩니다.
3. 별도 빌드나 외부 의존성은 없습니다.

## 라이선스

이 프로젝트는 [MIT License](./LICENSE)를 따릅니다.

### 안녕하세요

Flutter 앱과 Spring Boot 서버를 만들고, 스토어에 출시한 서비스를 직접 운영하고 있습니다.

## FEPLE

페스티벌 정보와 라인업을 보고 팬끼리 소통하는 커뮤니티 앱입니다.

[App Store](https://apps.apple.com/kr/app/feple/id6804336803) · [Google Play](https://play.google.com/store/apps/details?id=com.dobino.feple)

| 저장소 | 내용 |
|------|------|
| [feple-frontend](https://github.com/yangjaehoon/feple-frontend) | Flutter 앱 (Provider, GetIt, Dio, Firebase) |
| [feple-backend](https://github.com/yangjaehoon/feple-backend) | Spring Boot 서버와 관리자 웹 (MySQL, AWS EC2·S3, GitHub Actions) |

운영 중에 해결한 문제

- 온보딩 일괄 등록이 간헐적으로 실패하던 원인을 InnoDB 갭 락 데드락으로 찾아 수정
- 회원탈퇴가 성공 응답을 주고도 DB에 반영되지 않던 JPA 영속성 컨텍스트 문제 수정
- 앱 콜드스타트 때 자동 로그인보다 화면이 먼저 그려져 게스트로 진입하던 경합 수정

## 다른 프로젝트

| 저장소 | 내용 |
|------|------|
| [overlay-camera](https://github.com/yangjaehoon/overlay-camera) | 반투명 참조 사진에 맞춰 같은 구도로 촬영하는 Flutter 카메라 앱 |
| [giftifridge](https://github.com/yangjaehoon/giftifridge) | 기프티콘 유효기한을 관리하는 React Native(Expo) 앱 |

## 기술

`Java` `Spring Boot` `JPA` `MySQL` `Dart` `Flutter` `TypeScript` `React Native` `AWS` `Firebase` `GitHub Actions`

# M&S 개인정보 처리방침 / Privacy Policy

시행일: 2026년 11월 2일

M&S는 여러 화면과 스피커의 밝기·음량을 조절하는 Mac 앱입니다. 앱 자체는 사용자 개인정보를 수집하거나 개발자 서버로 전송하지 않습니다. 계정, 광고 SDK, 이용 분석 SDK를 사용하지 않습니다.

## 오디오

사용자가 동시 음량 제어를 시작하고 macOS 시스템 오디오 권한을 허용하면, 재생 중인 시스템 오디오를 메모리에서 처리해 선택한 출력 장치로 보냅니다. 오디오를 파일로 녹음하거나 개발자·제3자 서버로 전송하지 않습니다. 마이크 소리를 녹음하지 않습니다. 제어를 끄거나 앱을 종료하면 해당 처리를 중단합니다.

## 로컬 설정

음량, 감광값, 장치 식별자와 원래 화면 색상 테이블 등 기능에 필요한 설정은 앱의 로컬 컨테이너에 보관합니다. 화면 색상 테이블은 종료 시 원래 화면 상태를 복원하고 재실행 시 감광이 중첩되지 않게 하는 데 사용합니다. 이 정보는 개발자에게 전송되지 않습니다.

## 자동화

M&S의 로컬 제어 인터페이스는 같은 Mac의 같은 사용자 계정에서만 사용하는 Unix 소켓입니다. 인터넷에 원격 제어 포트를 열지 않습니다. 인터페이스는 장치·설정·신호 크기 정보를 반환하며 오디오 내용은 반환하지 않습니다.

## 구매와 지원

Mac App Store 구매는 Apple이 처리합니다. M&S는 결제 카드 정보를 받거나 보관하지 않습니다. 지원 요청을 위해 GitHub에 공개 이슈를 남기면 해당 내용은 GitHub의 정책에 따라 공개될 수 있습니다. 비밀번호, 녹음 파일, 결제 정보 등 민감한 내용은 공개 이슈에 올리지 마세요.

지원: https://github.com/Wayne-Kim/ms-control-support/issues

---

M&S does not collect personal data, run advertising or analytics SDKs, or transmit playback audio to a developer server. System playback is processed only in memory, with macOS permission, and sent to selected local outputs. Microphone audio is not recorded. Settings, device identifiers and original display transfer tables remain in the app's local container. The local Unix-socket automation interface returns settings and signal levels, not audio content, and does not expose an Internet control port. Apple processes Mac App Store purchases. Content voluntarily posted to public GitHub support issues is handled by GitHub and may be public.

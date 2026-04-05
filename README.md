# meta-rpi3

이 레이어는 Raspberry Pi 3 (64-bit)를 위한 **AI Agent Distro** 전용 래퍼(Wrapper) 및 설정 레이어입니다.

## 서지 사항 (Dependencies)
본 레이어는 다음 레이어들을 필요로 합니다.
- `poky/meta`
- `meta-raspberrypi`
- `meta-product`

## 주요 역할
- `raspberrypi3-64` 머신용 추가 설정 관리
- 하위 레이어 변수 덮어쓰기 및 제품 특화 설정 적용
- (옵션) 보드 특화 드라이버 및 앱 레시피 수용

## 상세 문서
상세한 시스템 빌드 및 포팅 가이드는 `manifest/docs/rpi3/` 디렉토리를 참조해 주세요.

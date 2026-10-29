# JHJ NetConnect — 배포판

**JHJ NetConnect** 는 원격 데스크톱 앞단의 자체 VPN 과 RDP 바로 열기 앱입니다. 원격으로 들어갈 PC(서버)와 붙을 PC(클라이언트)에 각각의 설치 파일을 관리자 권한으로 실행합니다.

## 받기

**JHJ 포털에서 받습니다** — https://jhj.wecco.co.kr/download/#netconnect

- JHJ 계정으로 로그인하면 바로 받습니다.
- 로그인하지 않으면 메일로 기한이 있는 다운로드 주소를 보내 드립니다.
- 메일로 받은 주소는 누르는 순간의 최신 판을 JHJ 서버에서 내려받는 기한부 주소입니다.

이미 설치한 앱은 스스로 업데이트합니다. 업데이트 파일은 JHJ 서버에서 받고, 받을 때마다 원본과 같은지(SHA-256) 확인합니다.

## 이 저장소

- 판마다 무엇이 추가 · 개선 · 수정됐는지 [Releases](https://github.com/HyungJIn-kr-97/JHJ_NETCONNECT_RELEASE/releases) 에 남깁니다.
- 소스 코드는 비공개 저장소에 있고 여기에는 올리지 않습니다.
- 배포 방식을 옮기는 동안에는 이미 설치된 옛 판의 업데이트를 위해 Releases 에 설치 파일도 함께 올라갑니다. 새로 받을 때는 위의 포털을 이용해 주십시오.

## 참고

- Windows 10/11 x64 전용입니다.
- 코드 서명이 없어 처음 실행할 때 SmartScreen 창이 뜰 수 있습니다. 「추가 정보」 → 「실행」을 누릅니다.

## 제3자 구성 요소

터널은 WireGuard LLC 의 공식 `wireguard.dll`(wireguard-nt)을 고치지 않고 그대로 씁니다 — 라이선스는 [wireguard-prebuilt-license.txt](wireguard-prebuilt-license.txt) 이고 설치 꾸러미에도 함께 들어 있습니다. JHJ NetConnect 는 WireGuard 프로젝트와 관계가 없습니다.
## 문의

서비스 · 광고 · 제휴 문의 jhj@wecco.co.kr

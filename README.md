# JHJ NetConnect — Releases

원격 데스크톱 앞단의 자체 VPN 과 RDP 바로 열기 앱 「JHJ NetConnect」의 **설치 파일만** 올리는 공개 저장소입니다. 소스는 비공개 저장소에 있습니다.

## 받기

[Releases](https://github.com/HyungJIn-kr-97/JHJ_NETCONNECT_RELEASE/releases/latest) 에서 받습니다.

| 파일 | 어디에 |
|---|---|
| `JHJ_NetConnect-Server-Setup.exe` | 원격으로 들어갈 PC(서버) — 관리자 권한으로 실행 |
| `JHJ_NetConnect-Client-Setup.exe` | 붙을 PC(기기) — 관리자 권한으로 실행 |

파일마다 `.sha256` 이 함께 있습니다. 서명이 없어 처음 실행할 때 SmartScreen 경고가 뜰 수 있습니다.

## 제3자 구성 요소

터널은 WireGuard LLC 의 공식 `wireguard.dll`(wireguard-nt)을 고치지 않고 그대로 씁니다 — 라이선스는 [wireguard-prebuilt-license.txt](wireguard-prebuilt-license.txt) 이고 설치 꾸러미에도 함께 들어 있습니다. JHJ NetConnect 는 WireGuard 프로젝트와 관계가 없습니다.

## 문의

서비스 · 광고 · 제휴 문의 jhj@wecco.co.kr
# 🏛️ HASTE Client Version Hub (헤이스트 단말기 버전 관리소)

HASTE 무인 스마트 카페 플랫폼의 클라이언트 배포 및 업데이트 저장소입니다.  
본 저장소는 **[핫패치]**, **[정식버전]**, **[설치]** 3대 영역으로 엄격히 분리 관리됩니다.

---

## 📌 3대 관리 영역 분류

| 영역 | 폴더 / 카테고리 | 배포 주기 및 대상 | 주요 내용 |
| :---: | :---: | :---: | :--- |
| **1. 핫패치** | [`hotpatch/`](./hotpatch/README.md) | 개발 / 테스트 채널 (운양역점/로컬)<br>• **최신 10개 롤링 유지** (`v3.3.1r141` ~ `v3.3.1r154`) | 경량 ASAR 핫패치 번들 |
| **2. 정식버전** | [`official/`](./official/README.md) | 상용 / 프로덕션 채널 (전국 전 가맹점)<br>• **100년 영구 보존 락** (`v3.3.1` 등) | 안정성 검증 완료 정식 ASAR |
| **3. 설치** | [`installer/`](./installer/README.md) | 신규 매장 세팅 및 단말기 인스톨러<br>• **단일 고정 파일** (`haste_client3-setup.exe`) | NSIS 단독 윈도우 인스톨러 |

---

## 🚀 다운로드 및 릴리즈 자산 바로가기
- **최신 핫패치 릴리즈**: [GitHub Releases (Latest 10 Hotpatches)](https://github.com/rst9374-tech/haste_client_version/releases)
- **정식 상용 버전**: [Release v3.3.1](https://github.com/rst9374-tech/haste_client_version/releases/tag/v3.3.1)
- **윈도우 설치 프로그램**: [haste_client3-setup.exe](https://github.com/rst9374-tech/haste_client_version/releases/download/v3.3.1/haste_client3-setup.exe)

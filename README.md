<img width="1102" height="602" alt="a" src="https://github.com/user-attachments/assets/c85c54b2-e9fa-4c06-a1c1-c1b9064d6383" />
# K-Fire Hydraulic Solver

**스프링클러 설비 수리계산 프로그램 | Sprinkler System Hydraulic Calculation Software**

[![Download](https://img.shields.io/badge/Download-v5.5.8-blue?style=for-the-badge)](https://github.com/yeoyong2002-coder/K-Fire-Hydraulic-Solver/releases/latest)
[![YouTube](https://img.shields.io/badge/YouTube-매뉴얼-red?style=for-the-badge)](https://www.youtube.com/watch?v=O6e3KqmXO40&list=PLJIPkrm6MfQk)
[![Blog](https://img.shields.io/badge/Blog-소개글-orange?style=for-the-badge)](https://firesafety.tistory.com/180)

---

## 다운로드 | Download

**[최신 버전 다운로드 (v5.5.8)](https://github.com/yeoyong2002-coder/K-Fire-Hydraulic-Solver/releases/latest)**

## 사용자 매뉴얼 | User Manual

프로그램 사용 방법은 유튜브 매뉴얼을 참고하세요.

- [K-Fire Hydraulic Solver 매뉴얼 (YouTube)](https://www.youtube.com/watch?v=O6e3KqmXO40&list=PLJIPkrm6MfQk)

## 기술문서 | Technical Reference

설치 파일과 함께 공개하는 기술문서 PDF입니다. 새 버전이 배포되어도 이 폴더의 파일은 유지·갱신됩니다.

| 문서 | 한국어 | English |
|------|--------|---------|
| 수리계산 | [PDF](docs/K-Fire_Hydraulic_Engineering_Overview_ko.pdf) | [PDF](docs/K-Fire_Hydraulic_Engineering_Overview_en.pdf) |
| 물도달시간 (WDT) | [PDF](docs/K-Fire_WDT_Engineering_Overview_ko.pdf) | [PDF](docs/K-Fire_WDT_Engineering_Overview_en.pdf) |
| PIPENET 비교검증보고서 | [PDF](docs/K-Fire_PIPENET_Verification_Report_ko.pdf) | [PDF](docs/K-Fire_PIPENET_Verification_Report_en.pdf) |

> 출력물 워터마크를 제외하면 **기능 제한 없이 무료**로 전체 기능을 사용할 수 있습니다.
>
> Free to use with full features (watermark on reports only for unregistered version).

---

## 소개 | About

배포판 출시 후 많은 업그레이드를 거쳐 정식 버전을 배포하게 되었습니다.
**V2.4.2 이전 버전에서 만든 파일은 호환되지 않거나 부속류 및 밸브 DB를 갱신해야 합니다.**

After numerous upgrades since the initial release, the official version is now available.
Files created in versions prior to V2.4.2 may not be compatible, or the fittings/valve DB must be updated.

---

## 다국어 지원 | Multilingual Support

한국어 · English · 日本語 · Español · 中文 · Tiếng Việt

---

## 버전별 주요 업그레이드 내역 | Version History

### V5.5.8 (최신 | Latest)

- 배관 우클릭으로 흐름 방향 뒤집기
- 헤드 다중선택 시 규격과 상태를 따로 변경
- 싱글인터록 물도달시간: 충수 중 헤드개방을 기본으로 끔
- 부동액 수리계산: 실행할 때마다 경계노드를 다시 지정
- 평평한 펌프 곡선이 계산을 막던 문제 수정

### V5.5

- 건식설비 물도달시간 (계산, 그래프, 2D 재생, 3D 시네마, mp4)
- 부동액 수리계산
- 배관 구경 자동 산정
- 45° 엘보 그리기

### V3.4

- 다중 배관 선택 후 배관 종류, 구경, C, 거칠기를 각각 독립적으로 변경 가능
- 배관 라이브러리 기능 향상 및 일부 버그 수정
- Multiple pipe selection: independently change pipe type, diameter, C-factor, roughness
- Pipe library enhancements and bug fixes

### V3.1

- 등가길이 계산 방식 변경: L/D 방식 → NFPA13 표준 등가길이
- NFPA13 호스스트림 기능 반영
- Changed equivalent length calculation from L/D method to NFPA13 standard
- NFPA13 hose stream function added

### V2.4.2

- 등가길이 환산계수 조도C 반영 및 구경D 미반영 부분 수정
- 정품 등록 시 HWID 키 추출 방식 개선

### V2.4.1

- 노즐 추가 시 색상 자동 반영
- 사소한 버그 수정

### V2.4.0

- 배관 중간 노드 삭제 기능
- 다양한 도구 추가: 스프링클러 작동시간, NFPA13 살수밀도, 노즐 방수량, 연기발생량 계산 등
- Various tools: sprinkler operation time, NFPA13 discharge density, nozzle flow, smoke generation

### V2.3

- 배관 생성 시 화살표 클릭으로 간단 생성
- 배관 분할 시 마우스로 분할 위치 설정
- 배관·노드 속성 Ctrl-C/V 복사·붙여넣기 단축키
- 배관 및 노드 다중 선택 후 일괄 수정·삭제
- 체크밸브 사용 기능 추가
- 다크모드 지원
- 보고서 출력 형식 및 내용 전면 개편
- 유량분포 그래프 보기 기능

---

## 정품 등록 | License

| 구분 | 내용 |
|------|------|
| 무료 버전 | 전체 기능 사용 가능, 보고서에 워터마크 표시 |
| 정품 등록 | 보고서 워터마크 제거 |
| 가격 | **90만원 / 년** |
| 무료 체험 | **2개월 무료 정품 등록 제공** |

2개월 무료 정품 등록: 프로그램 상단 메뉴 **도움말 → 정품등록** 클릭 후 '내 HWID'를 복사하여 아래로 문의해 주세요.

---

## 문의 | Contact

- ✉️ yeoyong2002@hanmail.net
- 📝 [블로그 소개글 | Blog](https://firesafety.tistory.com/180)

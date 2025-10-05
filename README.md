
# 🧪 MixCraft (Project MC)

> **"Combine, Create, and Craft!"**  
> 주어진 재료를 조합해 목표 아이템을 만들어내는 퍼즐 게임.  
> 간단한 조합에서 시작해 복잡한 창조로 확장되는 실험실-테마 캐주얼 게임입니다.

---

## 🧩 프로젝트 개요
| 항목 | 내용 |
|------|------|
| **프로젝트명** | MixCraft |
| **장르** | 스테이지형 조합 퍼즐 (Casual / Puzzle) |
| **개발 엔진** | Unity 2022 LTS (2D) |
| **대상 플랫폼** | Android (Portrait) |
| **개발 기간** | 2025.10 ~ 진행 중 |
| **개발자** | SuDev |

---

## 🧱 현재 진행상황 (Progress)
- ✅ **프로젝트 생성 및 환경설정**
  - Android Build Support 세팅 완료  
  - Portrait (세로) 모드 고정  
  - Package Name : `com.sudev.mixcraft`
- 🏗️ **UI 초기 레이아웃 구성 중**
  - Canvas / SafeArea / TopGoalBar / CombineBoard / InventoryDock 구조 설계  
  - 기본 스크롤 및 버튼 레이아웃 테스트 진행
- ⏳ **다음 단계 예정**
  - `CombineManager.cs` 구현 → 불 + 물 = 수증기 조합 테스트  
  - ScriptableObject 기반 조합 데이터 테이블 생성  
  - 임시 아이콘 셋 적용 및 UI 피드백 이펙트 추가

---

## 🧩 프로젝트 구조 (예정)

```
MixCraft/
 ┣ Scenes/
 ┃ ┗ MainScene.unity
 ┣ Scripts/
 ┃ ┣ CombineManager.cs
 ┃ ┗ SafeAreaFitter.cs
 ┣ Sprites/
 ┃ ┣ fire.png
 ┃ ┗ water.png
 ┗ Resources/
```

---

## 📱 빌드 정보
| 설정 | 값 |
|------|------|
| **Package Name** | `com.sudev.mixcraft` |
| **Minimum API Level** | Android 7.0 (API Level 24) |
| **Target API Level** | Automatic (Highest Installed) |
| **Orientation** | Portrait Only |

---

## 🚀 개발 로그 (Dev Log)
- **2025-10-05** : 프로젝트 세팅 완료, UI 기초 배치 작업 시작  
- **2025-10-06** : 조합 시스템 (CombineManager) 및 기본 아이콘 로직 적용 예정  

---

## 📚 향후 계획
- 스테이지별 목표 시스템 추가  
- 힌트 및 광고 보상 시스템 연동  
- 확장형 레시피 데이터 관리 (500+ 조합 목표)  
- 사운드 디자인 및 효과 음 추가  
- Google Play 출시 준비 (테스트 트랙)

---

## 🧑‍💻 License
이 프로젝트의 소스 코드는 MIT License 하에 공개됩니다.  
© 2025 SuDev (SuhnDev)

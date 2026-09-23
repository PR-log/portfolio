# 지호연 포트폴리오

한남대학교 빅데이터응용학과 3학년 지호연의 포트폴리오 사이트입니다.

🔗 **https://pr-log.github.io/portfolio/**

---

## 다룬 프로젝트

| 프로젝트 | 구분 | 저장소 |
|---|---|---|
| 운수종사자 사고 위험군 예측 (데이콘 437팀 중 21위) | 팀 4명 | [dacon-driver-risk-prediction](https://github.com/PR-log/dacon-driver-risk-prediction) |
| 차량 번호판 인식 · 출입 관리 시스템 | 개인 | [yolov8-license-plate](https://github.com/PR-log/yolov8-license-plate) |
| VisDrone 항공 영상 사람 탐지 | 개인 | [visdrone-object-detection](https://github.com/PR-log/visdrone-object-detection) |
| 한우 도체 등급 예측 | 팀 4명 | [data_mining_team_project](https://github.com/PR-log/data_mining_team_project) |
| NBA 우승 예측 모델 | 팀 5명 | [op_data](https://github.com/PR-log/op_data) |

---

## 구성

단일 HTML 파일에 결과 이미지 몇 장을 곁들인 정적 사이트입니다. 빌드 과정이 없고, 라이트/다크 테마와 반응형 레이아웃을 지원합니다.
글꼴(Pretendard)만 jsDelivr CDN에서 불러옵니다.

```
├── index.html    사이트 전체 (프로젝트 상세는 <dialog id="p-..."> 안에 있음)
├── assets/       프로젝트 레포에서 뽑은 결과 이미지 (WebP / PNG)
├── .nojekyll     GitHub Pages의 Jekyll 처리 비활성화
└── README.md
```

프로젝트 상세는 주소 뒤에 `#p-dacon`, `#p-visdrone`처럼 붙이면 바로 열립니다.
수정하려면 `index.html`을 편집하고 push하면 됩니다. 반영까지 보통 1분 이내 걸립니다.

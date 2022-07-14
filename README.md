![header](https://capsule-render.vercel.app/api?type=waving&color=703ee5&height=300&section=header&text=PocketTrainer&fontSize=90&animation=fadeIn&fontAlignY=38&desc=내%20주머니%20속의%20작은%20트레이너&descAlignY=51&fontColor=ffffff)

<h3 align="center">:weight_lifting:포켓트레이너:weight_lifting:</h3>
<p align="center"><img width="30%"  align="center" src="https://user-images.githubusercontent.com/37100067/178106686-9e2b93f7-78aa-48f0-b4a5-2b6b4ad9afcf.jpg"></p>

<h1><img src="https://user-images.githubusercontent.com/37100067/178103583-bb123eb6-a887-4b6f-95fc-45edaeaad4e3.png" width="5%" />포켓트레이너</h1>
> 인공지능 기반 자세추정을 통한 헬스트레이너 서비스 

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FPockeTrainer%2FPocket_Trainer&count_bg=%2379C83D&title_bg=%23555555&icon=insomnia.svg&icon_color=%232DCE89&title=%EB%B0%A9%EB%AC%B8&edge_flat=false)](https://hits.seeyoufarm.com)
[![GitHub forks](https://img.shields.io/github/forks/PockeTrainer/Pocket_Trainer)](https://github.com/PockeTrainer/Pocket_Trainer/network)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/PockeTrainer/Pocket_Trainer)

## :hammer_and_pick:(AI)기술태그:hammer_and_pick:

<img src="https://img.shields.io/badge/Tensorflow-FF6F00?style=for-the-badge&logo=Tensorflow&logoColor=white">  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white">



## 🧸 Pocket_Trainer_Model

운동별 모델과 학습 데이터를 담고있는 Repository입니다.

### 운동 종류
- 맨몸 운동 3
  - 푸시업(PushUp), 싯업(SitUp), 스쿼트(LightSquat)
- 부위별 운동 21
  - 가슴
    - 벤치프레스(BenchPress)
    - 인클라인 프레스(InclinePress)
    - 팩덱 플라이(PeckDeckFly)
  - 등
    - 랫 풀 다운(LatPullDown)
    - 바벨 로우(BarbellRow)
    - 시티드 로우(SeatedRow)
  - 어깨
    - 숄더 프레스(ShoulderPress)
    - 사이드 레터럴 레이즈(SideLateralRaise)
    - 리버스 팩덱 플라이(ReversePecDeckFly)
  - 삼두
    - 케이블 푸시 다운(CablePushDown)
    - 라잉 트라이셉스 익스텐션(LyingTricepsExtension)
    - 덤벨 킥백(DumbbellKickBack)
  - 이두
    - 이지바 컬(EasybarCurl)
    - 해머 컬(HammerCurl)
    - 암 컬(ArmCurl)
  - 복근
    - 크런치(Crunch)
    - 시티드 니 업(SeatedKneeUp)
    - 플랭크(Plank)
  - 하체
    - 스쿼트(Squat)
    - 레그 프레스(LegPress)
    - 레그 익스텐션(LegExtension)
### 트러블 슈팅
- ml5 - MoveNet 호환 문제
  - 자세 분류 모델 자체개발로 해결
- 학습된 모델이 희소하게 나오던 문제
  - BatchNormalization, Dropout 적용으로 해결

## :keyboard:참고한 OpenSource

1. <a href="https://www.tensorflow.org/hub/tutorials/movenet"><img src="https://img.shields.io/badge/movenet-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white">MoveNet - 관절 좌표 추출</a>
2. <a href="https://danfo.jsdata.org/"><img src="https://img.shields.io/badge/danfo-FFDF28?style=for-the-badge&logo=javascript&logoColor=white">Danfo.js - js의 Pandas</a>

## :roll_of_paper:추가판넬자료

https://drive.google.com/file/d/18B1whDcwz5KmK2FqZaZAn1tmMmeW0OHe/view?usp=sharing

## :trophy:최종결과물

<img src="https://user-images.githubusercontent.com/39055981/178031983-77292b00-2f99-41cb-b8b8-d01df8efda42.jpg" width="50%" >

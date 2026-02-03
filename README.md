# SKN24-Mini-EDA-1Team

## Team ⚡️날씨요정 찌릿찌릿⚡️

| <img width="140" height="140" src="./assets/EDA_Profile_Jaehoon.png"/> | <img width="140" height="140" src="./assets/EDA_Profile_unoo.png"/> | <img width="140" height="140" src="./assets/EDA_Profile_ara.png"/> | <img width="140" height="140" src="./assets/EDA_Profile_Lin.png"/> | <img width="140" height="140" src="./assets/EDA_Profile_Su.png"/> |
|:---:|:---:|:---:|:---:|:---:|
| **정재훈** | **김은우** | **고아라** | **나혜린** | **박수영** |
| 발표/강원도 | 경상도 | 충청도 | 전라도 | 수도권 |
| [![github - JeaHoon-J](https://img.shields.io/badge/JeaHoon--J-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JeaHoon-J) | [![github - whitehole17](https://img.shields.io/badge/whitehole17-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/whitehole17) | [![github - Akoh-0909](https://img.shields.io/badge/Akoh--0909-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Akoh-0909) | [![github - ](https://img.shields.io/badge/nngpfls-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nngpfls) | [![github - suyoung6279](https://img.shields.io/badge/suyoung6279-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://gith율

<table width="100%">
  <tr>
    <td width="50%">
      <img src="https://github.com/GitPractice-Hozero/practice_2/blob/kyu5KIm/%EC%84%9C%EC%9A%B8.png" style="width:100%; height:auto;" />
    </td>
    <td width="50%">
      <img src="https://github.com/GitPractice-Hozero/practice_2/blob/kyu5KIm/%EA%B2%BD%EC%9D%B8%EC%A7%80%EC%97%AD.png" style="width:100%; height:auto;" />
    </td>
  </tr>
</table>

- 서울 지역 : 일반 상업용이 많이 나타났다. 특히 강남, 서초 등과 같이 업무지구가 조성되어 있는 곳이 있어, 전력의 사용 비중이 높았음
- 경인 지역 : 인천과 경기도 5개 지역의 데이터를 이용했다. 인천과 경기는 주택과 산업이 같이 밀집되어 있다는 점, 또한 인천은 항구 도시이기에 산업용이 높게 나타나는 것을 볼 수 있었음

<table width="100%">
  <tr>
    <td width="50%">
      <img src="https://github.com/GitPractice-Hozero/practice_2/blob/kyu5KIm/%EA%B2%BD%EC%83%81%EB%B6%81%EB%8F%84.png" style="width:100%; height:auto;" />
    </td>
    <td width="50%">
      <img src="https://github.com/GitPractice-Hozero/practice_2/blob/kyu5KIm/%EA%B2%BD%EC%83%81%EB%82%A8%EB%8F%84.png" style="width:100%; height:auto;" />
    </td>
  </tr>
</table>

- 경상북도 지역 : 포항, 울산 등 대한민국 최대 공업단지가 조성되어 있어, 일반용이나 주택용이 상대적으로 다른 지역보다 적게 나타났고 산업용이 많이 나타났음
- 경상남도 지역 : 남해바다를 접하고 부산이라는 항구도시가 있어, 산업용이 높지만 크게 높은 비율을 보이진 않았음


<table width="100%">
  <tr>
    <td width="50%">
      <img src="https://github.com/GitPractice-Hozero/practice_2/blob/kyu5KIm/%EA%B0%95%EC%9B%90%EB%8F%84.png" style="width:100%; height:auto;" />
    </td>
    <td width="50%">
      <img src="https://github.com/GitPractice-Hozero/practice_2/blob/kyu5KIm/%EC%B6%A9%EC%B2%AD%EB%8F%84.png" style="width:100%; height:auto;" />
    </td>
  </tr>
</table>

- 강원도 지역 : 산업용이 높지만, 주택과 일반용도 완만한 비율을 보였고, 다른 지역에 비해 심야가 높은 것을 볼 수 있었음
- 충청도 지역 : 산업용이 높지만, 다른 지역에 비해 산업용 전력사용량의 평균이 완만하였음
---------------------
## 날씨 데이터 컬럼 설명

| 컬럼명 | 설명 |
|--------|------|
| 평균기온(°C) | 해당 지점의 하루 평균 기온 |
| 평균현지기압(hPa) | 해당 지점의 하루 평균 기압(지점 기준) |
| 평균해면기압(hPa) | 해당 지점의 하루 평균 해면 기준 기압 |
| 평균수증기압(hPa) | 공기 중 수증기가 주는 압력 |
| 평균상대습도(%) | 공기 중 수분 함량 비율 |
| 월합강수량(00~24h만)(mm) | 하루 합계 강수량을 월 단위로 합산한 값 |
| 평균풍속(m/s) | 하루 평균 풍속 |
| 일조율(%) | 하루 중 햇빛이 비친 시간 비율 |
| 최심적설(cm) | 하루 중 가장 깊은 적설(눈 깊이) |
| 평균지면온도(°C) | 하루 평균 지면 온도 |
| CDD | 냉방도일 – 냉방 필요 정도를 나타내는 지표 |
| HDD | 난방도일 – 난방 필요 정도를 나타내는 지표 |

<small>CDD (Cooling Degree Day, 냉방도일) = $\max(T_\text{평균} - 24, 0)$</small>  
<small>HDD (Heating Degree Day, 난방도일) = $\max(18 - T_\text{평균}, 0)$</small>


## 전력사용량 데이터 컬럼 설명

| 컬럼명 | 설명 |
|--------|------|
| 연도 | 데이터가 기록된 연도 |
| 시도 | 시·도 이름 |
| 시군구 | 시·군·구 이름 |
| 계약종별 | 전력 사용 형태(가로등, 교육용, 농사용, 산업용, 심야, 일반용, 주택용, 합계) |


## 계약종별 항목 설명

| 계약종별 | 설명 |
|----------|------|
| 가로등 | 가로등, 도로 조명용 전력 |
| 교육용 | 학교, 학원 등 교육기관에서 사용하는 전력 |
| 농사용 | 농업용 전력, 예: 온실, 급수 펌프 등 |
| 산업용 | 공장, 제조업 등 산업체에서 사용하는 전력 |
| 심야 | 심야 시간대(보통 23:00~07:00)에 사용하는 전력 |
| 일반용 | 상점, 사무실 등 일반 상업용 전력 |
| 주택용 | 가정에서 사용하는 전력 |
| 합계 | 위 모든 계약종별을 합산한 총 전력 사용량 |





















---------------------
## 4. 한계점:
  - 데이터 해상도: 시·도 단위 공공 데이터를 활용하여 개별 가구·건물의 세밀한 소비 행태 분석에는 제한이 있음.
  - 변수의 한정성: 전기요금, 경제지표 등 비기상 요인을 제외하고 기상 변수(기온·습도 등)에 집중함
  - 시간적 범위: 단기 데이터 분석으로, 장기적 기후변화 추세로 일반화하기에는 한계가 있음.
  - 분석의 지향점: 신규 알고리즘 개발보다 EDA와 기초 통계 모델을 통한 직관적 패턴 탐색 및 검증에 주력함.
  

















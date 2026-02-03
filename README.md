
## 지역별 전력사용량과 기상요인 상관관계 분석
<table width="100%">
  <tr>
    <td width="50%">
      <img src="https://github.com/user-attachments/assets/51250008-6046-495e-8344-ba1a2cf4f532" style="width:100%; height:auto;" />
    </td>
    <td width="50%">
      <img src="https://github.com/user-attachments/assets/eb4307e4-e9c2-4f5e-bb71-3ad8d227b567" style="width:100%; height:auto;" />
    </td>
  </tr>
</table>

</table>

- 서울: 냉방도일과 수증기기압이 각각 0.61, 0.38로 뚜렷한 양적 상관관계를 보임. 일조율은 -0.32로 뚜렷한 음의 상관관계를 보임.

- 경인: 냉방도일이 0.31로 뚜렷한 양적 상관관계를 보임. 나머지 기상요인들은 약한 상관관계를 보임.


<table width="100%">
  <tr>
    <td width="50%">
      <img src="https://github.com/user-attachments/assets/38461cd2-fa18-454a-b5df-37cc4e80cf4b" style="width:100%; height:auto;" />
    </td>
    <td width="50%">
      <img src="https://github.com/user-attachments/assets/2b3ed0a1-85e3-464e-aea1-972954760a0e" style="width:100%; height:auto;" />
    </td>
  </tr>
</table>

</table>

- 강원도: 평균풍속이 0.28로 약한 상관관계를 보임. 나머지 기상요인과 전력 사용량은 거의 상관관계가 없음.

- 충청도: 평균풍속이 0.34로 뚜렷한 양적 상관관계를 보임. 평균풍속을 제외한 나머지 기상요인과 전력 사용량은 거의 상관관계가 없음.




<table width="100%">
  <tr>
    <td width="50%">
      <img src="https://github.com/user-attachments/assets/725758ed-3d1e-49d8-a7e3-6466e7aead07" style="width:100%; height:auto;" />
    </td>
    <td width="50%">
      <img src="https://github.com/user-attachments/assets/5690c3ed-7060-4447-bc43-23d8c90a604e" style="width:100%; height:auto;" />
    </td>
  </tr>
</table>




</table>

- 경상도: 평균풍속과 평균현지기압이 각각 0.22, 0.21로 약한 양적 상관관계를 보임. 나머지 기상요인과 전력 사용량은 거의 상관관계가 없음.
  
- 전라도: 냉방도일이 0.12로 약한 양적 상관관계를 보임. 나머지 기상요인과 전력 사용량은 거의 상관관계가 없음.


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








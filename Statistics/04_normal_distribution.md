# 정규분포로의 근사
## 단위변환
* 표준화 : 평균을 빼고 표준편차로 나누는 변환
* 표준단위 : 표준화된 값
* 표준화된 변수는 평균이 0, 표준편차 1
* 값에 더하기 -> 평균 값만큼 덧셈, 표준편차는 변하지 않음
* 값에 나누기 -> 평균은 값만금 곱셈, 표준편차도 값만큼 곱셈
![정규분포](./정규분포.jpg)
* 측정 단위가 바뀌어도 **표준 단위는 변하지 않는다** -> 즉, 측정 단위가 다른 자료들을 비교할 때 각 자료를 표준화하면 편리하다
## 정규분포곡선
* 정규분포곡선은 실제 자료의 분포가 아니라, 실제 자료의 분포를 근사gg시켜줄 하나의 수학적 모형이다 -> 즉, 개념상 **모집단**에 해당한다
* 정규분포의 평균 μ은 모평균이고,  표준편차σ는 모표준편차이다
* 실제 주어진 자료의 히스토그램의 평균과 표준편차는 **표본평균**과 **표본표준편차**이다
* 평균이 0, 표준편차가 1인 정규분포는 **표준정규분포**라고 한다
    > 68-95-99.7의 법칙   
    > *  -1~1의 구간의 넓이는 약 68%
    > * -2~2의 구간의 넓이는 약 95%
    > * -3~3의 구간의 넓이는 약 99.7%   
   
* 정규 분포의 특징
    1. 좌우 대칭
    2. 종모양
    3. 봉우리 하나

## 백분위수
* 정규분포 곡선을 따르는 자료는 평균, 표준편차로 자료 확인 가능하지만 **정규분포 곡선을 따르지 않는 자료는 평균, 표준편차만으로는 충분하지 않다** 
* 이 경우 **백분위수**를 활용한다
* 백분위수 중 25%, 50%, 75% 지점을 제 1사분위수, 제 2사분위수, 제3사분위수라 한다.
* 50% 지점은 제 2사분위수이며, **중앙값**이다
* **사분위수 범위**는 ```제 3사분위수-제1사분위수```이다
* 자료가 분포 정도를 측정할 때 표준편차는 극단적인 값의 영향을 크게 받으므로, 극단적인 값이 존재하는 경우 표준편차를 대신하여 **사분위수 범위**를 활용하면 좋다.
* 보통 자료를 요약할 때 **제 1사분위수, 제 2사분위수, 제 3사분위수, 최대값, 최소값** 다섯 개를 사용하며 자료의 **다섯 숫자 요약**이라고도 한다
* 이는 Box plot으로 확인할 수 있다
* 최소값, 최대값 대신, 제 10분백분위수, 제 90백분위수나 제 5백분위수, 제 95백분위수, 극단치가 궁금한 경우 제 1백분위수, 제 99백분위수 등으로 변경하여 사용하기도 한다
 
    > * 예제) 통계학 수강생들의 중간고사 성적인 50점 만점에 평균이 27.93이고 표준편차가 8.52였다. 점수분포는 정규분포에 가까웠다면 상위 5%에 해당하는 학생의 점수는?   
    > * 해설) 45%의 구간에서 z의 지점 (정규분포표에서 확인)은 1.65이므로 8.52*1.65 = 14.06이다
    즉 5%에 해당하는 점수는 27.93 + 14.06 = 41.99이다

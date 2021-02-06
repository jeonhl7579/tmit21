# An E-day project

## project by 최민식, 김보금, 전세현, 김나연

## An introduction

  DSC Korea Solution Challenge Hackathon 2021에서 ‘가장 중요한 팀’의 주제는 데이터 시각화, 딥러닝 모델링, 웹 구현을 바탕으로 한 솔루션 첼린지 13번  **기후 변화 대응(climate action)** 이다. 기후변화는 우리에게 중요한 문제이지만 추상적이고 막연하게 여기어진다는 점에 착안해 지금 당장에 초점을 두어 현재 기온과 비교한 구체적인 수치를 제시하고자 했다. 그리고 현시대에 가장 큰 문제가 되고 있는 코로나에 대해 눈에 보이지 않는 바이러스를 시각적 차트를 통해 가시적으로 설명하여 일반대중들에게 이해하기 쉽게 할 수 있는 것처럼 지구온난화로 인한 기온상승, 온실가스증가에 대한 데이터를 시각화해 사람들의 직관적인 이해를 도우려고 했다. 마지막으로 과거 데이터를 기반으로 한 예측을 제시하면 환경을 보호하는 것에 설득력을 줄 수 있을 것이라고 생각했다.

## Development methods

 E-day 프로젝트는 HTML, CSS, JS, api, tensorflow를 바탕으로 구현한 웹페이지를 통해 기후변화 대응에 대해 우리 팀의 시각으로 접근한 프로젝트이다. 우선 데이터 시각화를 위한 자바스크립트 라이브러리 d3.js를 이용해 과거 데이터를 동적이고 인터렉티브한 라인 차트로 만들었다. 또한 날씨 api를 사용해 현재 위치와 기온을 받아 기상청의 과거 1973년 월 평균 기온과 실시간으로 비교하여 지구온난화로 인한 기온 상승을 보다 직관적으로 보여주고자 하였다. 마지막으로 머신러닝 텐서플로우를 이용해 기온 예측 모델를 만들었다. 일정한 시간 간격으로 배치된 시계열 데이터의 예측 및 분석에 많이 사용되는 LSTM 알고리즘을 이용해 2021년 이후의 월 평균 기온을 예측하고자 하였다.

## A possibility of expansion

 E-day 프로젝트를 통해 만들어진 웹사이트는 국내 기상청의 데이터를 이용해 지금까지 지구온난화로 인한 평균 기온 변화와 온실가스의 증가율을 파악하고 이에 대한 경각심이나 대비 방안이 없을 경우 미래에는 기온이 어떻게 바뀔지 예측해볼 수 있다. 기온 값이 추가되거나 기온 외의 다른 데이터가 있더라도 초기 데이터 파일만 바꿔주면 되기 때문에 예측 모델의 재사용성이 용이하고, api를 통해 실시간 기온과 과거의 평균 기온을 비교하면서 누구나 쉽게 차이를 파악할 수 있습니다. 국내뿐만 아니라 해외의 데이터도 활용한다면 풍부한 데이터를 바탕으로 보다 넓은 지역의 사람들에게 지구온난화로 인한 환경 변화와 그로 인해 우리가 직면할 미래 기후 변화에 대한 대응의 필요성을 시각 자료를 통해 쉽고 효과적으로 제시할 수 있을 것이다.

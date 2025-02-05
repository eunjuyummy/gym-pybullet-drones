# 동아대학교 산학협력 프로젝트: 강화학습기반 해상환경 함정간 무인드론 자율비행 기술 개발


## 제한 시간을 갖는 작업 환경에서 강화학습 기반 드론의 자율비행 비교 연구 (*Accept)

 본 논문은 혈액 운송과 같은 제한 시간을 갖는 작업 환경에서 드론의 자율비행에 관한 것으로, 기존 Proportional-Integral-Derivative (PID) 방식에 비해 강화학습(Reinforcement Learning; RL)을 이용하는 경우의 성능 향상을 비교 실험을 통해서 제시한다. 오픈소스 드론 시뮬레이터를 통해 PID 기반 드론의 자율비행보다 RL 기반 드론의 평균 비행시간이 약 2.8초 빠른 것을 확인할 수 있었다. 이러한 결과를 바탕으로 짧은 시간 내에 목표 달성이 필요로 하는 작업 환경에서 강화학습이 효과적으로 사용될 수 있을 것으로 기대한다.

저자: 권은주,정희철,김현석*
 저자 소속: 동아대학교 
 키워드: 강화학습, 드론, PID 한국통신학회
 
---
## gym-pybullet-drones 
<img src="files/readme_images/RL.gif" alt="control info" width="450">

## Installation

```sh
git clone https://github.com/eunjuyummy/gym-pybullet-drones.git
sudo apt install ffmpeg

cd gym-pybullet-drones/
sudo pip install -e.

cd gym_pybullet_drones/examples/

python main.py
```
## PID vs. RL
PID와 RL 기반 비행을 동시에 비교하기 위한 통합 환경 구축
<br/>- BothCtrlAviary.py
<br/>- main.py

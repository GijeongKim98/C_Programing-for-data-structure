# 자료구조
## 2021년 1학기 수업
자료구조 수업 과제 #1
이번 과제는 atm기가 3대가 있고 1분마다 사람이 들어온다고 가정한다. 1분 마다 들어 오는 사람은 id를 현재 분이라 하고 10시던 11시던 같은 분이라면 똑같은 id를 배정한다. 또한 atm기를 이용할 시간에 대해 배정받고 1/10 확률로 vip라면 제일 그 atm기의 줄의 처음에 선다. 이렇게 10시 부터 11시 59 분 까지 사람이 들어오고 atm기의 줄이 가장 짧은 곳으로 간다. 여기서 문제는 0분 부터 매 10분이 지날 때 마다 atm기 3대에서 줄을 선 사람중 id가 소수인 사람이 줄에서 이탈한다. 또한 atm기를 각각의 queue로 구현한다.  
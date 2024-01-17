# k8s_project

## 프로젝트 설명
- 쿠베네티스를 활용한 공항데이터 mlops 파이프라인 구현
- 항공 정보를 입력하면 지연시간을 예측하는 ML서비스를 제공하는 프로젝트
- 기존 Docker 환경에서 쿠버네티스를 사용하는 환경으로 업그레이드 진행
## 프로젝트 기간
2023.09.26 - 2023.11.03 (4주/5인)

## 역할 
- Flask deployment, service, ingress 작성 [[link]](https://github.com/yeardream-de-project-team4/k8s_project/wiki/flask-server)
- client와 웹 서버, 웹서버와 db 연동 담당 
- 모니터링을 위한 Grafana 연동 [[link]](https://github.com/yeardream-de-project-team4/k8s_project/wiki/prometheus-&-grafana-&-loki)

## 아키텍처
![Untitled (1)](https://github.com/kclown0/k8s_project/assets/104144701/77f73384-02ee-4cac-a561-4ef1aa60891a)

![Untitled (2)](https://github.com/kclown0/k8s_project/assets/104144701/cba610be-85df-48d3-bdb8-ec0004db7e9e)

### 기술 스택
<div style="text-align: left;">
   <img src="https://img.shields.io/badge/EC2-007396?style=for-the-badge&logo=S3&logoColor=white">
  <img src="https://img.shields.io/badge/Kubernetes-007396?style=for-the-badge&logo=S3&logoColor=white"> 
  <img src="https://img.shields.io/badge/minio-3776AB?style=for-the-badge&logo=EMR&logoColor=white">
  <img src="https://img.shields.io/badge/kafka-007395?style=for-the-badge&logo=Athena&logoColor=white">
  <br> <img src="https://img.shields.io/badge/spark-007396?style=for-the-badge&logo=S3&logoColor=white">
   <img src="https://img.shields.io/badge/Airflow-007396?style=for-the-badge&logo=S3&logoColor=white">
  <br> 
  <img src="https://img.shields.io/badge/Prometheus-007396?style=for-the-badge&logo=S3&logoColor=white">
  <img src="https://img.shields.io/badge/Grafana-007396?style=for-the-badge&logo=S3&logoColor=white">
  </div>

## 프로젝트 상세 설명
[[project-wiki-link]](https://github.com/yeardream-de-project-team4/k8s_project/wiki/%EB%B0%9C%ED%91%9C%EC%9E%90%EB%A3%8C-%EC%A0%95%EB%A6%AC)

## 프로젝트 회고
- EC2에 직접 쿠버네티스 환경을 설치하여 진행해 쿠버네티스 전반에 대한 이해를 할 수 있었 던 프로젝트입니다. <br> 다음에는 AWS EKS 서비스를 활용한 프로젝트를 진행하고 싶습니다. 
  

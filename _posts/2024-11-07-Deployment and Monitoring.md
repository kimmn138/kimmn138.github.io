---
layout: post
title: Deployment and Monitoring
subtitle: Deployment and Monitoring
categories: "SE_Study"
tags: [Server]
---

# Deployment and Monitoring

작성일시: 2024년 11월 7일 오후 8:10
자료: https://docs.delinea.com/online-help/server-suite/install/deployment/overview/index.htm, https://www.splunk.com/en_us/blog/learn/server-monitoring.html
유형: 서버 스터디

### Deployment and Monitoring

- Deployment
    - 배포의 첫 번째 단계에서는 조직의 요구 사항과 목표에 대한 세부 정보를 수집하고 분석해야 함
    - 분석한 후에는 사용할  Active Directory 조직 단위와 그룹을 준비해야 함
        - Active Directory란 사용자, 그룹, 컴퓨터, 그리고 다른 조직 단위 같은 AD 객체들을 논리적으로 그룹화하여 관리하는 컨테이너
    - Active Directory를 준비하고, 최소한 한 대의 컴퓨터에 관리 콘솔을 설치하고, 최소한 한 개의 영역을 만들면 관리할 컴퓨터에 배포할 준비가 된 것임
    - 대상 컴퓨터에 에이전트를 배포한 후에는 추가 컴퓨터에 배포하기 전에 작업을 테스트하고 확인해야 함
    - 대상 컴퓨터에서 배포가 성공적으로 이루어졌는지 확인한 후에는 진행 중인 작업을 세부화, 관리 및 개선할 수 있는 여러 가지 방법이 있음

[Deployment Process Overview | Delinea](https://docs.delinea.com/online-help/server-suite/install/deployment/overview/index.htm)

- Monitoring
    - 서버 모니터링은 물리적이든 가상이든 서버의 활동에 대한 가시성을 확보하는 프로세스
    - 시스템을 관찰하고 IT 관리 부서에 해당 시스템의 운영에 대한 여러 가지 주요 지표를 제공하도록 설계되었음
    - 서버의 성능과 가동 시간을 모니터링하는 것은 IT 환경의 건강을 유지하는 데 필수적이기 때문에 중요함
    - 시스템 유형
        - 온프레미스/전통적인 소프트웨어 기반 시스템
        - 클라우드/SaaS 시스템
        - 모바일 시스템

[What is Server Monitoring? A Beginner's Guide | Splunk](https://www.splunk.com/en_us/blog/learn/server-monitoring.html)
# CamFree: 카메라 없는 홈캠

## 프로젝트 개요

**CamFree**는 카메라 대신 **Wi-Fi CSI(Channel State Information) 기반 출입 감지**을 활용해 사용자의 입출입을 실시간으로 확인하는 모니터링 시스템입니다.

본 프로젝트는 기존 홈캠의 사생활 침해 문제를 해결하며 기존 Wifi 인프라를 활용하므로 저비용으로 유사한 기능을 구현할 수 있는 효율성을 제공합니다.

## 주요 기능

- **출입 감지 (Intrusion Detection)** : Wi-Fi CSI를 활용한 실시간 입출입 감지
- **실시간 알림 (Real-time Alert)** : 이상 출입 감지 시 모바일/웹 알림 전송
- **데이터 시각화 (Data Visualization)** : CSI 데이터를 분석하고 대시보드로 시각화

## 기술 스택

- **Hardware** : Raspberry Pi 4, Wi-Fi AP (CSI 수집용)
- **Backend** : Python, CSI data process library
- **Frontend** : React.js
- **Database** : MySQL
- **Notification** : Telegram Bot, Firebase Cloud Messaging(Firebase FCM)
- **Visualization** : Chart.js, Recharts

## 프로젝트 멤버

김채영, 박서연, 이소현

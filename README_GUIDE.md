# Bong_project 운영 가이드

## 목적
이 저장소는 서버 / 공통 인프라 / 전 프로젝트 공용 자산을 관리하는 GitHub 기준 저장소입니다.

## 역할
- macOS 서버 운영 스크립트 관리
- launchd / plist 관리
- 백업 / 모니터 / 알림 / healthcheck 관리
- Jupyter / Docker / Colima 운영 자산 관리

## GitHub / Notion / 서버 역할
- GitHub: 실행 기준 원문
- Notion: 구조 / 설명 / 기록 / 계획
- 서버: 실제 실행 반영 위치

## 포함 대상
- system_backup_run.sh
- check_bongssd.sh
- system_alert_send.sh
- server-bong-healthcheck.sh
- weekly_success_report.sh
- com.magi.*.plist

## 제외 대상
- PoC notebook
- 프롬프트 실험
- 테스트용 코드

## 원칙
- 운영 코드 변경은 GitHub 기준으로 관리
- 서버는 항상 GitHub와 동기 상태 유지
- 민감정보는 커밋 금지

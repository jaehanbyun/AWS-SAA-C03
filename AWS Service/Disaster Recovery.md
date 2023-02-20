### Disaster: 비즈니스에 심각한 부정적인 영향을 주는 사건
  * Natural Disasters - 지진, 홍수 등
  * Technical Failures - 전원 실패, 네트워크 연결 문제 등
  * Human actions - 부주의한 조작/설정, 허용하지 않은 사람의 액세스/변경 등
  
### Disaster Recovery
  * **전체** 워크로드를 별도의 장소에 복사
  * 지진, 홍수 등의 재난 이벤트
  * 목표는 끊기지 않는 비즈니스, 비즈니스의 연속성

### High Availability
  * **일부** 워크로드(워크로드 구성요소)의 서비스를 지속하는 것에 중심
  * 컴포넌트 실패, 네트워크 문제, 소프트웨어 문제, 시스템 과부하 등의 재해 복구보다 구체적이고 작은 범위
  * 고 가용성의 목표는 시스템의 기능 수행 시간의 최대화

### RPO(Recovery Point Objective): 복구 시점 목표
### RTO(Recovery Time Objective): 복구 시간 목표

### Disaster Recovery Strategies
  * Backup & Restore - Hours/High
  * Pilot Light - 10s of minutes
  * Warm standby - Minutes
  * Multi-site - Real-time/Low

### Database Migration Service(DMS)
  * 데이터베이스를 마이그레이션 하는 서비스 DB->DB
  * 온프레미스->AWS or AWS내->AWS내 마이그레이션 가능

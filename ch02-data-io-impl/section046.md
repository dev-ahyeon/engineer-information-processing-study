# Section 046 | 분산 데이터베이스 설계 (C)

### 1. 데이터베이스 용량 설계

### 2. 분산 데이터베이스 설계
- 정의 : 논리적으로는 하나의 시스템에 속하지만 물리적으로는 네트워크를 통해 연결된 여러 개의 사이트(Site)에 분산된 데이터베이스

### 3. 분산 데이터베이스의 목표
- 위치 투명성(Location Transparency)
- 중복 투명성(Replication Transparency)
- 병행 투명성(Concurrency Transparency)
- 장애 투명성(Failure Transparency)

### 4. 분산 설계 방법
- 테이블 위치 분산
- 분할(Fragmentation)
- 할당(Allocation)
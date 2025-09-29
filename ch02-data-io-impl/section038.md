# Section 038 | 이상 / 함수적 종속 (A)

### 1. 이상(Anomaly)
- 정의 : 테이블에서 데이터의 중복이 발생하고, 이 중복(Redundancy)으로 문제가 발생하는 형상
- 종류
  - 삽입 이상(Insertion Anomaly) : 테이블에 대이터를 삽입할 때 의도와는 상관 없이 원하지 않은 값들로 인해 삽입할 수 없게 되는 현상
  - 삭제 이상(Deletion Anomaly) : 테이블에서 한 튜플의 삭제할 때 의도와는 상관없는 값들도 함께 삭제되는, 즉 연쇄 삭제가 발생하는 현상
  - 갱신 이상(Update Anomaly) : 테이블에서 튜플에 있는 속성 값을 갱신할 떄 일부 튜플의 정보만 갱신되어 정보에 불일치성(Inconsistency)이 생기는 현상

### 2. 함수적 종속(Functional Dependency)
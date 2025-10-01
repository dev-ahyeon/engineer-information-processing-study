# Section 048 | 데이터베이스 보안 (A)

### 1.데이터베이스 보안

### 2. 암호화(Encryption)
- 암호화(Encryption) 과정 : 평문 → 암호문
- 복호화(Decryption) 과정 : 암호문 → 평문
- 암호화 기법
  - 개인키 암호 방식(Private Key Encryption)
  - 공개키 암호 방식(Public Key Encryption)

### 3. 접근통제
- 접근통제 3요소
  - 접근통제 정책
  - 접근통제 메커니즘
  - 접근통제 보안모델
- 접근통제 기술
  - 임의 접근통제(DAC, Discretionary Access Control)
  - 강제 접근통제(MAC, Mandatory Access Control)
  - 역할기반 접근통제(RBAC, Role Based Access Control)

### 4. 접근통제 정책
- 접근통제 정책의 종류
  - 신분 기반 정책
    - IBP(Individual-Based Policy) : 최소 권한 정책, 단일 주체에게 하나의 객체에 대한 허가를 부여
    - GBP(Group-Based Policy) : 복수 주체에 하나의 객체에 대한 허가를 부여
  - 규칙 기반 정책
    - MLP(Multi-Level Policy) : 사용자나 객체별로 지정된 기밀 분류에 따른 정책
    - CBP(Compartment-Based Policy) : 집단별로 지정된 기밀 허가에 따른 정책
  - 역할 기발 정책
    - GBP의 변형된 정책

### 5. 접근통제 매커니즘
- 종류 : 접근통제 목록, 능력 리스트, 보안 등급, 패스워드, 암호화 등

### 6. 접근 통제 보안 모델
- 종류
  - 기밀성 모델
  - 무결성 모델
  - 접근통제 모델

### 7. 접근통제 조건
- 값 종속 통제(Value-Dependent Control)
- 다중 사용자 통제(Multi-User Control)
- 컨텍스트 기반 통제(Context-Based Control)

### 8. 감사 추적
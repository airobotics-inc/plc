# PLC 프로젝트

이 프로젝트는 PLC(Programmable Logic Controller) 관련 파일들을 포함하고 있습니다.

## 프로젝트 구조

```
plc/
├── mx5a/                    # MX5A PLC 관련 파일
│   ├── 초기화.state         # 초기화 상태 파일
│   └── 초기화.xgwx         # 초기화 설정 파일
├── on/                      # ON PLC 관련 파일
│   ├── 333.state           # 333 상태 파일
│   └── 333.xgwx           # 333 설정 파일
└── README.md               # 프로젝트 설명서
```

## 파일 설명

### MX5A PLC

- **초기화.state**: PLC 초기화 상태를 정의하는 파일
- **초기화.xgwx**: PLC 초기화 설정을 포함하는 파일

### ON PLC

- **333.state**: PLC 333 상태를 정의하는 파일
- **333.xgwx**: PLC 333 설정을 포함하는 파일

## 사용법

1. 각 PLC 폴더의 `.state` 파일을 확인하여 현재 상태를 파악
2. `.xgwx` 파일을 통해 PLC 설정을 조정
3. 필요에 따라 상태 및 설정 파일을 수정

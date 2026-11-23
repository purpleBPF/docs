# PurpleBPF Docs

eBPF 기반 컨테이너 런타임 위협 탐지 · 커버리지 루프 프로젝트 **PurpleBPF**의 설계 문서.
코드: [purpleBPF/purplebpf](https://github.com/purpleBPF/purplebpf)

## 목차

| 문서 | 내용 |
|---|---|
| [데이터 모델](./data-model/README.md) | PostgreSQL ERD · Iceberg(Parquet) 파일 구조 · dbt `coverage` 마트와 table 저장 이유 |
| [아키텍처](./architecture/README.md) | 전체 구성도(draw.io) · 공격/방어/측정 루프 |

## 구조
```
docs/
├── README.md
├── data-model/
│   ├── README.md      # ERD + Iceberg + dbt 설명
│   └── erd.png
└── architecture/
    ├── README.md
    └── purplebpf-architecture.drawio
```

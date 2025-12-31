# presence-infra
Energy-aware AI infrastructure for edge and telco environments

┌───────────────────────────────┐
│           CLOUD / CORE        │
│   Large models • heavy train  │
└───────────────▲───────────────┘
                │
┌───────────────┴───────────────┐
│        REGIONAL / METRO        │
│  Shared inference • batching  │
└───────────────▲───────────────┘
                │
┌───────────────┴───────────────┐
│        TELCO EDGE / CO         │
│  Low-latency inference        │
│  Power- & cooling-aware       │
└───────────────▲───────────────┘
                │
┌───────────────┴───────────────┐
│      ACCESS / LOCAL SITES     │
│  Homes • offices • venues     │
└───────────────▲───────────────┘
                │
┌───────────────┴───────────────┐
│        DEVICES / ENDPOINTS    │
│  On-device AI • sensors       │
└───────────────────────────────┘

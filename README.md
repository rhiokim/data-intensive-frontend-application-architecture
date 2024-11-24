# data-intensive-frontend-application-architecture
Data Intensive Frontend Application Architecture

- Screen
  - File system based routing
- Separation of concern
  - Reusable functions to manipulate primitive data
  - Reusable functions to manipulate Object
  - Reusable functions to manipulate Array
  - Reusable functions to manipulate Date
  - Reusable functions to manipulate data for specific domain
- Constants
  - global
    - packages/constants/src/index.ts 
  - domain specific
    - packages/constants/:serviceIdentifier/*.ts
- Data
  - Refining
  - Immutability
- Function
- Events
  - Device
  - Browser
- Type definitions
  - 타입 선언은 IDE에서 데이터에 대한 규격을 빠르게 접근, 이해하기 위한 참조 데이터로 이 또한 데이터 중심적 사고로 접근할 수록 좋다.
  - packages/api/src/index.ts
    - Do have DTO(data transfer object) type definition only
  - packages/types/src/index.ts
    - packages/types/src/:serviceIdentifier/*.ts 

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

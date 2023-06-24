# NFT 데이터 분석 프로젝트

이 프로젝트는 NFT(Non-Fungible Token)의 거래 데이터를 분석하여 거래량, 가스 비용, 가스 비용의 증가 시간 등의 정보를 제공합니다. 

## 폴더 구조

- `RequestData/` : 컨트랙트 주소를 사용하여 NFT 거래 데이터를 요청하고, 가져온 데이터를 `GeneratedData/` 폴더에 저장합니다.
- `AnlzData/` : `GeneratedData/` 폴더에 저장된 데이터를 분석하고, 분석 결과를 다시 `GeneratedData/` 폴더에 저장합니다.
- `GeneratedData/` : 가져온 데이터와 분석 결과를 저장하는 폴더입니다. 이 폴더는 `.gitignore`에 의해 Git 추적에서 제외됩니다.

## 파일 설명

- `RequestData/RequestTransactionByContractAddress` : 컨트랙트 주소를 입력받아 NFT 거래 데이터를 요청하는 스크립트입니다.
- `AnlzData/` : `GeneratedData/` 폴더의 데이터를 분석하는 스크립트들이 포함되어 있습니다.
- `GeneratedData/` : 이 폴더에는 요청된 데이터와 분석 결과가 저장됩니다.
- `정보보호.pdf` : 프로젝트에 대한 비교 분석 보고서입니다.

## 실행 방법

1. `RequestData/RequestTransactionByContractAddress` 실행 : 컨트랙트 주소를 입력하고, NFT 거래 데이터를 요청합니다.
2. `AnlzData/`의 스크립트들 실행 : 요청된 데이터를 분석하고 결과를 저장합니다.

이 프로젝트는 NFT 거래 데이터에 대한 깊은 이해를 제공하는 데 도움이 될 것입니다.

# USB_LoRa_RSSI_Detecter

**USB Serial API**를 통해 Arduino에 연결된 **LoRa 장치**의 RSSI 신호 강도, 현재 위치, 송수신 데이터를 **실시간으로 모니터링**할 수 있는 웹 기반 서비스입니다.  
본 프로젝트는 [Vercel V0](https://vercel.com/v0) 기반으로 제작되었으며, 일부 구성 요소는 커스터마이징되어 개발되었습니다.

---

## 🧩 서비스 구조

### 🔌 USB Serial API
- 브라우저의 Web Serial API를 통해 Arduino 장치와 직렬 통신
- LoRa 수신기에서 전송된 RSSI, GPS 좌표, 데이터 패킷 등을 수신

### 📡 Live Monitor Section
- 수신된 LoRa 데이터 로그를 실시간으로 확인 가능
- 시간, 송신자, 메시지, RSSI 등의 정보 실시간 갱신

### 📍 Live Position Monitoring Section
- 수신된 GPS 좌표를 기반으로 지도에 LoRa 장치의 위치 표시
- 위치 정보를 실시간으로 갱신

### 🔄 LoRa Communication Monitoring Section
- 송수신 데이터의 무결성, 전송 횟수, 실패율 등의 통신 상태 확인
- RSSI 값을 히스토리 차트로 시각화

---

## 📦 하드웨어 정보

### 💾 PCB Layout
- Circuit Diagram을 바탕으로 제작한 Arduino Nano 기반 PCB
- EasyEDA를 통해 설계 및 제작
- [PCB Layout 링크 - 추후 첨부 예정]

### ⚙️ Circuit Diagram
- Arduino Nano 기반의 양방향 LoRa 송수신 회로
- 수신기는 버튼을 눌러 데이터를 전송하며, 노트북(또는 모바일 기기)에 연결되어 실시간 데이터를 시각화
- 송신기는 수신기로부터 데이터를 받아 RSSI, 수신 시간 등을 SD 카드에 저장
- [회로도 링크 - 추후 첨부 예정]

---

## 🌐 서비스 다운로드 및 접속

- [서비스 링크 - 추후 첨부 예정]

---

## 🛠 Powered By

**SEOGO** in Gongju High School

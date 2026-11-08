# 📱 CSEETV

> **Powered by KH2C**  
> **Creator**: **Brian Kim** (<dev.kh2c@gmail.com>)

사용하지 않는 안드로이드 스마트폰을 **웹 브라우저로 어디서나 접속 가능한 스마트 CCTV 및 자동 순환 녹화 블랙박스**로 활용할 수 있는 애플리케이션입니다.

---

## 📥 1. 앱 다운로드 및 설치 방법 (APK)

1. CCTV로 사용할 안드로이드 스마트폰의 웹 브라우저에서 아래 링크를 눌러 설치 파일(**`CSEETV.apk`**)을 다운로드합니다:
   * 👉 **[📦 CSEETV.apk 바로 다운로드 (Direct Download)](https://github.com/kbwook/CSEETV/raw/main/CSEETV.apk)**
2. 다운로드한 `CSEETV.apk` 파일을 실행하여 설치합니다.
   * *안드로이드 보안 안내 창이 나타나면 **"이 출처의 앱 설치 허용(출처를 알 수 없는 앱 허용)"**을 켜주세요.*
3. 앱을 실행한 뒤 **[CSEETV 웹서버 시작하기]** 버튼을 누르고 **카메라 및 알림 권한**을 허용합니다.

---

## 🚀 2. 빠른 실행 및 접속 요약

1. **CCTV 가동 시작**:
   * 스마트폰에서 **CSEETV** 앱을 실행하고 **[CSEETV 웹서버 시작하기]** 버튼을 누릅니다.
   * 기기마다 고유한 **카메라 ID**(예: `cam-a3f1`)가 자동 생성되며, 필요 시 원하는 이름으로 변경하거나 **접속 PIN(비밀번호)**을 설정할 수 있습니다.
2. **PC 또는 다른 스마트폰에서 실시간 영상 보기**:
   * **방법 1 (QR 코드 스캔 — 가장 간편)**: CCTV 스마트폰 화면에 표시된 **QR 코드**를 다른 스마트폰 카메라로 스캔하면 즉시 웹 콘솔에 접속됩니다.
   * **방법 2 (동일 Wi-Fi 내부 접속)**: 같은 공유기(Wi-Fi)에 연결된 PC/스마트폰 브라우저 주소창에 앱 화면 상단의 주소(예: `http://192.168.x.x:8080`)를 입력합니다.
   * **방법 3 (외부 LTE/5G 접속)**:
     * 공유기 UPnP가 활성화된 환경에서는 앱 화면의 **`다이렉트(UPnP)`** 주소 또는 **`Hybrid Gateway`** 주소(`http://kbwook.familyds.com:9080/cam/<카메라ID>/`)로 어디서나 접속할 수 있습니다.
     * UPnP 동작에 문제가 있는 공유기 환경에서도 **Hybrid Gateway** 주소를 통해 자동으로 연결됩니다.

---

## 📖 3. 상세 설치 및 사용 설명서 (GitHub Pages)

앱 화면의 각 설정 항목, 원격 CCTV 가동/중지(Start/Stop), 시간/용량 단위 자동 동영상 순환 녹화(블랙박스), 동작 감지, 블랙 스크린 절전 모드, 그리고 접속 보안(PIN) 설정에 대한 자세한 사용 방법은 아래 **사용자 가이드 페이지**를 참조하세요.

* 🌐 **[CSEETV 앱 설치 및 상세 사용 가이드 (GitHub Pages 바로가기)](https://kbwook.github.io/CSEETV/)**
* 🔒 **[개인정보처리방침 및 오픈소스 고지 (Privacy Policy)](https://kbwook.github.io/CSEETV/privacy.html)**

---

## 👥 Credits
* **CSEETV · Powered by KH2C**
* **Created by Brian Kim** ([dev.kh2c@gmail.com](mailto:dev.kh2c@gmail.com))

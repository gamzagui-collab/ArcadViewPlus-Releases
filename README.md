# Arcad View+

Android에서 DWG·DXF 도면을 열고, 거리를 재거나 도면 위에 표시할 수 있습니다.

## [↓ Android 설치 파일(APK) 바로 다운로드 · v0.9.3](https://github.com/gamzagui-collab/ArcadViewPlus-Releases/releases/download/v0.9.3/ArcadViewPlus-0.9.3.apk)

- **설치 파일** · ArcadViewPlus-0.9.3.apk · 약 96 MB
- **설치 환경** · Android 6.0 이상 · 64비트(arm64-v8a, x86_64) · GitHub 로그인 없이 다운로드

[항상 최신 릴리스와 변경 사항 보기](https://github.com/gamzagui-collab/ArcadViewPlus-Releases/releases/latest)

## 처음 설치하기

1. Android 휴대폰에서 위 **Android 설치 파일(APK) 바로 다운로드**를 누릅니다.
2. 다운로드 알림이나 **다운로드** 폴더에서 **ArcadViewPlus-0.9.3.apk**를 엽니다.
3. Android가 설치 권한을 요청하면 **설정 → 이 출처의 앱 설치 허용**을 선택하고 설치 화면으로 돌아옵니다. 메뉴 이름은 기기마다 다를 수 있습니다. [Android 설치 권한 안내](https://support.google.com/pixelphone/answer/7391672?hl=ko)
4. **설치**를 누른 뒤 **열기**를 누릅니다.

### 기존 사용자가 업데이트하기

기존 앱을 열면 필수 업데이트를 안내합니다. 다운로드가 끝나면 Android 설치 화면에서 **설치** 또는 **업데이트**를 누릅니다. 직접 확인하려면 홈에서 **앱 정보 → 업데이트 확인**을 누릅니다. 기존 앱 위에 설치하면 도면과 작업 데이터가 유지됩니다.

<p>
  <img src="docs/media/home.png" width="250" alt="Arcad View+ 홈 화면의 도면 열기, 폴더 연결, 앱 정보">
  <img src="docs/media/update-approval.png" width="250" alt="이미 설치된 Arcad View+의 Android 업데이트 승인 화면">
</p>

## 도면 열기와 거리 측정

1. 홈에서 **도면 열기** 또는 **폴더 연결**을 누릅니다. 필요한 경우 도면 폴더 사용을 허용하고 목록에서 DWG나 DXF를 선택합니다.
2. 도면에서 손가락 하나를 끌어 화면을 이동합니다. 두 손가락을 벌리거나 모아 확대·축소합니다.
3. 하단 **측정**을 누르고 도면에서 두 점을 차례로 찍으면 정렬 거리가 표시됩니다.
4. 짧게 눌러 점을 입력하거나, 한 위치를 약 0.25초 누른 뒤 움직여 위치를 미세 조정합니다. 최근에 연 파일은 홈의 **최근 도면**에서 다시 열 수 있습니다.

<img src="docs/media/open-and-measure.gif" width="300" alt="실제 Arcad View+에서 예제 도면을 열고 두 점 사이 거리를 측정하는 과정">

<p>
  <img src="docs/media/drawing-list.png" width="250" alt="DWG와 DXF 예제가 표시된 도면 선택 화면">
  <img src="docs/media/distance.png" width="250" alt="도면 위에 두 점 사이 정렬 거리 측정 결과가 표시된 화면">
</p>

화면과 GIF는 LDPlayer-9에서 예제 도면으로 직접 캡처했습니다.

## 범위로 객체 선택하기

도면 하단의 **선택**을 누릅니다. 도면에서 시작점을 약 0.25초 누른 상태로 원하는 범위 끝까지 끌고 손을 떼세요. 사각형 안에 완전히 들어온 객체에 윤곽과 선택 개수가 표시됩니다. **선택 해제**로 초기화할 수 있습니다.

짧게 눌러 개별 객체를 선택하고, 누르자마자 끌어 화면을 이동합니다. 이동·삭제는 개별 객체에 적용됩니다.

<img src="docs/media/window-selection.png" width="270" alt="예제 도면의 범위 선택 결과로 객체 두 개와 청록색 윤곽이 표시된 화면">

## 이용 범위와 라이선스

기본 도면 보기와 정렬 거리·정렬 치수는 무료입니다. 유료 도구는 로그인과 해당 이용권이 필요합니다.

GUI's Arc Industry가 Arcad View+를 배포합니다. 앱의 **앱 정보 → 오픈소스 및 라이선스**에서 구성요소별 고지를 확인할 수 있습니다.

- [제3자 구성요소 및 라이선스 고지](https://github.com/gamzagui-collab/ArcadViewPlus-Releases/releases/latest/download/THIRD-PARTY-NOTICES.zip)
- [GNU LibreDWG 대응 소스 및 GPL 라이선스 · v0.9.3](https://github.com/gamzagui-collab/ArcadViewPlus-Releases/releases/download/v0.9.3/GNU-LibreDWG-Corresponding-Source-0.14.9167.zip)
- [배포 파일 SHA-256 확인 · v0.9.3](https://github.com/gamzagui-collab/ArcadViewPlus-Releases/releases/download/v0.9.3/SHA256SUMS.txt)

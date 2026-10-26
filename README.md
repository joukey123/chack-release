<p align="center"><img src="icon.png" width="160" alt="Chack! 아이콘"></p>

<h1 align="center">Chack! · 월간 가계부</h1>

<p align="center">서버 없이 <b>내 맥과 내 iCloud Drive에만</b> 저장하는 개인 가계부 (macOS 13 이상)</p>

## 다운로드

| 내 맥 | 설치 파일 |
| --- | --- |
| 애플 실리콘 (M1, M2, M3, M4 …) | **[Chack-AppleSilicon.dmg](https://github.com/joukey123/chack-release/releases/latest/download/Chack-AppleSilicon.dmg)** |
| 인텔 | **[Chack-Intel.dmg](https://github.com/joukey123/chack-release/releases/latest/download/Chack-Intel.dmg)** |

내 맥이 어느 쪽인지 모르겠다면 화면 왼쪽 위 Apple 메뉴 › **이 Mac에 관하여**에서 "칩"이 Apple M…이면 애플 실리콘, "프로세서"가 Intel…이면 인텔이에요.

## 설치

1. 받은 DMG를 열고 **Chack!** 을 **Applications** 폴더로 끌어다 놓아요.
2. 응용 프로그램 폴더에서 Chack!을 열어요.
3. 처음 열 때 "Apple에서 확인할 수 없음" 창이 뜨면 **완료**를 누르고,
   **시스템 설정 › 개인정보 보호 및 보안**의 아래쪽에서 **그래도 열기**를 눌러요.
   (개발자 인증서 없이 직접 배포하는 앱이라 처음 한 번만 필요해요.)
   터미널이 편하면: `xattr -dr com.apple.quarantine "/Applications/Chack!.app"`

## 업데이트

앱의 **설정 › 업데이트 확인 → 업데이트 설치**를 누르면 이 저장소의 최신 버전을 받아 바꿔 끼우고 다시 열어요.
가계부 기록은 iCloud Drive에 있어서 업데이트해도 그대로 남아요.

## 기록은 어디에?

- `iCloud Drive › Chack › 가계부.json` 파일 하나에 모든 기록과 설정이 들어가요. 자동 백업은 같은 폴더의 `백업`에 남아요.
- 개발자 서버로는 아무것도 보내지 않아요. 인터넷은 업데이트 확인에만 써요.
- 카드 내역 사진·PDF는 맥에 내장된 문자 인식으로 맥 안에서만 읽고, 원본은 저장하지 않아요.

모든 버전은 [Releases](https://github.com/joukey123/chack-release/releases)에서 볼 수 있어요.

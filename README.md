# 꺼줘 (Kkeojwo) — Support

## 설치 / Install

**Homebrew** (공증된 Developer ID 빌드 / notarized Developer ID build):

```sh
brew install ulBible/chakchak/kkeojwo
```

Mac App Store 버전은 준비 중입니다. / Mac App Store version coming soon.

**Keep Awake, Sleep & Shutdown Timer for macOS.** 정한 시각까지 깨어 있다가, 시간이 되면 꺼줘.
*A Chakchak Works app — small tools that snap right in.*

- 개인정보 처리방침 / Privacy Policy: [PRIVACY.md](PRIVACY.md)
- 문의·버그 신고 / Support: [Issues](https://github.com/ulBible/Kkeojwo-support/issues)
- Mac App Store: (출시 후 링크 추가 / link coming soon)

## 요구사항 / Requirements
Apple Silicon Mac, macOS 14 or later. 한국어 · English · 日本語 · 简体中文.

## 자주 묻는 질문 / FAQ

**왜 "자동화(System Events)" 권한을 묻나요?** — 잠자기·종료 예약을 실행할 때 macOS에 그 명령을 전달하기 위해서입니다. 다른 앱을 제어하거나 입력을 읽지 않습니다. 깨어 있기와 화면 잠금은 이 권한 없이 동작합니다.
*Why does it ask for Automation (System Events)?* — Only to hand the scheduled sleep/shutdown command to macOS. Keep-awake and screen lock work without it.

**화면 잠금이 암호를 묻지 않아요.** — 시스템 설정 › 잠금 화면에서 "잠자기 또는 화면 보호기 시작 후 암호 요구"를 **즉시**로 두세요.
*Lock doesn't ask for a password.* — Set System Settings › Lock Screen › "Require password after sleep or screen saver begins" to **Immediately**.

**뚜껑을 닫고 나갔다 오니 예약이 취소됐어요.** — 의도된 동작입니다. 맥이 잠든 사이 예약 시각을 2분 넘게 지나쳤으면, 깨어난 직후 갑자기 끄지 않고 취소한 뒤 알려드립니다.
*My schedule was cancelled after I closed the lid.* — By design: if the scheduled time passed by more than two minutes while the Mac was asleep, Kkeojwo cancels instead of powering down the moment you open the lid.

**종료가 안 되고 멈춰요.** — 저장하지 않은 문서가 있으면 macOS가 저장 여부를 물으며 종료를 멈춥니다. 꺼줘는 이를 우회하지 않습니다.
*Shutdown stops halfway.* — macOS halts shutdown when an app has unsaved work. Kkeojwo never bypasses that.

**뚜껑을 닫아도 깨어 있게 할 수 있나요?** — 아직 아닙니다(클램셸 모드는 검토 중). 뚜껑을 닫으면 macOS가 맥을 재웁니다.
*Can it keep the Mac awake with the lid closed?* — Not yet (clamshell mode is under consideration).

## 버그 신고 / Reporting a bug
[Issues](https://github.com/ulBible/Kkeojwo-support/issues)에 macOS 버전, 앱 버전(꺼줘 정보에서 확인), 무엇을 했고 무엇이 보였는지를 적어주세요.
Please include your macOS version, the app version (About Kkeojwo), what you did, and what you saw.

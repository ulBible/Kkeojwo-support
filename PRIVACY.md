# 꺼줘 (Kkeojwo) 개인정보 처리방침 · Privacy Policy

시행일 / Effective: 2026-08-30 · Chakchak Works

## 한국어

**꺼줘는 어떤 개인정보도 수집하지 않습니다.**

- 네트워크 통신, 분석 도구, 계정, 서버, 광고가 없습니다. 앱은 인터넷에 연결하지 않습니다.
- 앱이 저장하는 것은 설정값(끝 동작 기본값, 화면 잠자기 허용, 메뉴바 표시, 알림, 온보딩 완료 여부)뿐이며, 이 값은 사용자의 맥 안(앱 컨테이너의 사용자 기본값)에만 남습니다.
- 깨어 있기(웨이크락)·화면 잠금·잠자기·종료는 전부 macOS의 시스템 API로 이 맥 안에서 실행됩니다.

앱이 요청하는 권한과 용도:

| 권한 | 언제 | 용도 |
|---|---|---|
| 자동화 (System Events 제어) | 잠자기·종료를 예약하거나 "지금 바로 종료"를 처음 실행할 때 macOS가 1회 요청 | 예약한 시각에 잠자기·종료 명령을 macOS에 전달. 다른 앱을 제어하거나 입력을 읽지 않습니다. |
| 알림 | 끝 동작이 있는 세션을 처음 시작할 때 | 잠금·잠자기·종료 60초 전 안내와 취소·연장 버튼 |
| 로그인 항목 (선택) | 온보딩 또는 설정에서 스위치를 켤 때만 | 로그인 시 자동 실행 |

문의: https://github.com/ulBible/Kkeojwo-support/issues

## English

**Kkeojwo does not collect any personal data.**

- There is no network communication, no analytics, no accounts, no servers, and no ads. The app never connects to the internet.
- The only things the app stores are its own settings (default end action, allow display sleep, menu bar display, notifications, onboarding done), kept in the app's container on your Mac.
- Keep-awake, screen lock, sleep, and shutdown are all performed on your Mac through macOS system APIs.

Permissions the app asks for, and why:

| Permission | When | Purpose |
|---|---|---|
| Automation (control System Events) | Once, the first time you schedule sleep/shutdown or use "Shut Down" right now | To hand the sleep/shutdown command to macOS at the scheduled time. The app never controls other apps or reads your input. |
| Notifications | The first time you start a session with an end action | The 60-second heads-up before lock, sleep, or shutdown, with Cancel / 10 more minutes |
| Login item (optional) | Only when you turn on the switch in onboarding or Settings | Launch at login |

Contact: https://github.com/ulBible/Kkeojwo-support/issues

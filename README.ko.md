# Spotlight Clipboard History Keyboard Shortcut

[English](README.md)

**Option+V (⌥V)**로 macOS Spotlight의 **클립보드 기록**을 여는 Karabiner-Elements 규칙입니다.

## 설치

**macOS Tahoe 26 이상**, 권한 설정을 마친 **Karabiner-Elements 16 이상**이 필요합니다.

1. Karabiner-Elements에서 **Complex Modifications → Add your own rule**을 엽니다.
2. [`karabiner-rule.json`](karabiner-rule.json)을 붙여 넣고 저장한 뒤 **⌥V**를 누릅니다.

## 동작

Spotlight 검색창에 포커스가 있을 때만 Command+4를 전송합니다. 이미 열려 있으면 즉시, 짧게 누르면 V를 뗄 때, 계속 누르면 100ms에 확인하고 필요 시 300ms에 재확인합니다. 중복 열기는 500ms 동안 차단합니다.

전환되지 않으면 **⌥V**를 다시 누릅니다. 별도 프로그램은 필요하지 않습니다.

Apple이 Spotlight 클립보드 기록 전용 단축키를 제공할 때까지 유지보수합니다.

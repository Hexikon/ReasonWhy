[ReasonWhy](/README.md)
===
[Software / Coding_IDE / UniversialIDE](./README.md)
```
#Choosing #Reason #Software
```

## :card_index_dividers: 유니버셜 IDE ( CUI/GUI )
유니버셜 IDE 는 플랫폼에 종속된 코딩을 제외한 스크립트코딩과 범용적인 코딩을 위한 IDE입니다. 현재 모바일컴퓨터(패드,폰)에서 코딩을 함에 있어서 적절한 IDE가 존재하지 않습니다. 모바일에서는 원격제어를 통한 CUI 에디터로 코딩이 가능하기에 CUI/GUI를 하나씩 선택해야합니다.

**선택조건**
- 기본 : 범용적인 언어선택이 가능해야한다.
- UI : 터미널, 파일트리 기능이 존재해야 한다.
- UX : 단축키설정과 세부적인 이동, 포커스 기능이 세밀하게 되어야 한다
- 기능 : 프로젝트파일검색, 명령어검색, 심볼검색, 파일타입선택, 찾기&변환, 멀티커서, 이지모션
- 기타 : CUI/GUI의 통합이 되야함으로 두 에디터의 기능이 동일해야한다.

선택대상
- GUI : ATOM ( 제외 )
- GUI : VSCODE ( 확인중 )
- GUI : INTELLIJ ( 확인중 )
- CUI : NEOVIM ( 제외 )
- CUI : EMACS ( 선택 )

## :card_index_dividers: 상세설명
### GUI : ATOM ( 제외 )

> 제외이유 : 각종 플러그인에서 터미널의 Toggle이 적절하게 이루어지지 않는다
> 
> 확인 플러그인
> - platformio-ide-terminal
> - terminal-plus
> - vk-terminal
> - terminal-tab
> - iv-terminal
> - x-terminal

Editor 부분에 포커스 상태에서는 Toggle이 정상적으로 이루어지나, 포커스가 터미널에 존재할때 Toggle되는 적절하게 되는 플러그인이 존재하지 않는다.
![Screen Capture 2022-02-11 at 09 23 45](https://user-images.githubusercontent.com/77244047/153519344-b0444273-6a26-4c1d-8816-2a6dfd6413b5.gif)

### CUI : NEOVIM ( 제외 )

> 제외이유 : 일반적인 GUI 에디터와 사용자 인터페이스 통합을 해야하나 VIM은 기본적으로 insert모드가 기본이 아님으로 사용자기준 통합이 어럾다

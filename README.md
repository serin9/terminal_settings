# terminal_settings

1. [terminal을 iterm 설치](https://www.iterm2.com/downloads.html)
2. [oh my zsh 설치](http://sourabhbajaj.com/mac-setup/iTerm/zsh.html)
3. .zshrc 수정
* => 현재 설정한 테마는 "bullet_train"
* => 설정 방법: 
  * (1) 테마 다운로드:[링크](https://raw.githubusercontent.com/caiogondim/bullet-train-oh-my-zsh-theme/master/bullet-train.zsh-theme) - 여기에 더 많은 테마들이 있음.
  * (2) $ZSH_CUSTOM/themes/ 이 경로로 해당 bullet-train.zsh-theme 파일을 옮기기
  * (3) ~/.zshrc 파일에서 ZSH_THEME: "bullet_train" 이렇게 수정
  * (4) bullet_train 테가 같이 현재 경로가 바 형식으로 나오는거는 prefences의 profiles의 Text에서 폰트를 수정해야함.
    * 현재 상태:
      * Regular Font: 14pt Roboto Mono for Powerline
      * Non-ASCII Font: 13pt Sauce Code Powerline
      * (해당 폰트 없으면 다운 받아야함)
  * (5) 테마의 지정색의 명도나 채도를 바꾸려면 preference의 profiles의 Colors에서 pick!
* => [참고]: [테마 설정 방법](https://github.com/caiogondim/bullet-train-oh-my-zsh-theme#for-oh-my-zsh-users)


* + [이외 맥 셋업 가이드](http://sourabhbajaj.com/mac-setup/)
* + [이외 vim 설정 가이드](http://vimdoc.sourceforge.net/htmldoc/syntax.html)
  * vim plugin 적용: vim +PluginInstall +qall

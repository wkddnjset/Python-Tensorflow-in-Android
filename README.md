# Python_in_Android
 1. Termux를 이용하여 안드로이드OS에서 Jupyter Notebook으로 python 코딩하기


## Termux로 Python 개발환경 구축
  
  
### Install Package (Python...)


   - Termux는 apt install이 아닌 pkg install을 사용합니다. Termux의 패키지종류는 [여기](https://github.com/termux/termux-packages)에서 확인 하실 수 있습니다.
  
  
  ```
 $ pkg install clang python python-dev fftw libzmq libzmq-dev freetype freetype-dev libpng libpng-dev pkg-config
  ```
  
### Install Python Libraries


   - Termux에서 pip를 사용할 경우 아래와 같이 사용해야 합니다. 혹시 이미 pip install을 사용하여 다운로드 하셨을 경우 
   pip uninstall 명령어를 사용하여 삭제 후 다시 인스톨 해주셔야 합니다. 
   
   
  ```
  $ LDFLAGS=" -lm -lcompiler_rt" pip install numpy==1.12
  $ LDFLAGS=" -lm -lcompiler_rt" pip install matplotlib pandas jupyter
  ```
  
  
  
  
## 참고

- [안드로이드 터미널 명령어](https://github.com/jackpal/Android-Terminal-Emulator/wiki/Android-Shell-Command-Reference) 
- [안드로이드에서 터미널 기반 개발 환경 세팅하기](http://arkainoh.blogspot.kr/2017/04/android.terminal.html) (Termux 사용)

- [안드로이드에서 쥬피터 사용하기](http://www.leouieda.com/blog/scipy-on-android.html) (Termux 사용)
- [README 쓰는 방법](https://stackedit.io/editor) (낙서장)

# Python-in-Android
 1. 안드로이드 OS에서 Python(Tensorflow) 코딩하기
 2. Jupyter Notebook을 이용하여 안드로이드에서 Python 코딩하기

## Termax 사용하기

  - “Unable to locate package” 에러
  
  ```
  $ apt install clang python python-dev fftw libzmq libzmq-dev freetype freetype-dev libpng libpng-dev pkg-config
  $ LDFLAGS=" -lm -lcompiler_rt" pip install numpy matplotlib pandas jupyter
  $ jupyter notebook
  ```
  
  - Install Python
  
  ```
  $ apt install clang python python-dev fftw libzmq libzmq-dev freetype freetype-dev libpng libpng-dev pkg-config
  $ LDFLAGS=" -lm -lcompiler_rt" pip install numpy matplotlib pandas jupyter
  $ jupyter notebook
  ```

  
  
  
## 참고

- [안드로이드 터미널 명령어](https://github.com/jackpal/Android-Terminal-Emulator/wiki/Android-Shell-Command-Reference) 
- [안드로이드에서 터미널 기반 개발 환경 세팅하기](http://arkainoh.blogspot.kr/2017/04/android.terminal.html) (Termux 사용)

- [안드로이드에서 쥬피터 사용하기](http://www.leouieda.com/blog/scipy-on-android.html) (Termux 사용)
- [README 쓰는 방법](https://stackedit.io/editor) (낙서장)

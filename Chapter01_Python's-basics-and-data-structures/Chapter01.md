# What is Python ?

<img src="https://www.python.org/static/community_logos/python-logo-master-v3-TM-flattened.png" height="100">

파이썬,

<img src="https://upload.wikimedia.org/wikipedia/ko/4/49/WeWantToKnow.jpg" width="300">

## Interprete(동시통역) vs Compile(번역)

파이썬은 인터프리트 언어일까요, 컴파일 언어일까요? → 정답: 인터프리트 언어

인터프리트 언어..?

쉽게 말하면 interprete ≒ 동시통역, compile ≒ translate

<p align="center">
  <img src="https://github.com/cho-hyeonjin/python-algorithm-first-step/assets/78816754/24d50d45-47cf-475b-bf5c-02eb5783f09a" width="50%" align="center" />
  <img src="https://logos-world.net/wp-content/uploads/2021/10/Python-Symbol.png" width="30%" align="center" />
  <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" width="5%" align="center" />
  &nbsp;
  <img src="https://brandslogos.com/wp-content/uploads/images/java-logo-1.png" width="8%" align="center" />
</p>

인터프리터 : 말 한마디마다 순간기억 → 실시간으로 번역해줌

<p align="center">
  <img src="https://github.com/cho-hyeonjin/python-algorithm-first-step/assets/78816754/dc33dba9-a8df-4bec-8653-e9c11868a743" width="40%" align="center" />
  &nbsp;
  &nbsp;
  &nbsp;
  &nbsp;
  <img src="https://i.namu.wiki/i/KcqDuQYTxNpUcLIMZTg28QXse0XiWx1G7K68kYYCo1GuhoHmhB_V8Qe9odGGt0BH9-0nQZTN53WXTNpDmwVfWQ.svg" width="5%" align="center" />
  &nbsp;
  &nbsp;
  &nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/ISO_C%2B%2B_Logo.svg/612px-ISO_C%2B%2B_Logo.svg.png" width="4%" align="center" />
  &nbsp;
  <img src="https://go.dev/blog/go-brand/Go-Logo/PNG/Go-Logo_Blue.png" width="10%" align="center" />
  &nbsp;
  &nbsp;
  &nbsp;
  &nbsp;
  &nbsp;
  &nbsp;
  &nbsp;
  &nbsp;
  &nbsp;
  &nbsp;
  &nbsp;
  &nbsp;
  &nbsp;
  &nbsp;
  &nbsp;
  &nbsp;
  &nbsp;
</p>

컴파일러 : 말 끝날때까지 적어두고 하고 말 끝나면 한 번에 번역해줌

Python shell = interpreter, Python shell 이 명령어 번역하는 방식 = interprete

## How to use Python?

파이썬은 동시통역형 Interpreted 언어임에도 2가지 모드 제공

### 1. Interactive Mode

  <img width="500" src="https://github.com/cho-hyeonjin/python-algorithm-first-step/assets/78816754/662af592-2900-4437-81e0-386a1a963c15" />

  <br/>

  <img src="https://github.com/cho-hyeonjin/python-algorithm-first-step/assets/78816754/12602fbd-11cb-4c91-bd36-68b6da6e0ed6">

> 1.  터미널에서 ' `python3` ' 엔터
>
> 2.  ' `>>>` ' : Interactive shell이 실행됨. 대화모드 들어온 것임.
>
> 3.  하고 싶은 계산식 넣고 엔터
>
> 4.  결과 나옴
>
> 5.  ' `exit()` ' 또는 ' `quit()` ' : interactive shell 나오기, 대화모드 종료

이렇게 자세히 적을 필요도 없음.

1+1을 알고 싶으면

python3 엔터 → 1+1 엔터 → exit() 엔터

너무 쉬워서 당황스러울 지경

### 2. Module file Mode ( Script file Mode )

파일에 코드 작성하고 해당 파일을 실행하는 방법

<img src="https://github.com/cho-hyeonjin/python-algorithm-first-step/assets/78816754/c450d777-3a15-4349-a8a0-70c9eb6a9ef2">

node 파일 실행하는거랑 비스무리 한 듯

> 1.  파이썬 문법으로 코드 작성 후 ' `파일명.py` ' 로 저장
>
> 2.  해당 파일 저장된 위치에서 ' `python3 파일명.py` ' : 파일명.py 실행됨.

### 주석은 '#'

```python
  # scriptMode.py 실행해서 확인해보셈

print ("주석 다는 법은 # 주석주석 쏼랴쏼라")
# print "이것은 Python 주석입니다. (난 안보일껄?👻)"

```

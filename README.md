Smart Mirror
=========
# Research
------------------------
Platform : Android (TestBed 진행후 완성도와 상업성 에따라 하드웨어 이식 결정)

Language : JAVA

Development Tool : Android Studio x.x.x

License : MIT

JAVA Language Rules
----------------------------

### Remark

모든 클래스, 메소드는 해당하는 소스의 상단에 클래스, 메소드에 대한 내용에 대한 주석을 단다

### JAVA Naming Conventions

CamelCase : 변수 이름중 새로운 단어가 시작될 때 맨 처음 알파벳은 대문자로 표기한다

Name|Conventions|examples
-----|----------|--------
class|대문자로 시작하고, 명사입니다|String, Color, Button...
interface|대문자로 시작하고, 형용사입니다|Runnable, Remote, ActionListener...
method|소문자로 시작하고, 동사입니다|actionPerformed(), main(), print, println()...
variable|클래스의 약어로 시작합니다|int형 : iCount, double형 : dRate...
Package|소문자로 시작합니다|java, lang, sql, util...
constant|대문자로 표시하며, 단어와 단어 사이에 '_'를 넣습니다|RED, MAX_PRORITY...

Github Commit Message Rule
--------------------------

    [State] : [File]

        [State] : [class/method/...]

            >>>[내용]


- State

    State|When
    -----|----
    Add|새로운 파일, 클래스, 메소드 등이 추가된 경우
    Fix|기존의 파일, 클래스, 메소드 등이 수정된 경우
    Remove|기존의 파일, 클래스, 메소드 등이 제거된 경우

- File

    해당되는 파일 이름

- [class/method/...]

    해당되는 클래스, 메소드 이름

- 내용(단순하게)

    State|설명
    ------|---------
    제거|제거하는 이유
    수정|수정한 부분에 대한 설명
    추가|해당 파일, 클래스, 메소드에 대한 내용


자료 조사 및 사전 확인 작업 전용 레파지토리
--------------------------
신속히 적어 넣을것!

프로젝트 목표 : 

총 예산 : 미정

라이벌 상품들의 리스트와 장점과 단점 :

테스트 용 부품(예 : 라즈베리 파이나 아두이노나 그 친척, 값이 싼 디스플레이, 값이 싼 스피커, 값이 싼 마이크, 값이 싼 마이크로 USB 혹은 C타입 전원 어댑터) 리스트

그 외 필요한 것과 주요 팀원 리스트 소개

빨리 이 글이 전부 지워지고 다른 것으로 채워지길 바랍니다.

Others
------
### [microsoft Face API](https://azure.microsoft.com/ko-kr/services/cognitive-services/face)
알아본 결과단순 얼굴인식으로 그치는 수준이 아닌 안경을 썻는지 부터, 화장을 했는지, 표정, 등등의 다양한 정보 추출 가능, 1달 에 30,000 건 까지 무료사용

```
Detection Result:
3 faces detected
~~
“faceAttributes”: {
“age”: 30.7,
“gender”: “male”,
“headPose”: {
“roll”: -8,
“yaw”: 47.1,
“pitch”: 0
},
“smile”: 0.023,
“facialHair”: {
“moustache”: 0.6,
“beard”: 0.3,
“sideburns”: 0.2
},
“glasses”: “ReadingGlasses”
}
~~
“faceAttributes”: {
“age”: 26.7,
“gender”: “female”,
“headPose”: {
“roll”: -0.4,
“yaw”: 20.5,
“pitch”: 0
},
“smile”: 0.995,
“facialHair”: {
“moustache”: 0,
“beard”: 0,
“sideburns”: 0
},
“glasses”: “NoGlasses”
}
~~
“faceAttributes”: {
“age”: 32.8,
“gender”: “male”,
“headPose”: {
“roll”: -0.5,
“yaw”: 42.8,
“pitch”: 0
},
“smile”: 1,
“facialHair”: {
“moustache”: 0,
“beard”: 0,
“sideburns”: 0
},
“glasses”: “NoGlasses”
}
```
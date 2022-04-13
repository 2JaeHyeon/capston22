# 이재현 프로젝트 설명
팀명 : 투게더 <br>
이름 : 강현준(리더),김민호(코딩),이재현(디자인)... <br> 
운동일지를 적는 어플리케이션 <br>
졸업작품 소개 사이트 : <URL> <br>
포트폴리오 소개 사이트 : <URL> <br>

[졸업작품소개]
- 작품명 : 운동 캘린더 <br>
- 개발환경 : 윈도우 (안드로이드 스튜디오) <br>
- 작품 소개 : 운동을 좋아하고 어떻게 관리하는지 길을 못잡고있는 사람들을 위해서 만들어내는 간단한 캘린더 형식의 운동관리 어플<br>
- 작품의 특징 : 자신이 운동을 어떻게했고 언제했는지 알수있고 다른운동의 방법을 알수있다<br>

<!-- [개발 일지]<br>
*최소한 일주일에 한번 (강의가 있는 날짜로 작성)<br>
ex) <br>
(03월23일) <br>
~~... <br>
내용은 자유 <br>
예) 회의 내용, 개발 과정, 오류해결, 보고서 작성(제출) <br> -->

## 0413 이재현 프로젝트
![0413](https://user-images.githubusercontent.com/79895999/163120776-b8402880-19b8-44d9-a622-27cf94e99653.png)
## 메인화면 재수정작업
디자인을 구현한 PC에서 가동하였으나 열리지않아서 학교 PC에서 재구현하고 입력받는 속성값에 제한을 두어서 값을 넘기지 않도록 구현 <br> 
```
    <EditText
        android:id="@+id/height"
        android:layout_width="300dp"
        android:layout_height="50dp"
        android:layout_gravity="center"
        android:background="@drawable/color"
        android:hint="  키를 입력하세요."
        android:inputType="number"
        android:maxLength="3" />
```
코드에서 maxLength값을 지정해주면서 3자리 이상부터는 받지않도록
구현하였다 나머지 몸무게/나이/성별에도 같은 코드를 지정해주면서
제각각다른 값을 지정해주었다.

## BMI 계산창
![Screenshot_20220413_152811](https://user-images.githubusercontent.com/79895999/163122806-f31142a4-6f3b-4e53-95fe-e7710d37b5ae.png)

BMI 계산하는 결과값에서 계산할 "키"값과 "몸무게"값을 대입하고
계산을 누르면 밑에 23.66처럼 BMI 값이 나오는데 여기서 BMI를 확인하고 자신이 어느정도인지 확인할수있는 창을 만들었고 
밑에 저체중 ~ 고도비만까지 각각의 색을 입혀서 경각심을 느끼게끔 제작을 해보았다. 



## 0406 이재현 프로젝트
### 0406 수정 작업 
##### 첫 화면

![default](img/joljack.jpg)
└─첫화면을 지정하고 뼈대를 지정하면서 기초 화면을 구현<br>
##### 실행시 메인으로 들어갈 화면
<img src="img/main01.png" width="200" height="200">

└─실행시 성별선택 및 개인정보를 입력하는 창을 생성
<br>
을 구현하였으나 디자인성이 부족하다고 느껴서 디자인 수정작업을
진행하였다.

### 수정 디자인
<img src="img/main01_1.png" width="200" height="200">
<br>
창이 잘들어갔는지 확인할수있게 백그라운드 색깔을 임의 지정하였고 <br>
다음창으로 넘어갈수있는 기능을 버튼으로 입력 받을 예정이기 때문에 임의의 버튼을 하나 생성하여 추가하였다.



## 0330 이재현 프로젝트

#### 큰 소개
일러스트로 기초적인 베이스 어플리케이션의 화면을 구현 제작 <br>
안드로이드를 사용해서 보이는 화면쪽을 구현하면서 제작하였다 <br>
추가적인 Java 및 코딩을 이용한 프로그래밍은 나중에 추가할 예정이다.<br>
##### 첫 화면
![default](img/joljack.jpg)
└─첫화면을 지정하고 뼈대를 지정하면서 기초 화면을 구현<br>
##### 실행시 메인으로 들어갈 화면
<img src="img/main01.png" width="200" height="200">

└─실행시 성별선택 및 개인정보를 입력하는 창을 생성
<br>

#### 운동부위별 소개  img
<img src="img/sub01.png" width="200" height="200"><br>
└─운동 방법소개에서 운동부위를 크게 2개를 선정해서 버튼형식(터치)으로 생성하였음 

##### 로딩부분
<img src="img/health.png" width="100" height="100"> <br>
└─로딩 어플리케이션이 실행중 또는 서브페이지 부분에 추가하여 운동이라는 캘린더의 이미지를 부각
<br>

#### 메인아이콘 img
<img src="img/forearm.png" width="100" height="100"><br>
└─앱으로 추출하게된다면 메인 아이콘으로 설정이 될것같다
<br>

## 0323 이재현 프로젝트

GitHub <br>
github.com : Repo 생성, 본인 id와 동일 <br>
[id] github.io <br>

임의의 Repo, 생성후 page생성
[id].github.io/[repo,Name]

#### Team

APP Web Design 공히 GitHubPage로 소개 페이지 작성 <br>
사이트 이름은 자유 (Repo,이름) <br>
대표사이트는 팀별로 1개 사이트 <br>
본인의 포트폴리오로 활용하려면 개인적으로 만들기 가능 <br>

#### <개인>
GitHub Repo, 이름을 capstone22로 생성해서 README.md파일 생성 <br>


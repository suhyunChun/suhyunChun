## 전수현👋

- 🔭 I’m currently working on React / Frontend Developer 
- 🌱 I’m currently learning **Unity**
- 📫 How to reach me: **wjstngus22@naver.com** 



## 🛠️ 기술 스택

<p align="center">
<img alt="JavaScript" src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" />
<img alt="React" src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" />
<img alt="styled" src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
<img src="https://img.shields.io/badge/Unity-FFFFFF?style=for-the-badge&logo=unity&logoColor=Black">
<img src="https://img.shields.io/badge/csharp-512BD4?style=for-the-badge&logo=csharp&logoColor=Black">
</p>

## 💬 프로젝트

### 웹
#### 1. [Day Logger](https://github.com/suhyunChun/final_project)

##### 2인 프로젝트 

##### -FrontEnd

###### 오늘 날짜를 기준으로 더이상 미래의 날짜는 이용할 수 없도록 화살표를 disabled로 설정.
###### 사용자가 원하는 타입의 질문을 설정할 수 있도록 설정 (다중선택, true false, 주관식 등)
###### 원하는 질문들을 저장한 후에는 날짜별로 똑같은 질문들이 뜰 수 있도록 구현.
###### 사용자가 입력한 값들을 그래프 지표로 표현

#### 2. [환율계산기](https://github.com/suhyunChun/Wanted_pre_onboarding-1st_calculate_project)

##### 4인 프로젝트 

##### 첫번째 계산기
수취 국가를 선택하면 환율이 바뀌어 나타남.
송금액을 입력하고 Submit을 누르면 수취금액이 계산해서 화면에 나타남.
API를 이용해서 각 환율을 계산할 수 있도록 구현. 

#### 3. [제품 페이지](https://github.com/suhyunChun/Wanted_pre_onboarding-2st_product_add)

##### 4인 프로젝트 


###### util함수 제작. (uploadImageFile)
######  “상품 정보 고시” 컴포넌트 제작 및 기능 추가
######  전체 상품 리스트 (object array) map으로 출력 및 새로운 항목 추가 기능 담당
######  상품 리스트, 각각의 리스트 저장포맷 관리.

#### 4. [요청 페이지](https://github.com/suhyunChun/Wanted_pre_onboarding-4st_request)

##### 4인 프로젝트 

네비게이션 바, 전체적인 레이아웃, 모바일 반응형 레이아웃과 사이드 슬라이드의 구조와 애니메이션 등을 같이 구현 제한된 컴포넌트들 안에서만 state를 주고 받았기 때문에 리덕스를 쓰는 대신 state를 따로 선언하여 컴포넌트 간의 소통이 일어나도록 구현. 또 styled component에서도 프로퍼티를 받아 윈도우 크기에 따라 다른 스타일이 적용되도록 함.

#### 5. [채팅창](https://github.com/suhyunChun/Wanted_pre_onboarding-5st_setting)

##### 4인 프로젝트 

##### utils 함수들 구현 
삭제되는 메세지의 길이가 10자 이상일시 ...로 줄여주는 함수 및 날짜를 포맷에 맞춰서 출력하는 함수

##### common 폴더의 Button.tsx 구현 

공통적으로 사용되는 디자인의 버튼을 구현, 그리고 id 값을 받는 함수 추가. 삭제, 답장 버튼에 사용.

##### 채팅창의 전체적인 디자인

위의 타이틀 fixed로 고정, 채팅방 스크롤 추가, 새로운 메세지가 추가될 때마다 스크롤이 자동으로 밑으로 내려가는 기능 구현, 화면에서의 삭제



#### 6. [모바일버전 카테고리 및 제품 설명](https://github.com/suhyunChun/15_06th_doubleNC)

##### 4인 프로젝트 

###### 홈/카테고리/브랜드
이미지 슬라이더 구현 (3가지 버튼을 추가 후 버튼을 누를 때마다 지정된 페이지로 이동)
카테고리 테이블 구현 및 링크 기능 추가
땡처리콘 리스트 추가 , 땡처리 API호출로 데이터를 받아온 후 리스트로 출력

### 유니티 

#### 1. [미니알피지](https://github.com/suhyunChun/TeamProjectMiniRPG)

##### 4인 프로젝트 

##### 로딩씬 - Addressable을 이용한 리소스 에셋 비동기 로드

ResourceManager.cs => 각 씬에 필요한 에셋 및 데이터를 비동기 로드.

씬이 다양하고 필요한 에셋들의 숫자가 생각보다 커서 Addressable을 활용해보기로 결정.

각 에셋에 필요한 태그를 추가 후 (Preload, StartScene 등) Addressable를 이용해 비동기 로드. 로드를 하는 도중에는 유저에게 로딩페이지를 보여줌으로 완벽하게 로드 된 상태에서 게임을 플레이 할 수 있도록 환경 조성.


#### 2. [십삼지신이다냥 - RPG](https://github.com/suhyunChun/13-zodiac-animals-meow)

##### 4인 프로젝트 

##### 인벤토리 - 

EventHandler를 이용해서 Draggable로 구현. 무기 위치 바꾸기, 무기 스왑, 마우스 호버링할때 툴팁 보이기 등 구현 
인벤토리에 아이템의 아이콘만 표시되었기 때문에 아이템 정보를 표시해주는 기능을 추가하면 게임 진행에 효율적이라고 판단. OnPointerExit, OnPointerEnter를 사용하여 해당 아이콘 위로 마우스가 올라갔을 때, 그리고 벗어났을 때의 상황에 대한 구현을 진행.
사용자의 편의성을 추가하기 위해 드래그 앤 드랍의 기능을 넣어 아이템의 위치를 원하는 대로 설정할 수 있게 함. 오브젝트가 이상한 곳에 생기지 않 드래그 하는 동안은 레이캐스트 타겟을 끔. 

[트러블슈팅] 
UI를 한 폴더 안에 묶어 정리하는 과정에서 드래그 하는 도중 아이템이 잘 보이지 않는 문제 발생. 이는 각 아이템이 드래그 할 때는 부모의 가장 마지막 자식으로 가도록 설정. UI폴더라는 부모가 더 생김으로써 발생하는 문제. 따라서 인벤토리 UI는 묶어두는 대신 밖에 따로 둠으로서 해결. 


##### Scriptable Object을 이용해서 아이템들의 정보 저장. 

RPG게임이라는 특성을 가지고 있는 저희 게임 특성 상 퀘스트는 스토리 진행에 핵심적인 요소. 퀘스트 정보는 필요에 의해 팀원 중 누구라도 추가하고 수정할 수 있는 정보. 따라서 SO로 관리하는 것이 편리할 것이라고 판단. 
게임 플레이 중에 변하는 정보는 추상 클래스를 만든 뒤 모든 퀘스트가 추상클래스를 상속. 
Dictionary로 커스텀 클래스의 값을 저장함으로서 재사용성과 유지보수성을 높임.
이외의 변하지 않는 정보는 SO로 저장. 
Resources폴더 안에 퀘스트의 SO의 모든 정보를 담고 게임 시작과 동시에 Resources.LoadAll를 통해 모든 정보 로드를 진행.  

##### Newtonsoft json을 사용한 JSON 저장방식으로 게임에 필요한 데이터 저장 및 로드

아이템이 이후에 많이 추가 될 가능성과 여러번의 데이터 수정 과정이 있었음.  csv보다는 json이 가독성으로 더 효율적일 수 있다고 생각해서 json 방식 채택.
 Dictionary를 사용해서 각 필드를 정의하고 추가 및 수정을 용이하게 함으로써 팀프로젝트의 효율성을 높임. Unity에서 Dictionary형태의 구조를 저장할 수 있도록 Newtonsoft json을 이용. 데이터매니저를 이용해서 텍스트를 json으로 변환하는 함수, json을 텍스트로 변환하는 함수를 싱글톤으로 구현하여 전역접근 허용.

##### 레이캐스팅을 이용한 건물 인터렉션

여러 건물이 설치되어 있는 환경 안에서 플레이어와 건물 간의 인터렉션을 하도록 하여 원하는 건물에 손쉽게 관련 UI를 띄울 수 있도록 구현. 레이캐스팅을 플레이어에 적용시켜 특정 태그("Interactable")가 걸려있는 오브젝트만 감지할 수 있도록 구현. Update문을 사용해서 태그를 가진 오브젝트와의 충돌이 특정 거리 안에서 발생했을 때, 인터렉션 키보드키(F)를 입력했다면 각 건물이 가지고 있는 UI가 열림.

#### 3. [테트리스 - 개인프로젝트](https://github.com/suhyunChun/Assignment_Sample_Game_Tetris)

##### 1인 프로젝트

##### enum을 이용한 블록 랜덤 스폰 
게임의 재미를 더하기 위해서는 블록이 랜덤하게 스폰되어야 될 필요성이 있음. enum을 통해 7개의 블록의 종류를 모두 넣은 후, Random하게 숫자를 선택함으로서 랜덤한 블록이 스폰 될 수 있게 구현. 어떤 블록이 나올지 알 수 없기에 게임의 재미를 더할 수 있었음. 

##### 한줄을 채우면 삭제 & 위의 블록들을 한칸씩 내림 

특정 height의 모든 object를 null로 바꿔주는 걸로 구현. 지워진 줄의 윗즐을 블럭들은 transform position의 y값(height)을 1을 뺀 값을 조정함으로써 위의 블럭들을 내리는 코드를 구현. 퍼포먼스 효율을 위해 윗칸에 블럭이 채워져있는지 아닌지 확인하는 조건문을 추가.

##### 방향키를 이용한 블록 회전 및 이동

숫자 방향키를 이용해 회전 및 이동이 가능. 위쪽 방향키로 블록의 회전, 나머지는 블록의 이동을 담당. Input.GetKeyDown을 통해 각 키별로 행동을 설정. 
각 블록에 있는 모든 오브젝트들의 포지션 값을 체크해서  validation을 체크. 유효하지 않는 행동을 하려고 할 때는(벽에 붙어서 회전) 아예 동작이 하지 않도록 구현. 

#### 4. [ATM 프로그램](https://github.com/suhyunChun/Assignment_ATM)

##### 1인 프로젝트

##### 버튼을 눌렀을때 씬전환 대신 보이는 오브젝트들만 바뀌도록 구현

필요한 배경은 2개. 씬을 각각 따로 만들기에는 중복되는 부분이 많았음.
그래서 씬을 하나로 통일 후에 버튼을 누르면 바뀌어야 되는 오브젝트들을 SetActive이용해서 관리. 

#### 5. [우주탐정코고로 - 비행슈팅게임](https://github.com/suhyunChun/Space-Detective-556)

##### 4인 프로젝트 

##### 움직이는 배경 

배경에 위치한 물체를 일정 간격마다 반복되게 아래로 움직이게 구현. 오브젝트들이 다 내려간 후에는 위에 생성되게 만들어서 퍼포먼스적으로 무겁지 않도록 구현. 


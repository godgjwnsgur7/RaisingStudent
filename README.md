# 컴공생키우기

> 첫 프로젝트입니다.

This is my first project.

> 출시 링크 : https://play.google.com/store/apps/details?id=com.EXPstudio.RaisingStudent

Release Link


---


> **2D** / **다이얼로그** / **퀘스트** / **안드로이드** 게임입니다.

It's based on 2D platform and Dialogue, Quest, Android game. 


> 개발기간 : 2020.12.10 ~ 2021.08.27

Dev Period : 2020.12.10 ~ 2021.08.27


---


> 개발인원 : 7명

> **기획** : 박솔휘(메인 기획 겸 프로그래머), 이하영

> **그래픽** : 이가은(UI 디자인), 이경주(캐릭터 디자인), 노희진(일러스트 디자인) 

> **프로그래밍** : 박솔휘, 허준혁

> **사운드** : 이정훈


---


Game Designer (3) : Park Sol Hwi, Lee Ha Yeong

Game Artists (3) : Lee Ga Eun, Lee Gyeong Ju, No Heuijin

Game Programmers (4) : Park Sol Hwi, Heo Jun Hyeok

Sound Designer (1) : Lee Jeong Hun
  
  
---

> 다이얼로그 시스템 아웃라인

![image](https://user-images.githubusercontent.com/67333432/144268169-b82f7f10-3acf-4843-876d-a2c991f91fcc.png)

- 사용자는 UI를 통해 캐릭터의 퀘스트 혹은 일반 대화 데이터를 요청한다.

- 요청을 받은 게임 매니저는 퀘스트 매니저 혹은 토크 매니저를 호출한다.

- 토크 매니저는 Questdata(Json, Scriptable Object) 혹은 npcdata, objectdata(Monobehaviour)를 분석하여 다이얼로그 매니저에게 보낸다.

- 다이얼로그 매니저는 데이터를 받아 대화하는 NPC의 일러스트 / 표정 / 대사를 추출한다.

- 애니메이션 효과와 함께 화면에 출력!


  

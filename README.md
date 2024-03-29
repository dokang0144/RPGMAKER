# 알만툴로 만든 게임(성소오니)
알만툴(RPG MAKER)을 활용해서 저희 반 담임 선생님인 장성소 선생님을 도깨비로 만들어 봤습니다.

## RPG MAKER가 뭐죠?
### RPG MAKER
줄여서 알만툴 말그대로 RPG게임 만드는 툴 이라는 뜻인데 코딩을 안해도 RPG게임을 쉽게 만들수 있습니다.<br><br>
RPG MAKER도 여러 버전이 있는데 제가 사용한것은 RPG MAKER XP라는 툴로 2004년에 발매된 툴입니다.<br><br>
Ruby라는 프로그래밍 언어를 사용하여 스크립트를 작성하고 해상도가 640×480까지만 지원합니다.<br><br>
`지금은 RPG MAKER MZ가 최신버전이고(2020년 발매) 자바스크립트를 사용합니다.`<br><br>
## RPG MAKER로 게임만들기
![image](https://user-images.githubusercontent.com/88234731/185748051-e5df4ca7-2464-4689-83db-e9fc2aea92e2.png)
RPG MAKER를 실행한후 프로젝트를 새로 만든 화면입니다.<br><br>
맵에 아무것도 없으니 꾸며줘야 합니다.<br>
![image](https://user-images.githubusercontent.com/88234731/185748256-4e5d1bcd-7fae-4438-9a0b-262ae00b49c2.png)<br>
여기서 앞에 3개는 레이어 편집이고<br>
뒤에 큐브는 이벤트 편집입니다.<br><br>
맵을 꾸며줘야 하니 레이어 편집을 클릭합니다.<br><br>
그리고 왼쪽의 원하는 타일셋을 선택합니다.<br>
![image](https://user-images.githubusercontent.com/88234731/185748780-d489a32a-625b-4974-ae0b-9f60a6f9f33f.png)<br><br>
![image](https://user-images.githubusercontent.com/88234731/185748831-869bd7f0-e8fb-4014-96d8-1a2d004a1a59.png)<br>
순서대로 연필, 직사각형, 원, 칠하기, 선택입니다.<br>
위의 도구를 이용하여 맵을 꾸며줍니다.<br><br>
저는 이런식으로 꾸며 봤습니다.<br>
![image](https://user-images.githubusercontent.com/88234731/185749376-39e4370d-056d-4a64-ac30-d765d526d6d9.png)<br><br>
새로운 맵을 작성한후 텐트 내부도 꾸며줍니다.<br>
![image](https://user-images.githubusercontent.com/88234731/185751104-589f1cc8-778f-44e9-acb8-0144621c5e7d.png)<br><br>
이제 텐트 밖에서 텐트 안으로 들어오는 이벤트를 만들어 봅시다.<br><br>
이벤트 편집을 클릭후 텐트 입구를 더블클릭 해줍니다.<br>
![image](https://user-images.githubusercontent.com/88234731/185751257-abe01cf8-cf1f-416d-9702-07339bb7db65.png)<br><br>
그러면 이벤트 만들기 창이 뜨는데<br>
![image](https://user-images.githubusercontent.com/88234731/185751472-91120379-f24c-4fee-9049-c93e4dbb2cfe.png)<br><br>

플레이어가 텐트입구에 닿으면 텐트안으로 보내야 하므로<br><br>
시작 조건을 플레이어가 접촉으로 체크해주시고<br>
![image](https://user-images.githubusercontent.com/88234731/185751677-be5fd7b8-c2b9-47b2-b651-aff117fe05d6.png)<br><br>
마름모(◆) 모양을 눌러 실행 내용 창으로 이동합니다.<br>
![image](https://user-images.githubusercontent.com/88234731/185751764-38f20b44-63b3-4d85-90f3-7d30a18a6d1c.png)<br><br>
실행 내용 창에서 2번을 누른후 장소 이동 버튼을 누른다음<br>
![image](https://user-images.githubusercontent.com/88234731/185789118-a223594f-84dd-4261-a92a-efee5226a779.png)<br><br>
직접 지정을 클릭하여<br>
![image](https://user-images.githubusercontent.com/88234731/185788972-c0e2ec88-b2a1-4178-9468-ba65f9f8cc09.png)<br><br>
텐트 내부의 입구로 클릭해줍니다.<br>
![image](https://user-images.githubusercontent.com/88234731/185752027-692d7658-97fe-45c8-a594-4f40903d8245.png)<br><br>
텐트 안에서도 바깥으로 나갈수 있도록 이벤트를 작성해줍니다.<br>
![image](https://user-images.githubusercontent.com/88234731/185752692-c51a43cd-df3f-4458-8a9e-f4e3860f591c.png)<br><br>
그리고 저장후 게임을 실행해보면<br>
![1](https://user-images.githubusercontent.com/88234731/185788849-3e239c1f-5e17-4f24-8d62-011cc8d4dcc8.gif)<br><br>
이렇게 간단하게 게임을 만들수 있습니다. 그리고 여러가지 이벤트를 작성하여 다양한 게임도 만들수 있습니다.
## 성소오니
저는 '아오오니'라는 게임을 언팩하여 대사와 이벤트를 수정하고 '성소오니'를 만들었습니다.<br>
![image](https://user-images.githubusercontent.com/88234731/193286018-b1fa124d-ecd7-46e4-9261-2be8bce0701b.png)<br><br>
[![Video Label](https://user-images.githubusercontent.com/88234731/193291269-d6f549d7-2b26-4ad7-8926-0b55c566a518.gif)](https://youtu.be/3oIgSRp19t8)<br>
↑ ↑ ↑ 게임 플레이 유튜브 링크 (gif를 클릭해주세요)






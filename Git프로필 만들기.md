주변 사람들의 github 프로필이 점점 화려해진다는 걸 알고 나서... 
나도 만들어야 겠다는 결심을 하게 됨..
근데... 뭔가 어찌 만들어야 하는지 잘 모르겠는거야..

뭔가 나만 모르는거 같아서....
열심히 리서치를 통해서 + 수업을 통해서 알게된 사실..!!!

git readme를 고정해서 꾸미는 방법은.. 

###   본인 닉네임으로 repository를 생성을 한다

필자의 경우는 Minseo-Ming으로 설정을 해뒀기 때문에.. 레포를

### MinSeo-Ming으로 설정을 하고 생성을 했다.

![](https://images.velog.io/images/ccmmss98/post/98aa936d-1bf0-45ae-b95b-6488c0f6b771/image.png)

그래서 저기에 보이는데로 적으면!![](https://images.velog.io/images/ccmmss98/post/950fe286-9211-4511-8abe-0173fea62ed4/image.png)
이렇게 레포가 생성이 된다. 여기서 중요한 점

### 꼭 README file에 대해서 체크를 하고 생성을 해야한다.

그리고 보인 깃 메인 화면으로 돌아오면

![image-20210707212949597](C:\Users\minseo\AppData\Roaming\Typora\typora-user-images\image-20210707212949597.png)

이런식으로 생성이 되는 것을 확인 할 수 있다.

여기서 이것저것 다양하게 적는 사람도 많고 줄글로 적어서 본인 github.io링크도 걸어놓는 사람들도 있다. 하지만 필자는 정리할 포트폴리오도 있고 하지만... 현재는 간단하게 

- 내가 할줄 아는 기술 stack

- 현재 하고 있는 공부 or 할 예정인 공부
- 써본 개발을 위한 협업 tool들
- Gmail 연락하기 위해서
- 그리고 깃상태
- 추가로...(?) 백준 알고리즘 과 연동된 sloved.ac랭킹과 관련되어서 꾸민것들을 보여주려고한다.  
- ~~현재 상태에선 뭔가 위치가 애매하게 않맞아서 여기선 설명만하겠다.~~



## 그리고 이것이 내가 현재 꾸민 상태의 깃 화면이다.



![image-20210707213610736](C:\Users\minseo\AppData\Roaming\Typora\typora-user-images\image-20210707213610736.png)

----



일단 내가 사용한건

### 1. git emoji

 https://gist.github.com/rxaviers/7360908

이 페이지에서 가져오는게 가장 좋았어서 참고사항으로 넣는다. 

넣는 방법은 어렵지 않은데 그냥 :heart: `:heart:` 이런식으로 작성을 하면 바로 들어간다. 참고로 필자는 :seedling: `:seedling:`, :hammer: `:hammer:` :muscle: `:muscle`  :mailbox: `:mailbox:`이렇게 네가지 정도만 사용했지만 다양하니 



~~git commit 메세지나 read me  나 .md파일을 사용할 수 있는 데에선 사용해보는 걸 추천한다..!~~

~~추천만 하는 이윤 필자도 아직 readme밖에 안써봤기 때문이다..~~



### 2. 프로필 헤더

필자는 이걸 적용했다가 이름이(?) 너무 강조 되는 것 같아서...

 사용했다가 철회를 했지만 원하는 사람이 있다면?? 써보는 것도 나쁘지 않을듯하다. 

https://github.com/kyechan99/capsule-render

이곳에 가면 사용방법이 나와 있으나 예시를 들면

 ![header](https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=hello%20everyone&fontSize=90)

이런식으로 나오는데 코드는

`![header](https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=hello%20everyone&fontSize=90)`

저 깃에 가면 좀더 많은 정리가 되어 있겠지만 흔들리는 type을 변화 하고 싶음

- `app/api?type=이부분` 이부분이라 적힌 부분을 
  - wave
  - egg
  - shark
  - slice ...

등등으로 바꾸면 애니메이션이 바뀐다고 한다.

- `color=auto`color는 auto로 그때 그때 바뀌는데 원하는 색상이 있다면 색상코드를 hexcode로 바꿔서 넣으면 그색으로 고정이 된다. 대표적인 색들이 있지만 ... 뭐 auto도 나쁘지 않다고 생각한다.

- 높이를 바꾸고 싶으면 height부분을 `&height=300`  300을 다른 숫자로 바꿔주면 될 듯 싶다. 
- section부분을 건들이면 아마`section=header` 고정되는 위치가 달라 질듯 싶으나... ~~느낌상 header가 가장 좋을 듯 싶다.~~
- `&text=hello%20everyone` 이제 가장 중요한 글인데 이때 중요한건 공백은 `%20`으로 해줘야 공백으로 나타난다. 글자 크기는 `fontSize=90` 이부분중 90을 바꿔주면 된다. 



자세한건 저 깃에 가면 잘 적혀 있으니 보고 바꾸면 좋다!



### 3.  Simple Icons & Shield.io 

이건 뭔지 궁금해할거 같은데

![image-20210707215541946](C:\Users\minseo\AppData\Roaming\Typora\typora-user-images\image-20210707215541946.png)

이걸 만드는 방법이다. 본인이 처음부터 끝까지 만들 수 있지만... 필자는 

`<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white" />`

이런식으로 만들었다. 

링크가 궁금한 분들은 **shield.io** 는 https://shields.io/ 이고, **Simple** **Icons** 은 https://simpleicons.org/ 여기이다.

simple Icons에만 들어가서 배경색을 가져와서 진행했다.

위의 html5는 완성본의 예시 일뿐 틀은

`<img src="https://img.shields.io/badge/기술 이름-배경색?style=flat-square&logo=기술 이름&logoColor=white" />`

이구조로 진행했다. 배경색은 Simple Icons에 가면

![image-20210707220022518](C:\Users\minseo\AppData\Roaming\Typora\typora-user-images\image-20210707220022518.png)

이런식으로 이름을 검색해서 배경색을 가져올 수 있다. 저 #E34F26부분을 클릭해서 복사하여 가져와서 복붙하여 하나하나 완성을 하여 만들었다.



### 3-1. 메일 링크

아 적다가 안 사실이... 5가지 인데 곁다리로 1가지 더 적어야 한다는 사실이 생각이 났다....ㅋㅋㅋㅋㅋㅋㅋ바로 링크 거는건데 일반 링크보단

![image-20210707221313713](C:\Users\minseo\AppData\Roaming\Typora\typora-user-images\image-20210707221313713.png)

필자의 페이지에 가서 gmail을 누르면 mail로 연동이 될텐데.... 필자가 이걸 적으려다가 놀라운 사실을 알게되었는데...

ㅋㅋㅋㅋ 필자는 이 블로그를 쓰기 전까지 저 gmail버튼을 누르면 필자에게 바로 g-mail을 보낼 수 있도록 설정을 해뒀던것이다..ㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋ 혹시 참고할 사람들은 코드를 남겨둔다.

`<a href="https://mail.google.com/mail/?view=cm&amp;fs=1&amp;to=지메일 주소" target="_blank">  </a>`

그렇지만 이게 아닌 그저 메일로 연락을 하고 싶다 하는 사람들은

`<a href="mailto:이메일 주소" target="_blank"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logoGmail&logoColor=white" ></a>`

이렇게 진행하면 된다.

### 4. git status표현

이는 마지막에 존재하는 것은 내 github에 대한 사항이다.

![image-20210707220234475](C:\Users\minseo\AppData\Roaming\Typora\typora-user-images\image-20210707220234475.png)

이부분인데 이것또한 오픈소스로

https://github.com/anuraghazra/github-readme-stats

이곳에 가면 적용방법이 잘 나와있고 버전이 여러가지 이므로 주의가 필요하다.

잘읽어보면 커스텀마이즈도 가능하지만... 필자는 굳이 진행하지는 않았다... 

필자의 버전은 `![여러분의 이름's GitHub stats](https://github-readme-stats.vercel.app/api?username=여러분의 닉네임(이름)&show_icons=true&theme=radical)`

이렇게 사용하면 필자와 같은 화면이 나온다. 필자 것을 제외하고도 아래에 보면 여러가지 종류가 나오는데 원하는 걸로 `theme`에서 바꿔쓰면 될 듯하다.

![image-20210707220455718](C:\Users\minseo\AppData\Roaming\Typora\typora-user-images\image-20210707220455718.png)

### 5. Solved.ac 랭크

필자는 꾸미다 보니 뭔가 배치가 맞지 않는다는 걸 알게되어서 버렸지만.. 백준 알고리즘을 잘 푸는 사람들의 경우 배지를 차는 것도 나쁘지 않다고 판단된다.

일단 이 배지를 보여주기에 앞서서... 중요한것이 백준과 solved.ac가 연동이 되어 있는지 판단을 해야한다. ~~물론 그전에 백준 아이디가 있어야하겠지만~~  연동하는 방법은 어렵지 않으니 solved.ac 링크를 남기겠다. 가입(?)하고 백준을 연동하고 다시 컴백 하길!

https://solved.ac/

이것또한 https://github.com/mazassumnida/mazassumnida 주소에 가면 자세히 나와있다.

그러나... 가기 싫은 귀차니즘들을 위해서 내가 사용한 이팩트를 보여주겠다.

![image-20210707220931800](C:\Users\minseo\AppData\Roaming\Typora\typora-user-images\image-20210707220931800.png)

`[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=백준아이디)](https://solved.ac/백준아이디/)`

이렇게만 한다면 본인의 랭크가 보일것이다. ~~사진이 길어서 gold와 silver bronze는 가져오지 않았음을 참고 바란다. 궁금하면 git페이지에 가서 확인하길~~



이상으로 다 적었습니다... 라고 하면 답답해할거 같아서 필자의 스크립트를 필자 정보를 제외하고 올리겠다. 많은 참고가 되길 바라며...



## 스크립트

필자의 스크립트 이지만 원하는 데로 바꿔서 사용하라

``` python
###  :muscle:Skills

<p align ="center">
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=MongoDB&logoColor=white" />
<img src="https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=C&logoColor=white" />
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=C++&logoColor=white" />
<img src="https://img.shields.io/badge/JAVA-007396?style=flat-square&logo=JAVA&logoColor=white" />
<img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=Android&logoColor=white" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=OpenCV&logoColor=white" />
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=Flask&logoColor=white" />
<img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=Django&logoColor=white" />
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=Jupyter&logoColor=white" />
<img src="https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jQuery&logoColor=white" />
<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=jQuery&logoColor=white" />
<img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white" />


### :seedling: Studying

<p align ="center">
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=Kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=AWS&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=Node.js&logoColor=white" />
    

###  :hammer:Tools


<p align ="center">
<img src="https://img.shields.io/badge/Slack-E34F26?style=flat-square&logo=HTML5&logoColor=white" />
<img src="https://img.shields.io/badge/Trello-0052CC?style=flat-square&logo=Trello&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logoGitHub&logoColor=white" />

![여러분's GitHub stats](https://github-readme-stats.vercel.app/api?username=여러분의 깃 닉네임&show_icons=true&theme=radical)





###  :mailbox: Contact

<a href="mailto:여러분의 지메일주소" target="_blank"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logoGmail&logoColor=white" ></a>
```


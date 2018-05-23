### 전체적인 과정
레시피 박스 만들기! 음식 사진도 굉장히 먹음직스럽도록 hover를 사용하였다. 그리고 작성, 수정시에 ingredient와 description을 기입할 수 있게 하였다.
### 새로 안 내용
haml으로 작성하면서 되게 신기했다. 매우 친숙해진다면 간편하겠지만, 잘 모르는 상태에서 무턱대고 쓰다가는 엄청 꼬일 것 같다. 그럼에도 편리한 내용임에는 틀림없다.
### 오류 내용
1. 인덱스 파일을 index.html.erb로 만들어놓고 

```@recipe.each do |recipe|
  %h2= link_to recipe.title, recipe```

왜 적용이 안 될까 한참 생각했다..

2. haml는 들여쓰기가 상속을 결정하는데, 잘 모르던 때.. 삐뚤빼뚤 배열될까 고민했었다.
3. paperclip 사용이 계속 되지 않았다. imagemagic이 필요하다는데.. 어떻게 구할지 갈피를 못 잡았다. 
    그러던 중 http://robmclarty.com/blog/how-to-install-image-magick-and-setup-paperclip의 도움을 받아서
    마침내 paperclip을 사용할 수 있게 되었다.
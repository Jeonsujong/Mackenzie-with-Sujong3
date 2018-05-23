index.html.erb로 만들어놓고 

- @recipe.each do |recipe|
  %h2= link_to recipe.title, recipe

왜 적용이 안 될까 한참 생각함

haml는 들여쓰기가 상속을 결정함 이걸 모르고 왜 난 디자인이 저렇게 되지 고민했엇으
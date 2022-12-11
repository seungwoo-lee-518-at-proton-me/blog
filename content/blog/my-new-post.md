+++
title = "Blog 를 만들었다."
date = "2022-12-11T17:06:45+09:00"

description = "블로그를 만든 이야기"

tags = ['blogging']
+++

귀차니즘으로 블로그같은거 안하고 ~~정리할게 없어서 그렇~~ 크롬 탭만 여러개 열어놓고
지내고 있었는데, 겨울이 되고 (바쁘긴 하지만) 최근에 읽었던거 정리해두려고 하는 용도로
블로그를 만들었다.

원래는 Google 의 Blogger 을 사용했었는데, `최소한의 귀찮음` 만 갖고 `마크다운이 지원되는`
블로그는 뭐가 있을까 하고 찾아보다가 [Hugo](https://gohugo.io) 를 사용해서 Github Pages 에
그냥 Publish 해버리는게 제일 좋을 것 같다는 생각이 들어서, 한번 만들어봤다.

처음에 [QuickStart](https://gohugo.io/getting-started/quick-start/) 문서를 보면서 이것저것
따라해봤으나, Git Submodule 을 추가하지 않고서는 하나의 Repository 에서 작업하기 불편한 구조가
될 것 같아서, 다른 분들 글 보면서 다시 `Init` 하고, [`hugo-bearblog`](https://themes.gohugo.io/themes/hugo-bearblog/)
테마를 추가해서 설정하고 올려보니 잘 돌아가는 것 같다.

여기에 뭘 담아볼지는 고민해봐야 할 것 같지만, 주로 이것저것 읽었던 것들이나 정리해봐야 되겠다.
최근에 `linux namespacing` 을 활용한 컨테이너 구현... 을 [lwn.net#531114](https://lwn.net/Articles/531114/)
에서 봤던 것 같은데, 시간이 나면 `Golang` 으로 구현해보면서 블로그 글을 써보면 좋을 것 같다.

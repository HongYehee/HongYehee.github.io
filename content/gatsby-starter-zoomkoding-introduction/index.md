---
emoji: 🧢
title: 쉽고 빠르게 나만의 개츠비(Gatsby) 블로그 만들기
date: '2021-03-22 23:00:00'
author: 줌코딩
tags: blog gatsby theme 개츠비 테마
categories: 블로그 featured
---

## ✍️ 글 쓰기

본격적으로 블로그에 글을 쓰려면 `/content` 아래에 디렉토리를 생성하고 `index.md`에 markdown으로 작성하시면 됩니다.

> 이 때, 폴더의 이름은 경로를 생성하는데 됩니다.

### 🏗 메타 정보

index.md 파일의 상단에는 아래와 같이 emoji, title, date, author, tags, categories 정보를 제공해야 합니다.

> emoji는 글머리에 보여지게 되며, categories는 띄어쓰기로 나누어 여러개를 입력할 수 있습니다.

```
---
emoji: 🧢
title: Getting Started
date: '2021-03-22 23:00:00'
author: 줌코딩
tags: tutorial
categories: tutorial
---
```

### 🖼 이미지 경로

글에 이미지를 첨부하고 싶으시다면 같은 디렉토리에 이미지 파일을 추가하셔서 아래와 같이 사용하시면 됩니다.

```
![사진](./[이미지 파일명])
```

### 🔍 목차 생성

글의 우측에 목차가 보이기를 원하신다면 `index.md` 파일 맨 아래에 다음 내용을 추가하시면 자동으로 목차가 생성됩니다.

    ```toc
    ```

```toc

```

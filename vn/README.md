# Front end training path

> Tạo document chung để training những bạn thực tập sinh có định hướng Front end.

## Table of Contents

1. Git / Github.
2. HTML / SCSS.
3. Javascript.
4. Vue / React.
5. Config simple Fe Project - optional.

## Git / Github (3 ngày)
* Nắm được kiến thức cơ bản về Git, cách quản lý source code.
* Phân biệt được Git / Github.
* Xử lý những vấn đề thường gặp khi sử dụng Git.

#### Git / Github
Tài liệu: Xem tại trang chủ [Git](https://git-scm.com/book/en/v2).

Những vấn đề cần phải nắm được:
```
Git là gì? Github là gì? Remote là gì?
Khởi tạo Github repository?
Cách init Git?
Những trạng thái của file: tracked (unmodified, modified, staged) và untracked?
Giải thích được các lệnh: clone, pull, push, checkout, branch,...
Conflict là gì? Cách xử lý khi bị conflict?
```

## HTML / SCSS (2 tuần)
### Lựa chọn Text Editor
```
Hướng dẫn lựa chọn và cấu hình text editor. (Recommend: VSCode, Atom).
```

### HTML
Tài liệu: [HTML](https://www.w3schools.com/html/).

Những vấn đề cần phải nắm được:
```
Những html tag cơ bản: p, a, span, div, h1..h5, ul, ol, img,...
Sematic tag là gì? Tại sao phải sử dụng sematic tags?
Thuộc tích trong <head>: descriptions, og-descriptions, title, og-title, keywords, og-keywords...
Tìm hiểu thêm về template engine.
BEM là gì? Tại sao nên dùng BEM?
SEO là gì? Có những cách nào để tối ưu SEO?
```

### SCSS
Tài liệu: [CSS](https://www.w3schools.com/css/).
          [SCSS](https://sass-lang.com/documentation/syntax).

Những vấn đề cần phải nắm được:
```
Thuộc tích cơ bản của css?
Phân biệt inline, inline-block, block, table, table-cell,...
Phân biệt position: relative, absolute, fixed?
Box-sizing: border-box or content-box?
Thế nào là responsive web? Phân biệt mobile first và web first?
....
Scss là gì? Tại sao phải sử dụng Scss?
```

### Practice
* Lưu ý: Follow [this](https://github.com/nhithaivn/coding-guideline). , đọc coding styleguide html/css.
* Clone [this](https://github.com/nhithaivn/gulp-config).
* Yêu cầu: Code template hiển thị CV của bản thân.
* Được sử dụng: Boostrap, Bulma, Spectre.

## Javascript (2 tuần)
### Javascript
Tài liệu: [Javascript](https://javascript.info).

Những vấn đề cần phải nắm được:
```
Data types
Objects
Operators
Conditional
Loop
Function
Modules
Prototypes, inheritance
```

[Es6/Es2015](https://www.freecodecamp.org/news/write-less-do-more-with-javascript-es6-5fd4a8e50ee2/).
Những vấn đề cần phải nắm được:
```
Syntax
Import, export
```
### Practice
Sử dụng template cũ, viết thêm 1 page sử dụng javascript hiện thực `todo app`. Template và function tham khảo ở [đây](http://todomvc.com/examples/backbone/).

### Next level

```
Tìm hiểu về Callback, promises, async/await?
Tìm hiểu về api? Tại sao sử dụng api?
RESTful api là gì? Tìm hiểu axios và fetch?
```

### Practice
Sử dụng [mock api](https://www.mockapi.io). để tạo fake api cho `todo app`. Sử dụng axios hoặc fetch để call api.

## Vuejs (2 tuần)
### Vuejs
Tài liệu: [Vuejs](https://vuejs.org).
          [Video](https://www.udemy.com/course/vuejs-2-the-complete-guide/learn/lecture/13914128#overview).

### Những vấn đề cần nắm được:
```
Làm cách nào để khởi tạo một dự án với Vuejs?
Nắm được syntax căn bản của Vue: Declarative Rendering, Conditionals, Loops,...?
Vue instance là gì? Thế nào là MVVM pattern?
Nắm được data, method, computed, watch?
Lifecycle Hooks?
Nắm được template syntax: Interpolations, Directives, Shorthands; Event/List/Conditional Handling?
Props, Slots?
Minxis and Custom Directive?
```

### Vue Router
Tài liệu: [Vue Router](https://router.vuejs.org).

### Practice
Đọc [styleguide](https://vuejs.org/v2/style-guide/).
Clone [this teamplate](https://github.com/gothinkster/realworld-starter-kit/blob/master/FRONTEND_INSTRUCTIONS.md).
Sử dụng props và router cắt nhỏ component và chia page.

### Vuex
Tài liệu: [Vuex](https://vuex.vuejs.org).

### Những vần đề cần phải nắm được:
```
Vuex là gì? Tại sao cần phải sử dụng Vuex?
One-way data flow trong Vuex
Nắm được thành phần trong Vuex: State, Getters, Mutations, Actions?
Vuex Structure và cách setup.
```

### Practice
Sử dụng teamplate đã viết
Sử dụng [api](https://github.com/gothinkster/realworld/tree/master/api). để hoàn thiện app

### Advance
```
Viết test cho Vue app
Server side Rendering bằng Nuxtjs
```
# Programming Languages

*본 스터디의 계획서 및 내용, 과제는 [고려대학교 소프트웨어 분석 연구실 오학주 교수님](http://prl.korea.ac.kr/~pronto/home/)의 프로그래밍언어 수업을 바탕으로 하고 있음을 밝힙니다.

## Logistics
- Tutor: [Jaeho Kim](https://oojahooo.github.io) (oojahooo@gmail.com)
- Time: 매주 수, 목 오후 4시 ~ 5시 반
- Location: 정보관 (대면, 자세한 장소는 확정 후 공지 예정)

## Abstract
프로그래밍 언어는 왜 언어일까?

어떤 나라의 언어를 이해한다는 것은 그 나라의 문화, 역사, 사람들의 의식을 공유할 수 있게 된다는 것이라고 한다.
프로그래밍 언어를 이해한다는 것 역시, 그 언어를 만들게 된 배경과 만든 사람들의 신념, 의도, 또 개발자들이 그 언어를 사용하는 이유까지 알 수 있게 되는 과정이다.
그리고 이해의 끝에는 컴퓨터와 내가 서로 완벽히 호응하는 몰입의 순간이 찾아온다.

그러나, 당신은 프로그래밍 언어를 어떻게 대하고 있는가?
다듬어지지 않은 코드로 컴퓨터와 유저들에게 상처를 주고 있진 않은가?
어떻게든 돌아가면 된 게 아니냐는 얄팍한 생각에 100만원을 훌쩍 넘기는 컴퓨터에게 몹쓸 명령을 하고 있지는 않은가?

언어에는 문법과 의미가 있다.
알맞은 문법을 사용해야 컴퓨터가 이를 알아들을(compile) 수 있을 것이며, 문법이 알맞더라도 내가 의도한 대로 컴퓨터가 이해(evaluate)하고 이행하기 위해서는 그 의미를 해석(interpret)할 수 있어야 할 것이다.
이제 우리는 아주 간단한 프로그래밍 언어를 컴퓨터가 해석할 수 있도록, 인터프리터라고 불리는 프로그램을 설계할 것이다.
그 과정에서 알아야 할 이론적 배경을 배우며, 프로그래밍 언어를 만들고 사용한다는 것의 명쾌함과 아름다움을 향유할 수 있었으면 한다.

(*주의: 본 스터디는 코드를 잘 짜는 방법에 대해 알려주지 않습니다. 다만 프로그래밍 언어의 구조를 이해함으로써 코드를 잘 짜는 데에 큰 도움이 될 것입니다.)

## References
- [Essentials of Programming Languages](https://www.amazon.com/gp/product/0262062798?ie=UTF8&tag=ucmbread-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=0262062798)
- [Notes on Programming Languages (in Korean)](http://prl.korea.ac.kr/~pronto/home/courses/cose212/2019/pl-book-draft.pdf)

## Goal & Topics
프로그래밍 언어의 가장 기본적인 요소들에 대해 이해하는 것을 목표로 한다.
특히 프로그래밍 언어의 인터프리터를 설계하고 구현하는 과정을 공부함으로써 프로그래밍 언어를 구성하는 문법(syntax)과 의미(semantics)가 무엇이며, 정해진 규칙대로 작성된 코드가 컴퓨터에서 실행될 수 있게 되는 과정을 이해하고자 한다.
자세한 주제는 다음과 같다:

- **Preliminaries:** Inductive definition, Rule of inference, Functional programming
- **Basic Concepts:** Syntax, Semantics, Naming, Binding, Scoping, Environment, Interpreters, States, Reference, Parameter passing
- **Advanced Concepts:** Type system, Typing rules, Type checking, Soundness/completeness, Type inference, Polymorphism, Objects, Classes, Methods, Inheritance, Typed object-oriented languages

## Prerequisties
본 스터디의 내용과 과제에서는 함수형 프로그래밍을 주로 다루지만, C나 Python과 같은 언어의 기본적인 프로그래밍 스킬을 자연스럽게 할 수 있는 수준이면 좋다.

프로그래밍 과제는 모두 Ocaml을 활용할 예정이다.
대표적인 함수형 프로그래밍 언어이자 선언형 프로그래밍 언어이기 때문에 공부해 두면 인생에 큰 도움이 될 것이다.

또 아주 약간의 계산이론 내용과 이산수학 내용을 알고 있으면 도움되지만, 모르는 사람을 위해 첫시간에 관련 스터디를 진행할 예정이다.

## Assignments
본 스터디의 과제는 GitHub Classroom으로 진행될 예정이다.
이에 약간의 Git, GitHub 스킬을 가지고 있으면 좋으나 이 역시 스터디에서 충분히 따라올 수 있도록 설명할 예정이다.

구체적인 과제 내용 및 제출 방식은 스터디 첫 시간에 공지하도록 하겠다.

## Schedule (Tentative)
|Weeks|Topics|Lecture Videos|Assignments|
|:---:|:---:|:---:|:---:|
|Week 1|귀납적 구조를 정의하는 법, Ocaml 기초|[1-1](https://youtu.be/6_7SOjb13DE), [1-2](https://youtu.be/qrL-4JyL1i0)|[Assignment 1](https://classroom.github.com/a/-ZucFpOD)|
|Week 2|OCaml을 활용한 함수형 프로그래밍|[2-1](https://youtu.be/54rwCzb0Qxg), [2-2](https://youtu.be/xz5mTx20LF0)|[Assignment 2](https://classroom.github.com/a/m7O-j0zq)|
|Week 3|인터프리터 만들기: 식(Expressions), 함수(Procedures)|[3-1](https://youtu.be/9SrQGQ0G54Y), 3-2||
|Week 4|인터프리터 만들기: 재귀함수(Recursion), 유효범위 규칙(Scoping Rules)|4-1, 4-2|[Assignment 3](https://classroom.github.com/a/FhJhhdbN)|
|Week 5|인터프리터 만들기: 상태(States), 포인터(Pointers)|5-1, 5-2|Assignment 4|
|Week 6|더 나은 인터프리터 만들기: 간단한 타입 체계(Type System)|6-1, 6-2||
|Week 7|더 나은 인터프리터 만들기: 타입 추론(Type Inference)|7-1, 7-2|Assignment 5|
|Week 8|마무리: 람다 칼큘러스(Lambda Calculus), 그래서 왜 PL인가?|8-1, 8-2||

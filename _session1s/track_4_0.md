---
layout: session1
order: 3
title: "CloudEvents 소개 - 상호 운용 가능성을 극대화한 이벤트 데이터를 정의하는 새로운 포맷"
track: Track 4
time: "13:20 ~ 13:50"
duration: 30분
speakers:
  - name: 유정협 (Justin Yoo)
    org: Mexia Consulting
    desc: 
    image: ../assets/imgs/유정협.png
---

## 제목
- 한글: "CloudEvents 소개 - 상호 운용 가능성을 극대화한 이벤트 데이터를 정의하는 새로운 포맷"
- English: "CloudEvents – A Common Way of Describing Events by CNCF"

## 개요

클라우드, 온프레미스를 가리지 않고 시스템에서는 항상 이벤트가 발생합니다. 그런데, 이러한 이벤트들을 묘사하는 방식은 모두가 다 다릅니다. 이렇게 이벤트를 정의하는 방식이 다 다르고 공통의 표준이 없었기 때문에, 개발자들은 새로운 이벤트가 생기면 그에 따라서 다시 뭔가를 공부하고 기존의 방식에 적용시켜야 합니다. 아주 비싸지요. 이것은 또한 이벤트 데이터를 전달하는데 필요한 라이브러리, 툴, 인프라스트럭처를 준비하는데 있어서도 큰 걸림돌입니다. 덕분에 전체적인 생산성은 그만큼 줄어들 수 밖에 없습니다.

CloudEvents 는 이러한 고민의 결과로서 만들어진, "공통의 이벤트 데이터 포맷"을 정의하는 스펙입니다. 이를 적용한다면 플랫폼에 상관없이, 시스템에 상관없이, 서비스에 상관없이 이벤트 데이터를 전송할 수 있게 됩니다.

이 세션에서는 CNCF의 서버리스 워킹 그룹 주도 아래 만들어지고 있는 이 CloudEvents 에 대해 알아보고 실제 현장에서 어떻게 적용되고 있는지 간단한 사례와 데모를 통해 보여줍니다. 이 세션이 끝난 후 CloudEvents 가 클라우드 서비스 제공자 사이에서 어떻게 적용되고 있는지 알 수 있고, 자신이 운용하는 시스템에는 어떻게 적용시킬 수 있는지 알 수 있게 됩니다.

## Abstract

Events occur everywhere. But event publishers describe those events differently. There has been no way describing events in a common way, which make developers in their hard time to constantly re-learn how to consume events.

CloudEvents is an open spec for event data driven by CNCF (Cloud Native Computing Foundation) and many industry vendors, including Azure, AWS, CGP, IBM and OpenStack, take part in setting up the spec. Any application implementing and/or consuming webhook can introduce this spec and Azure Event Grid is one of them.

At the end of this session, audiences will learn 1) what CloudEvents spec is, 2) how it can be implemented, 3) how Azure Event Grid copes with CloudEvents, and 4) How other popular platforms can redesign their events.
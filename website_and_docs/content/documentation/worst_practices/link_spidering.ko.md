---
title: "링크 이동"
linkTitle: "링크 이동"
weight: 7
aliases: ["/documentation/ko/worst_practices/link_spidering/"]
---

WebDriver를 링크를 통해 이동하는 것은 권장되는 연습이 아니다. 
할 수 없어서가 아니라, WebDriver가 확실히 이것에 가장 이상적인 도구가 아니기 때문이다.
WebDriver를 시작하는 데 시간이 필요하며 최대 1분까지 몇 초 정도 걸릴 수 있음
시험이 어떻게 작성되느냐에 따라, 그냥 페이지로 가서 DOM을 통과한다.

[curl](//curl.haxx.se/)명령어를 실행하거나, BeautifulSoup과 같은 라이브러리를 사용함으로써, 
browser를 만들고 페이지로 이동하는데 의존하지 않는 방법이기에 WebDriver를 사용하는 것보다 
더 많은 시간을 절약할 수 있다. 당신은 이 작업에 WebDriver를 사용하지 않음으로써 많은 시간을 절약하고 있다.
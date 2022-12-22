---
description: 하나의 큰 작업을 여러 개의 core를 사용해서 병렬로 처리하고 싶은 경우
---

# Multiprocessing

일반적으로, 단순히 하나의 함수로 작업을 진행하면 일반적으로CPU에서 1개의 core로 작업이 진행된다. 만약 적당한 크기의 데이터라면 1개의 core로 작업해도 기다릴 만한 수준의 시간이 소요되겠지만, 하나의 큰 데이터에 대해서 분석을 진행하고 싶을 때에는 너무 많은 시간이 소요될 수 있다. 이런 경우에는 많은 core를 한번에 사용해서 병렬로 작업을 진행하는 것이 유리할 수 있다. 이 때 사용되는 패키지가 바로 multiprocessing이다.&#x20;

[Mnutiprocessing](https://docs.python.org/ko/3/library/multiprocessing.html#module-multiprocessing)은 기본 내장 패키지이기 때문에 별도의 설치가 필요 없다. 바로 python 코드에서 아래와 같이 불러오는 것이 가능하다. 여기서는 편의를 위해 mp로 지정하였다.

```
import multiprocessing as mp
```








# D-Day 확인하기 AWS 배포

## 소개

기존의 D-Day 확인하기를 AWS로 배포한 것입니다.

배포는 다음 링크에서 했습니다. -> [링크](http://3.35.13.146)

기존의 [D-Day 확인하기]는 다음 링크에서 확인하실 수 있습니다. -> [링크](https://github.com/bada3670/d-day-checker)

## 사용한 서비스 및 동작 원리

다음 서비스들을 사용하였습니다.

EC2, RDS

RDS에서는 MySQL을 운영하고 있고, EC2에서는 client와 server를 운영하고 있습니다.

client는 webpack의 dev-server를 사용하고 있고, server는 express를 사용하고 있습니다.

EC2에서 터미널을 꺼도 운영이 될 수 있게 리눅스의 screen을 사용하고 있습니다.

## 참고자료

Vite를 활용해서 서비스를 배포하는 방법을 유튜브로 올렸습니다. 해당 서비스와 유사하여 링크를 남깁니다. -> [링크](https://youtu.be/P5RSa9RUPKA)

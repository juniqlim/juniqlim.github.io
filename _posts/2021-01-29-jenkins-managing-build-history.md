# 젠킨스 빌드 기록 관리

회사에서 젠킨스를 사용하고 있는데, 점점 느려졌다.
빌드 기록들이 들어나면서 점점 느려지는 것 같아서 구글링을 해봤다.
한글로된 자료가 없어서 한참을 찾았는데 영어로 검색하니 금방 나왔다. 진작에 영어로 검색할껄..

https://plugins.jenkins.io/build-discarder/

##### 1.Jenkins 관리로 가서

<kbd><img width="248" alt="스크린샷 2021-01-29 오전 11 22 39" src="https://user-images.githubusercontent.com/15120049/106230790-a241af80-6233-11eb-8531-2605f397b7b7.png"></kbd>
![alt-text](https://user-images.githubusercontent.com/15120049/106230790-a241af80-6233-11eb-8531-2605f397b7b7.png){:.border}


##### 2.스크롤 내려보면 Global Build Discarders 항목이 보임. add 눌러서 Specific Build Discarder를 선택

<kbd><img width="460" alt="스크린샷 2021-01-29 오전 11 23 00" src="https://user-images.githubusercontent.com/15120049/106230793-a2da4600-6233-11eb-9500-323897b6bf0c.png"></kbd>


##### 3.빈칸에 적당한 값을 넣어준다.

<kbd><img width="1087" alt="스크린샷 2021-01-29 오전 11 25 08" src="https://user-images.githubusercontent.com/15120049/106230798-a40b7300-6233-11eb-84ed-ad9235574d25.png"></kbd>


설정하고 나니 빨라진 느낌이다. 적당한 설정값은 아직 모르겠다.

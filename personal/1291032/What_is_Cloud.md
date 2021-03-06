##What is Cloud?

###클라우드 컴퓨팅
과거에는 사진을 컴퓨터와 휴대폰과 같은 저장소에 저장해 놓아야만 했다. 하지만 클라우드를 이용하면, 인터넷 공간 어딘가에 (보통 기업이 제공하는 인터넷 공간상의 저장소) 내 이름 밑으로 사진을 저장해 놓고, 언제든지 어디든지 인터넷만 연결되어 있다면, 인터넷 저장소에 접속하여, 내 사진을 볼 수 있다.

사진을 저장하는 것 이외에도, 기업이 제공할 수 있는 다양한 서비스, 심지어 어플리케이션을 개발하는 일까지, 클라우드 방식은 점점 더 발전하고, 다양한 영역에 스며들고 있다.

클라우드는 크게 다음의 3가지로 분류할 수 있다.

###1. IaaS (Infrastructure as a Service)

어떤 서비스가 있다. 이 서비스는 여러 사람이 동시에 인터넷을 통해 사용하고, 정보를 공유한다. 이런  경우 여러사람이 사용하기 때문에 '서버'가 필요하다. 서버를 통해 서로 정보를 주고 받기도 하고 개개인이 필요한 정보를 서버로부터 받을 수도 있다.

이전에는 어떤 서비스를 하기 위해서는 서버도 직접 설계하고 구축해야 했는데, 최근에는 클라우드를 이용해 서버를 좀 더 쉽게 구성할 수 있게 되었다. IaaS는 서버를 운영하기 위해 필요한 자원 (서버 자원, IP, 네트워크, 스토리지), 밑 바탕을 쉽고 편하게 이용할 수 있는 서비스를 제공하는 것을 말한다. 뒤에서 말할 PaaS와 SaaS의 기반이 되는 기술이기도 하다.

주로 어떤 어플리케이션을 만들거나 서비스를 하기 위해, 그것을 처음부터 구성하고 설계하는 일을 하는 사람이 이 서비스의 주요 대상이다.

* Amazon, E2C (Elastic Computing Cloud)
* 이노그리드, Cloudit /  서버 자원을 필요한 만큼 빌려서 사용할 수 있는 서비스

###2. PaaS (Platform as a Service)

대부분의 어플리케이션은 인터넷을 필수적으로 이용하고, 그러기 위해서는 거의 필수적으로 서버를 필요로 한다. PaaS는 개발자가 서버에 신경을 덜 쓰게 해준다. 개발자가 만들고자 하는 어플리케이션 개발에 좀 더 집중할 수 있도록 안정적인 환경을 제공한다. 또한, 그 환경 위에서 동작하는 어플리케이션을 좀 더 쉽게 만들 수 있도록 기본 틀(API)을 제공하기도 한다.

어플리케이션 개발자가 PaaS의 주요 서비스 대상이다.

* Google App Engine (GAE)
* Salesforce, Force.com
* KT, Ucloud

###3. SaaS (Software as a Service)

SaaS는 일반 사용자를 대상으로 한다. 아까 맨 처음에 언급한 '사진을 저장하는 인터넷 공간'도 SaaS의 작은 부분이라고 할 수 있다. 하지만 실제적으로 SaaS는 단순히 파일을 클라우드에 저장하는 것만을 의미하지는 않는다.

정학히 SaaS는 클라우드 환경에서 동작하는 어플리케이션을 서비스하는 것이다. Gmail을 예로 들면, 실제로 메일을 보내고, 받고, 스팸을 차단하는 일은 구글의 서버에서 일어나고, 사용자는 그 결과를 인터넷을 통해 보기만 한다. 다시 말해서 사용자는 이 시스템이 무엇으로 이루어져 있고, 어떻게 동작하는지 전혀 알 수 없다.

* Google, Gmail
* Salesforce, CRM
* KT, bizmeka

###* BaaS (Backend as a Service)

BaaS는 위에서 말한 세가지 클라우드와는 조금 다른 개념이다. 결론부터 말하자면, BaaS는 모바일 서비스에 최적화된 클라우드 서비스이다. 모바일 앱을 개발할 때, 자주 사용하는 백엔드 기능을 표준화, 추상화 하여 기본 틀(API)의 형태로 제공한다.

많은 사람들이 모바일을 통해 다양한 서비스를 이용하고, 모바일을 통해 할 수 없는 것을 찾기가 더 힘들어졌다. 아직 이 기술이 나중에 크게 성장할지 여부는 확실하지 않지만, 현재의 뜨거운 화두인 것은 확실한 듯 하다.

* Salesforce,
* KT, baas.io


-----------------------------------------------------------------------
**Backend,**

온라인 서비스는 사용자가 보는 프로그램(front-end), 관리자가 보는 프로그램(back-end)로 나뉜다. 인스타그램의 경우, 사진을 저장할 공간, 그 공간을 관리하는 기능 등등을 쉽게 사용하도록 서비스하는 것이 BaaS

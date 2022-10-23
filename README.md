# WIL(Weekly I Learned)
<details>
<summary>221016(MON) ~ 1023(SUN)</summary>
<div markdown="1">
<hr/>
  
##### Learned : ORM 데이터베이스 관계, 스프링 좋아요 기능 구현
##### Weekly
프론트엔드와의 협업 과제 전, 백엔드 마지막 과제를 끝냈다. 기존 CRUD, JWT로그인 구현 및 추가적으로 **좋아요기능**을 구현하는데 
  
초점을 맞췄던 한 주, 3주간의 스프링 주특기 주가 끝난만큼 앞으로 이 토대 위에 전문적이고 딥한 탐구 및 구현력을 요망📝
  
게시글 좋아요 기능을 구현하는데 있어서, 유저와 게시글간 데이터베이스의 관계에 대해 이해하게 되었다.

금요일에는 드디어 처음으로 프론트엔드 팀원 분들과 팀을 이루어 미니프로젝트를 하게되었다. 팀이 구현할 주제 회의 및
  
FIGMA를 통한 와이어프레임 구성 등을 완료. 앞으로의 프로젝트들은 좀 더 흥미진진할듯 싶다🤝 

##### Keyword🔑 CORS?
  
CORS란 (Cross Origin Resource Sharing) 교차 출처 리소스 공유이다.  
</div>
</details>
<details>
<summary>221010(MON) ~ 1015(SUN)</summary>
<div markdown="1">
<hr/>

##### Learned : Spring CRUD, JWT, SPRING SECURITY
##### Weekly 
저번주에 진행했던 기존 CRUD에 spring **security**와 **JWT**방식을 이용한 로그인을 구현하는데 집중한 주 였다.

JWT 와 시큐리티의 인증, 인가의 복잡한 흐름이 머리속을 혼란스럽게 한다!🥶

시간이 되면 그림을 그리면서 한번 정리해볼 예정🧐

그리고 10/15 카카오 데이터 센터 화재 덕에, GITHUB로 블로그를 이전함.

마크다운 문법이 익숙하지 않지만, 역시 깃허브 쪽이 훨씬 흥미롭다.🔮
##### Keyword🔑 ORM?

**1. ORM**
(Object-Relational Mapping)

**객체와 관계형 데이터베이스의 데이터를 자동으로 매핑해주는 것을 말한다.**

객체 지향 프로그래밍은 클래스를 사용, 관계형 데이터베이스는 테이블을 사용.

▶️ 객체 모델과 관계형 모델 간의 불일치가 존재.

ORM을 통해 객체 간의 관계를 바탕으로 SQL을 자동으로 생성해서 불일치를 해결해준다.

Database Data **<-Mapping->** Object Field

Persistant API라고도 부른다. (JPA, Hibernate)

**2. ORM의 장, 단점**

**장점** : 객체 지향적인 코드로 인해 더 직관적이고, 비즈니스 로직에 집중할 수 있게 도와준다. 

SQL 쿼리가 아닌 직관적인 코드로 데이터를 조작할 수 있어 개발자가 객체 지향 프로그래밍하는데 도움을 준다. 

재사용성 및 유지보수의 편리성 증가

DBMS(Database Management System)에 대한 종속성이 줄어든다.

**단점** : 완벽히 ORM으로만 서비스 구현이 힘듬

사용하기는 편하지만 설계단계에서 신중해야하며, 프로젝트가 복잡해질 경우 난이도 상승

잘못 구현된 경우, 속도저하 및 일관성이 무너지는 문제점이 생길수 있다. 
</div>
</details>

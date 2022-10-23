# WIL(Weekly I Learned)
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

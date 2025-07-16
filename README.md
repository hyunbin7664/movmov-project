# MovMov

**MovMov**는 영화 정보 열람 및 리뷰, 굿즈/티켓 거래, 그리고 유저 간 소통 기능을 통합한 영화 커뮤니티 기반 웹 플랫폼입니다. 
본 프로젝트는 영화에 대한 다양한 정보를 공유하고, 유저 간 취향 기반의 소통이 가능하며, 굿즈 및 티켓 거래 기능을 구현하고, 고객센터를 통해 영화 팬들에게 실질적이고 안정적인 가치를 제공하는 것을 목표로 합니다.
영화 콘텐츠 중심의 커뮤니티와 커머스를 결합한 서비스로서, 사용자 경험을 고려한 UI/UX 설계와 Oracle DB 기반의 안정적인 데이터 관리, 그리고 웹 기반의 직관적인 인터페이스 구현에 중점을 두었습니다.

---

## 중심 기능

- **상품 목록 조회**
- **장바구니** (담기/수정/삭제/총합)

---

## 기술 스택

- **Backend**: Java, JSP, Servlet, MyBatis
- **Frontend**: HTML5, CSS3, JavaScript
- **Database**: Oracle DB
- **Tools**: Apache Tomcat, GitHub

---

## Commerce 주요 DB 테이블 구조

| 테이블명              | 설명                      |
|----------------------|---------------------------|
| `app_users`          | 사용자 정보 테이블        |
| `shop_items`         | 상품 정보 테이블          |
| `shop_cart_items`    | 장바구니 아이템 테이블    |

## ERD
<img width="2910" height="2352" alt="movmov-5" src="https://github.com/user-attachments/assets/3c68ec24-66fb-4d70-ac48-9157d7563eb1" />

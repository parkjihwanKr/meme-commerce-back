# 🛍️ Meme Commerce Backend

## 프로젝트 소개
**밈 커머스**는 최신 트렌드인 '밈'과 인기 캐릭터 상품을 활용하여 이모지 형태로 커스터마이징할 수 있는 독특한 기능을 제공하는 이커머스 플랫폼입니다. 웹과 모바일을 통해 서비스되며, 사용자 맞춤형 쇼핑 경험을 제공합니다.

## 🚀 기술 스택
- **Backend**: Java 17, Spring Boot, Spring Security, Spring Data JPA
- **Database**: PostgreSQL, Redis
- **인증**: JWT, OAuth2.0
- **결제**: Toss Payments
- **검색엔진**: ElasticSearch (향후 구현)
- **문서화**: Swagger
- **배포환경**: AWS (EC2, S3, CloudFront, RDS, ElastiCache, WAF)
- **CI/CD**: GitHub Actions

## 🔑 핵심 기능

### 1차 MVP
- **사용자 관리**: 회원가입, 로그인, 비밀번호 재설정
- **상품 관리**: 상품 목록 및 상세 조회
- **장바구니**: 상품 추가/삭제/수량 변경
- **주문/결제**: Toss 결제 연동, 주문 처리
- **커뮤니티**: 게시판 기능
- **재고 관리**: Redis 기반 재고 관리 및 품절 처리

### 향후 구현 기능
- 사용자 리뷰 및 평점 시스템
- ElasticSearch 기반 풀텍스트 검색
- 쿠폰 및 프로모션 관리
- 푸시 알림
- 어드민 대시보드
- 시스템 모니터링 및 로그 추적

## 🏁 시작하기

### 요구사항
- JDK 17+
- Gradle
- PostgreSQL
- Redis

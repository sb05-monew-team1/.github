 # MoNew - team1
📰 흩어진 뉴스를 한 곳에, 관심 있는 주제만 모아보세요!
모뉴(MoNew)는 다양한 뉴스 출처를 통합하여 관심사 기반으로 뉴스를 저장하는 뉴스 통합 관리 플랫폼입니다.
관심 있는 주제의 기사가 등록되면 실시간 알림을 받고, 댓글과 좋아요를 통해 다른 사용자와 의견을 나눌 수 있는 소셜 기능도 함께 제공됩니다. 🗞️💬

## 🔍 프로젝트 개요
- **프로젝트 기간**: 2025.10.17 ~ 2025.11.10
- **목표**: 관심사 기반 뉴스 통합 및 안정적인 데이터 관리 시스템 구축
- [Monew Team1 Notion](https://messy-freighter-299.notion.site/Team-1-Monew-2925223d614c8049931df3ad4cb0c16d)

## 🧑‍💻 팀원 소개
|              팀장               |                     팀원                       |                     팀원                      |                   팀원                  |                   팀원                  |
| :--------------------------------------------------------------------------: | :---------------------------------------------------------------------------: | :--------------------------------------------------------------------------: | :--------------------------------------------------------------------------: | :--------------------------------------------------------------------------: |
| <img src="https://avatars.githubusercontent.com/u/163991739?v=4" width="100"> | <img src="https://avatars.githubusercontent.com/u/217873189?v=4" width="100"> | <img src="https://avatars.githubusercontent.com/u/166792449?v=4" width="100"> | <img src="https://avatars.githubusercontent.com/u/217938046?v=4" width="100"> | <img src="https://avatars.githubusercontent.com/u/114233449?v=4" width="100"> |
| [김규섭](https://github.com/KarubiOhayo) | [김수연](https://github.com/sooyeonz) | [김준교](https://github.com/rlawnsry) | [강동민](https://github.com/DONGMIN-777) | [박윤지](https://github.com/yunji1014) |


## ⚙️ 기술 스택
### Front-end
<div align=left> 
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white">
</div>

### Back-end
<div align=left> 
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/springsecurity-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
  <img src="https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=JUnit5&logoColor=white">
</div>

### DB
<div align=left> 
  <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/h2database-09476B?style=for-the-badge&logo=h2database&logoColor=white">
  <img src="https://img.shields.io/badge/mongoDB-47A248?style=for-the-badge&logo=mongoDB&logoColor=white">
</div>

### CI/CD
<div align=left> 
  <img src="https://img.shields.io/badge/github actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
  <img src="https://img.shields.io/badge/Amazon-FF9900?style=for-the-badge&logo=Amazon&logoColor=white">
  <img src="https://img.shields.io/badge/sonarqubecloud-126ED3?style=for-the-badge&logo=sonarqubecloud&logoColor=white">  
</div>

### Collab Tool
<div align=left> 
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
  <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
</div>

## 📍 주요 기능



## 🧩 팀원별 구현 기능 상세
| 팀원 | 구현 기능 |
|------|----------|
| 김규섭 | |
| 김수연 | |
| 김준교 | |
| 박윤지 | |
| 강동민 |  |

### 🟦 김규섭

### 🟩 김수연

### 🟨 김준교

### 🟥 박윤지

### 🟪 강동민


## 📂 파일 구조
### monew-app
```
src
├── main
│   ├── java
│   │   └── com.codeit.monew
│   │       ├── MonewApplication.java
│   │       ├── activity
│   │       │   ├── controller
│   │       │   │   └── UserActivityController
│   │       │   ├── domain
│   │       │   │   └── UserActivity
│   │       │   ├── dto
│   │       │   │   └── UserActivityDto
│   │       │   ├── exception
│   │       │   │   ├── UserActivityException
│   │       │   │   └── UserActivityNotFoundException
│   │       │   ├── mapper
│   │       │   │   └── UserActivityMapper
│   │       │   ├── repository
│   │       │   │   └── UserActivityRepository
│   │       │   └── service
│   │       │       └── UserActivityService
│   │       ├── article
│   │       │   ├── controller
│   │       │   │   └── ArticleController
│   │       │   ├── domain
│   │       │   │   ├── Article
│   │       │   │   ├── ArticleSource
│   │       │   │   └── ArticleView
│   │       │   ├── dto
│   │       │   │   ├── ArticleBackupDto
│   │       │   │   ├── ArticleDto
│   │       │   │   ├── ArticleRestoreResultDto
│   │       │   │   ├── ArticleSearchRequest
│   │       │   │   ├── ArticleSearchRequestFromService
│   │       │   │   ├── ArticleSearchResultDto
│   │       │   │   └── ArticleViewDto
│   │       │   ├── exception
│   │       │   │   ├── ArticleException
│   │       │   │   ├── ArticleNotFoundException
│   │       │   │   └── ArticleViewAlreadyExistException
│   │       │   ├── mapper
│   │       │   │   ├── ArticleMapper
│   │       │   │   └── ArticleViewMapper
│   │       │   ├── repository
│   │       │   │   ├── impl
│   │       │   │   │   ├── ArticleQueryRepositoryImpl
│   │       │   │   │   └── ArticleViewQueryRepositoryImpl
│   │       │   │   ├── ArticleQueryRepository
│   │       │   │   ├── ArticleRepository
│   │       │   │   ├── ArticleViewQueryRepository
│   │       │   │   └── ArticleViewRepository
│   │       │   └── service
│   │       │       ├── ArticleService
│   │       │       └── ArticleStorage
│   │       ├── comment
│   │       │   ├── controller
│   │       │   │   └── CommentController
│   │       │   ├── domain
│   │       │   │   ├── Comment
│   │       │   │   └── CommentLike
│   │       │   ├── dto
│   │       │   │   ├── CommentActivityDto
│   │       │   │   ├── CommentDto
│   │       │   │   ├── CommentLikeActivityDto
│   │       │   │   ├── CommentLikeDto
│   │       │   │   ├── CommentLikeRequest
│   │       │   │   ├── CommentRegisterRequest
│   │       │   │   ├── CommentSearchRequest
│   │       │   │   └── CommentUpdateRequest
│   │       │   ├── mapper
│   │       │   │   └── CommentMapper
│   │       │   ├── repository
│   │       │   │   ├── impl
│   │       │   │   │   ├── CommentLikeQueryRepositoryImpl
│   │       │   │   │   └── CommentQueryRepositoryImpl
│   │       │   │   ├── CommentLikeQueryRepository
│   │       │   │   ├── CommentLikeRepository
│   │       │   │   ├── CommentQueryRepository
│   │       │   │   └── CommentRepository
│   │       │   └── service
│   │       │       └── CommentService
│   │       ├── common
│   │       │   ├── base
│   │       │   │   ├── BaseDomain
│   │       │   │   └── BaseUpdatableDomain
│   │       │   ├── config
│   │       │   │   ├── AwsProperties
│   │       │   │   ├── QuerydslConfig
│   │       │   │   └── SecurityConfig
│   │       │   ├── dto
│   │       │   │   └── CursorPageResponse
│   │       │   ├── exception
│   │       │   │   ├── storage
│   │       │   │   │   ├── StorageException
│   │       │   │   │   └── BusinessException
│   │       │   │   ├── ErrorCode
│   │       │   │   ├── ErrorResponse
│   │       │   │   └── GlobalExceptionHandler
│   │       │   ├── log
│   │       │   │   └── MdcLoggingFilter
│   │       │   └── util
│   │       │       ├── PageResponseMapper
│   │       │       └── SearchRequestNormalizer
│   │       ├── interest
│   │       │   ├── controller
│   │       │   │   └── InterestController
│   │       │   ├── domain
│   │       │   │   ├── Interest
│   │       │   │   ├── InterestKeyword
│   │       │   │   └── InterestSubscription
│   │       │   ├── dto
│   │       │   │   ├── InterestDto
│   │       │   │   ├── InterestRegisterRequest
│   │       │   │   ├── InterestSearchRequest
│   │       │   │   ├── InterestUpdateRequest
│   │       │   │   └── SubscriptionDto
│   │       │   ├── mapper
│   │       │   │   └── InterestMapper
│   │       │   ├── repository
│   │       │   │   ├── impl
│   │       │   │   │   └── InterestSubscriptionQueryRepositoryImpl
│   │       │   │   ├── InterestKeywordRepository
│   │       │   │   ├── InterestRepository
│   │       │   │   ├── InterestSubscriptionQueryRepository
│   │       │   │   └── InterestSubscriptionRepository
│   │       │   └── service
│   │       │       └── InterestService
│   │       ├── notification
│   │       │   ├── controller
│   │       │   │   └── NotificationController
│   │       │   ├── domain
│   │       │   │   └── Notification
│   │       │   ├── dto
│   │       │   │   ├── NotificationCreateRequest
│   │       │   │   └── NotificationDto
│   │       │   ├── exception
│   │       │   │   ├── NotificationException
│   │       │   │   └── NotificationNotFoundException
│   │       │   ├── repository
│   │       │   │   ├── NotificationQueryRepository
│   │       │   │   ├── NotificationQueryRepositoryImpl
│   │       │   │   └── NotificationRepository
│   │       │   └── service
│   │       │       └── NotificationService
│   │       └── user
│   │           ├── controller
│   │           │   └── UserController
│   │           ├── domain
│   │           │   └── User
│   │           ├── dto
│   │           │   ├── UserDto
│   │           │   ├── UserLoginRequest
│   │           │   ├── UserLoginResponse
│   │           │   ├── UserRegisterRequest
│   │           │   └── UserUpdateRequest
│   │           ├── exception
│   │           │   ├── UserAlreadyDeletedException
│   │           │   ├── UserAlreadyExistsException
│   │           │   ├── UserException
│   │           │   ├── UserForbiddenException
│   │           │   ├── UserLoginFailedException
│   │           │   ├── UserNotFoundException
│   │           │   └── UserNotSoftDeletedException
│   │           ├── mapper
│   │           │   └── UserMapper
│   │           ├── repository
│   │           │   └── UserRepository
│   │           └── service
│   │               ├── UserCleanupService
│   │               ├── UserDetailsServiceImpl
│   │               └── UserService
│   └── resources
│       ├── static
│       │   ├── .well-known.appspecific
│       │   │   └── com.chrome.devtools.json
│       │   ├── assets
│       │   │   ├── index-BBLcifoK.js
│       │   │   ├── index-CHX_5t7G.css
│       │   │   ├── landing_comments-BoMt6RvV.svg
│       │   │   ├── landing_interests-CBQzCgwG.svg
│       │   │   └── landing_notifications-BkwzqdfE.svg
│       │   ├── fonts.pretendard
│       │   │   ├── LICENSE.txt
│       │   │   ├── Pretendard-Bold.woff2
│       │   │   ├── Pretendard-Regular.woff2
│       │   │   └── PretendardVariable.woff2
│       │   ├── favicon.ico
│       │   └── index.html
│       ├── application.yml
│       ├── application-dev.yml
│       ├── application-prod.yml
│       ├── application-test.yml
│       ├── data.sql
│       ├── logback-spring.xml
│       ├── schema-h2.sql
│       └── schema-postgres.sql
└── test
    └── java
        └── com.codeit.monew
            ├── activity
            │   └── exception
            │       ├── UserActivityExceptionTest
            │       └── UserActivityServiceTest
            ├── article
            │   ├── ArticleApiIntegrationTest
            │   ├── ArticleRepositoryTest
            │   └── ArticleServiceTest
            ├── comment
            │   └── CommentServiceTest
            ├── common.config
            │   └── TestSecurityConfig
            ├── interest
            │   ├── controller
            │   │   └── InterestControllerTest
            │   ├── domain
            │   │   ├── InterestKeywordTest
            │   │   ├── InterestSubscriptionTest
            │   │   └── InterestTest
            │   ├── repository
            │   │   ├── InterestRepositoryTest
            │   │   └── InterestSubscriptionRepositoryTest
            │   └── service
            │       └── InterestServiceTest
            ├── notification
            │   ├── exception
            │   │   └── NotificationExceptionTest
            │   ├── repository
            │   │   └── NotificationRepositoryTest
            │   └── service
            │       ├── NotificationServiceTest
            │       └── NotificationServiceUnitTest
            └── service
                └── MonewApplicationTests
```
### monew-batch
```
src
├── main
│   ├── java
│   │   └── com.codeit.batch
│   │       ├── MonewBatchApplication.java
│   │       ├── article
│   │       │   ├── config
│   │       │   │   ├── ArticleBackupJobConfig
│   │       │   │   ├── ArticleIngestionJobConfig
│   │       │   │   ├── AwsProperties
│   │       │   │   ├── OpenApiProperties
│   │       │   │   └── RssProperties
│   │       │   ├── domain
│   │       │   │   ├── Article
│   │       │   │   ├── ArticleInterest
│   │       │   │   ├── ArticleInterestId
│   │       │   │   ├── ArticleSource
│   │       │   │   ├── Interest
│   │       │   │   ├── InterestKeyword
│   │       │   │   └── InterestSubscription
│   │       │   ├── dto
│   │       │   │   ├── ArticleBackupDto
│   │       │   │   ├── ArticleCandidate
│   │       │   │   ├── NewsItem
│   │       │   │   ├── NewsResponse
│   │       │   │   ├── OpenApiFetchRequest
│   │       │   │   ├── RssFeedItem
│   │       │   │   └── RssFeedResponse
│   │       │   ├── fetcher
│   │       │   │   ├── ArticleFetchException
│   │       │   │   ├── OpenApiArticleFetcher
│   │       │   │   └── RssArticleFetcher
│   │       │   ├── listener
│   │       │   │   ├── ArticleInterestAggregationListener
│   │       │   │   └── InterestNotificationPublisher
│   │       │   ├── mapper
│   │       │   │   └── ArticleBackupDtoMapper
│   │       │   ├── processor
│   │       │   │   ├── ArticleBackupProcessor
│   │       │   │   └── ArticleProcessor
│   │       │   ├── reader
│   │       │   │   ├── ArticleBackupReader
│   │       │   │   ├── OpenApiArticleReader
│   │       │   │   └── RssArticleReader
│   │       │   ├── repository
│   │       │   │   ├── ArticleRepository
│   │       │   │   ├── InterestKeywordRepository
│   │       │   │   ├── InterestRepository
│   │       │   │   └── InterestSubscriptionRepository
│   │       │   ├── scheduler
│   │       │   │   └── ArticleScheduler
│   │       │   ├── storage
│   │       │   │   ├── BackupStorageException
│   │       │   │   └── S3BackupStorage
│   │       │   ├── tasklet
│   │       │   │   └── ArticleIngestionTasklet
│   │       │   └── writer
│   │       │       ├── ArticleBackupWriter
│   │       │       └── ArticleWriter
│   │       ├── common
│   │       │   ├── base
│   │       │   │   ├── BaseDomain
│   │       │   │   └── BaseUpdatableDomain
│   │       │   ├── config
│   │       │   │   └── QuerydslConfig
│   │       │   └── metrics
│   │       │       ├── BatchJobMetricsListener
│   │       │       ├── CloudWatchMetricsConfig
│   │       │       └── CloudWatchMetricsProperties
│   │       ├── log
│   │       │   ├── domain
│   │       │   │   └── IngestionLog
│   │       │   ├── repository
│   │       │   │   └── ArticleLogRepository
│   │       │   └── service
│   │       │       └── MonewBatchScheduler
│   │       ├── notification
│   │       │   ├── config
│   │       │   │   └── NotificationDeleteConfig
│   │       │   ├── domain
│   │       │   │   └── Notification
│   │       │   ├── repository
│   │       │   │   ├── NotificationQueryRepository
│   │       │   │   ├── NotificationQueryRepositoryImpl
│   │       │   │   └── NotificationRepository
│   │       │   ├── service
│   │       │   │   └── NotificationService
│   │       │   └── tasklet
│   │       │       └── NotificationDeleteTasklet
│   │       └── user.domain
│   │           └── User
│   └── resources
│       ├── app-schema-postgres.sql
│       ├── application.yaml
│       ├── application-dev.yaml
│       ├── application-prod.yaml
│       ├── application-test.yaml
│       ├── batch-schema-postgres.sql
│       ├── data.sql
│       ├── schema-create.sql
│       ├── schema-h2.sql
│       └── schema_batch.sql
└── test
    └── java
        └── com.codeit.batch
```

## 📺구현 홈페이지
[Monew](http://monew-alb-1161317653.ap-northeast-2.elb.amazonaws.com)

## 📑프로젝트 회고록

- 🎥시연 영상


- 🎬PPT

# v1 Roadmap





### Drizzle Kit V1

- [x] `generated` 컬럼 지원 [베타 브랜치]
- [x] Drizzle Kit에 Brocli 통합
- [ ] `try catches`와 `if not exists` 없이 생성된 SQL 마이그레이션 엄격 모드
- [x] Drizzle Kit 오픈소스로 전환 🎉
- [x] PostgreSQL 열거형(enum) 변경 사항 개선
- [x] PostgreSQL RLS(행 수준 보안) 지원
- [x] Drizzle Kit에서 `check` 제약 조건 지원
- [x] Drizzle Kit에서 프로그래밍 방식 접근을 위한 API 공개
- [x] Drizzle Kit에서 `materialised views` 지원
- [ ] Prisma, TypeORM, Sequelise의 스키마와 마이그레이션을 활용하여 Drizzle 마이그레이션 프로세스를 강화하는 Drizzle Kit 지원
- [ ] 도커 환경에서 Drizzle Studio `mkcert` 문제 수정


### Drizzle ORM V1

- [x] `generated` 컬럼 지원 [베타 브랜치]
- [x] MySQL `.$returningIds()` 지원
- [ ] 내장된 `.env` 사용자를 위한 `NODE_ENV` 지원
- [ ] PostgreSQL `decimals`에 대한 `mode: number` 및 `mode: bigint` 지원
- [x] 컬럼 타입 임포트를 선택적으로 생략할 수 있는 `(t) => ` 콜백을 사용한 테이블 선언
- [ ] 다운 마이그레이션, 더 나은 롤백 및 Drizzle Kit에서의 `migrate` 경험 개선
- [x] 테이블 선언에서 컬럼에 대한 선택적 데이터베이스 별칭 지원 -> `id: serial()`
- [x] PostgreSQL RLS(행 수준 보안) 지원
- [ ] 관계형 쿼리 V2 API
- [x] 학습 곡선을 낮추기 위한 `drizzle('pg', ...)` 드라이버 초기화
- [ ] CockroachDB 지원 (엄격한 SQL 마이그레이션과 함께 지원)
- [x] 네이티브 시딩 지원
- [ ] 수정: [#2575](https://github.com/drizzle-team/drizzle-orm/issues/2575), [#2572](https://github.com/drizzle-team/drizzle-orm/issues/2572), [#2571](https://github.com/drizzle-team/drizzle-orm/issues/2571),
[#2568](https://github.com/drizzle-team/drizzle-orm/issues/2568), [#2559](https://github.com/drizzle-team/drizzle-orm/issues/2559), [#2555](https://github.com/drizzle-team/drizzle-orm/issues/2555), [#2530](https://github.com/drizzle-team/drizzle-orm/issues/2530), [#2514](https://github.com/drizzle-team/drizzle-orm/issues/2514), [#2510](https://github.com/drizzle-team/drizzle-orm/issues/2510), [#2506](https://github.com/drizzle-team/drizzle-orm/issues/2506), [#2496](https://github.com/drizzle-team/drizzle-orm/issues/2496), [#2486](https://github.com/drizzle-team/drizzle-orm/issues/2486), [#2484](https://github.com/drizzle-team/drizzle-orm/issues/2484), [#2474](https://github.com/drizzle-team/drizzle-orm/issues/2474), [#2472](https://github.com/drizzle-team/drizzle-orm/issues/2472), [#2458](https://github.com/drizzle-team/drizzle-orm/issues/2458), [#2455](https://github.com/drizzle-team/drizzle-orm/issues/2455), `drizzle-kit migrate/push --inspect` 추가 [#2488](https://github.com/drizzle-team/drizzle-orm/issues/2448), [#2432](https://github.com/drizzle-team/drizzle-orm/issues/2432), [#2430](https://github.com/drizzle-team/drizzle-orm/issues/2430), [#2426](https://github.com/drizzle-team/drizzle-orm/issues/2426), [#2424](https://github.com/drizzle-team/drizzle-orm/issues/2424), [#2418](https://github.com/drizzle-team/drizzle-orm/issues/2418), [#2414](https://github.com/drizzle-team/drizzle-orm/issues/2414), [#2401](https://github.com/drizzle-team/drizzle-orm/issues/2401), [#2396](https://github.com/drizzle-team/drizzle-orm/issues/2396), [#2395](https://github.com/drizzle-team/drizzle-orm/issues/2395), [#2394](https://github.com/drizzle-team/drizzle-orm/issues/2394), [#2390](https://github.com/drizzle-team/drizzle-orm/issues/2390), [#2389](https://github.com/drizzle-team/drizzle-orm/issues/2389), [#2388](https://github.com/drizzle-team/drizzle-orm/issues/2388), [#2387](https://github.com/drizzle-team/drizzle-orm/issues/2387), [#2384](https://github.com/drizzle-team/drizzle-orm/issues/2384), [#1210](https://github.com/drizzle-team/drizzle-orm/issues/1210), [#1157](https://github.com/drizzle-team/drizzle-orm/issues/1157), [#1113](https://github.com/drizzle-team/drizzle-orm/issues/1113), [#1020](https://github.com/drizzle-team/drizzle-orm/issues/1020), [#1003](https://github.com/drizzle-team/drizzle-orm/issues/1003), [#998](https://github.com/drizzle-team/drizzle-orm/issues/998), [#830](https://github.com/drizzle-team/drizzle-orm/issues/830), [#724](https://github.com/drizzle-team/drizzle-orm/issues/724), [#2254](https://github.com/drizzle-team/drizzle-orm/issues/2254), [#2239](https://github.com/drizzle-team/drizzle-orm/issues/2239), [#2236](https://github.com/drizzle-team/drizzle-orm/issues/2236), [#2224](https://github.com/drizzle-team/drizzle-orm/issues/2224), [#2216](https://github.com/drizzle-team/drizzle-orm/issues/2216), [#2198](https://github.com/drizzle-team/drizzle-orm/issues/2198), [#2189](https://github.com/drizzle-team/drizzle-orm/issues/2189), [#2183](https://github.com/drizzle-team/drizzle-orm/issues/2183), [#2174](https://github.com/drizzle-team/drizzle-orm/issues/2174), [#2169](https://github.com/drizzle-team/drizzle-orm/issues/2169), [#2157](https://github.com/drizzle-team/drizzle-orm/issues/2157), [#2151](https://github.com/drizzle-team/drizzle-orm/issues/2151), [#2146](https://github.com/drizzle-team/drizzle-orm/issues/2146), [#2136](https://github.com/drizzle-team/drizzle-orm/issues/2136), [#2122](https://github.com/drizzle-team/drizzle-orm/issues/2122), [#2085](https://github.com/drizzle-team/drizzle-orm/issues/2085), [#2067](https://github.com/drizzle-team/drizzle-orm/issues/2067), [#2047](https://github.com/drizzle-team/drizzle-orm/issues/2047), [#2015](https://github.com/drizzle-team/drizzle-orm/issues/2015), [#1928](https://github.com/drizzle-team/drizzle-orm/issues/1928), [#1835](https://github.com/drizzle-team/drizzle-orm/issues/1835), [#1804](https://github.com/drizzle-team/drizzle-orm/issues/1804), [#1765](https://github.com/drizzle-team/drizzle-orm/issues/1765), [#1748](https://github.com/drizzle-team/drizzle-orm/issues/1748), [#1744](https://github.com/drizzle-team/drizzle-orm/issues/1744), [#1625](https://github.com/drizzle-team/drizzle-orm/issues/1625), [#1428](https://github.com/drizzle-team/drizzle-orm/issues/1428), [#1402](https://github.com/drizzle-team/drizzle-orm/issues/1402), [#1315](https://github.com/drizzle-team/drizzle-orm/issues/1315), [#1313](https://github.com/drizzle-team/drizzle-orm/issues/1313), [#1294](https://github.com/drizzle-team/drizzle-orm/issues/1294), [#1272](https://github.com/drizzle-team/drizzle-orm/issues/1272), [#1269](https://github.com/drizzle-team/drizzle-orm/issues/1269), [#1225](https://github.com/drizzle-team/drizzle-orm/issues/1225), [#2378](https://github.com/drizzle-team/drizzle-orm/issues/2378), [#2343](https://github.com/drizzle-team/drizzle-orm/issues/2343), [#2322](https://github.com/drizzle-team/drizzle-orm/issues/2322), [#2315](https://github.com/drizzle-team/drizzle-orm/issues/2315), [#2282](https://github.com/drizzle-team/drizzle-orm/issues/2282), [#2279](https://github.com/drizzle-team/drizzle-orm/issues/2279)
- [ ] 🎉 V1 릴리스 스트리밍 🎉
- [ ] MariaDB 지원
- [ ] MSSQL 지원



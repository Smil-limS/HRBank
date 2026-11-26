# HR Bank — Pull Request

> 원본 레포지토리 https://github.com/sb14-turtles/sb14-HRBank-turtles 의 Pull Request 기록을 2026-11-26에 보관한 사본입니다. 원본이 비공개로 바뀌거나 삭제되어도 볼 수 있도록 이 레포에 함께 저장했습니다. 작성자·날짜는 원본 기준(KST)이고, 본문과 댓글은 원문 그대로 옮겼습니다.

[← 기록 목차로](README.md)

## 목록

| # | 제목 | 작성자 | 브랜치 | 상태 | 생성일 |
|---|---|---|---|---|---|
| [#1](#pr-1) | chore: docker, postgresql 설정 추가 | parksunovo | `chore/docker` → `develop` | ✅ 병합 | 2026-09-09 |
| [#27](#pr-27) | [김어진] feat: 전역 예외 처리 공통 구조 추가 | rladjwls02 | `exception` → `develop` | ✅ 병합 | 2026-09-09 |
| [#28](#pr-28) | feat: 가장 많이 사용될 예외타입 추가 | rladjwls02 | `exception` → `develop` | ✅ 병합 | 2026-09-10 |
| [#29](#pr-29) | feat: C03 직원 통계 API 뼈대 및 임시 Entity 구현 | swanhw | `feature/c03-statistics` → `develop` | ⛔ 닫힘(미병합) | 2026-09-10 |
| [#30](#pr-30) | feat: 변경내역, 변경내용 엔티티 구현 | rladjwls02 | `feat/changeLog` → `develop` | ⛔ 닫힘(미병합) | 2026-09-10 |
| [#31](#pr-31) | 1 2joyejun | joyejun | `1-2joyejun` → `develop` | ⛔ 닫힘(미병합) | 2026-09-10 |
| [#32](#pr-32) | Feature/c03 statistics | swanhw | `feature/c03-statistics` → `develop` | ⛔ 닫힘(미병합) | 2026-09-10 |
| [#33](#pr-33) | feat: 변경이력, 변경내용 저장 구현 | rladjwls02 | `feat/changeLog` → `develop` | ✅ 병합 | 2026-09-10 |
| [#34](#pr-34) | feat: 직원 복합 검색 기능 구현 | parksunovo | `feat/searchByCondition` → `develop` | ✅ 병합 | 2026-09-11 |
| [#35](#pr-35) | feat: 직원 상세 조회, 삭제 기능 구현 | Smil-limS | `feat/employee-detail` → `develop` | ✅ 병합 | 2026-09-11 |
| [#36](#pr-36) | feat: 부서 CRUD (미완성)  | ziezz767 | `feat/department` → `main` | 🟢 열림 | 2026-09-11 |
| [#37](#pr-37) | feat: 변경이력 CRUD 구현 | rladjwls02 | `feat/changeLog-read` → `develop` | ✅ 병합 | 2026-09-14 |
| [#38](#pr-38) | docs: readme.md 추가 | swanhw | `feature/c03-statistics` → `main` | ✅ 병합 | 2026-09-14 |
| [#39](#pr-39) | Feat/employee page | parksunovo | `feat/employee-page` → `develop` | ✅ 병합 | 2026-09-14 |
| [#40](#pr-40) | feat: 부서 CRUD 구현, 부서 페이지네이션 구현 | Smil-limS | `feat/department-page` → `develop` | ⛔ 닫힘(미병합) | 2026-09-14 |
| [#41](#pr-41) | fix: EmployeeQRepositoryImpl 위치 변경 | rladjwls02 | `fix/develop` → `develop` | ✅ 병합 | 2026-09-14 |
| [#42](#pr-42) | fead: 파일 메타데이터 및 다운로드 구현 (테스트 미실행) | ziezz767 | `feat/fileDownload` → `main` | 🟢 열림 | 2026-09-14 |
| [#43](#pr-43) | feat: 데이터 백업 생성(미구현) | ziezz767 | `feat/employee-backup` → `main` | 🟢 열림 | 2026-09-14 |
| [#44](#pr-44) | feat: 파일 관리 구현 | Smil-limS | `feat/file` → `develop` | ✅ 병합 | 2026-09-14 |
| [#45](#pr-45) | feat: backup | rladjwls02 | `feat/backup` → `develop` | ✅ 병합 | 2026-09-14 |
| [#46](#pr-46) | 컨트롤러 구현 및 develop 변경사항 반영  | parksunovo | `refactor/employee` → `develop` | ✅ 병합 | 2026-09-14 |
| [#47](#pr-47) | feat: department controller 구현 | Smil-limS | `feat/department-controller` → `develop` | ✅ 병합 | 2026-09-14 |
| [#48](#pr-48) | feat: 프론트코드 연동 | parksunovo | `feat/front` → `develop` | ✅ 병합 | 2026-09-14 |
| [#49](#pr-49) | 프론트  연동 오류 수정 | parksunovo | `feat/front` → `develop` | ✅ 병합 | 2026-09-15 |
| [#50](#pr-50) | feat: 백업 성공, 실패시 csv, .log 파일 다운로드 구현 | rladjwls02 | `feat/backup-csv-connect` → `develop` | ✅ 병합 | 2026-09-15 |
| [#51](#pr-51) | feat: 백업 조회 및 페이지네이션 | Smil-limS | `feat/backup-search-pagination` → `develop` | ✅ 병합 | 2026-09-15 |
| [#52](#pr-52) | feat: 자동 백업 스케줄러 구현 및 검증 | rladjwls02 | `feat/backup-csv-connect` → `develop` | ✅ 병합 | 2026-09-15 |
| [#53](#pr-53) | refactor: 백업 조회 서비스에 ISP 적용 | Smil-limS | `feat/backup-search-pagination` → `develop` | ✅ 병합 | 2026-09-15 |
| [#54](#pr-54) | refactor: 변경 이력 서비스에 ISP 적용 | rladjwls02 | `refactor/changelog` → `develop` | ✅ 병합 | 2026-09-16 |
| [#55](#pr-55) | refactor: 에러 응답 형식 명세에 맞게 개선 | rladjwls02 | `refactor/error` → `develop` | ✅ 병합 | 2026-09-16 |
| [#56](#pr-56) | 대시보드 구현 | parksunovo | `feat/employeedashboard` → `develop` | ✅ 병합 | 2026-09-16 |
| [#57](#pr-57) | fix: csv생성시 이스케이프 추가 | rladjwls02 | `fix/csv` → `develop` | ✅ 병합 | 2026-09-16 |
| [#58](#pr-58) | refactor: DepartmentController에서 service 주입 대신 인터페이스 주입으로 변경 | Smil-limS | `feat/backup-search-pagination` → `develop` | ✅ 병합 | 2026-09-16 |
| [#59](#pr-59) | 전반적인 코드 구조 개선 | parksunovo | `feat/employeedashboard` → `develop` | ✅ 병합 | 2026-09-16 |
| [#60](#pr-60) | HR Bank v1.0.0 | parksunovo | `develop` → `main` | ✅ 병합 | 2026-09-16 |
| [#61](#pr-61) | docs: update readme | swanhw | `swanhw-patch-2` → `main` | ⛔ 닫힘(미병합) | 2026-09-16 |
| [#62](#pr-62) | docs: readme.md 추가 | swanhw | `swanhw-patch-4` → `develop` | ⛔ 닫힘(미병합) | 2026-09-16 |
| [#63](#pr-63) | fix: Railway 배포 빌드 오류 해결을 위한 foojay toolchain 플러그인 추가 | Smil-limS | `feat/backup-search-pagination` → `develop` | ✅ 병합 | 2026-09-16 |
| [#64](#pr-64) | fix: Railway 배포 빌드 오류 해결을 위한 foojay toolchain 플러그인 추가 | Smil-limS | `develop` → `main` | ⛔ 닫힘(미병합) | 2026-09-16 |
| [#65](#pr-65) | feat: Railway 배포 빌드 오류 해결을 위한 foojay toolchain 플러그인 추가 | Smil-limS | `feat/deploy` → `main` | ✅ 병합 | 2026-09-16 |
| [#66](#pr-66) | refactor: employeeApp구조 개선 | parksunovo | `refactor/employeeapp` → `main` | ✅ 병합 | 2026-09-17 |
| [#67](#pr-67) | fix: CSV 생성시 깨지는 문제 해결 | rladjwls02 | `fix/csv-excel-bom` → `main` | ✅ 병합 | 2026-09-17 |
| [#68](#pr-68) | readme.md 수정  | parksunovo | `docs/readme` → `main` | ✅ 병합 | 2026-09-17 |
| [#69](#pr-69) | fix: 버그수정 | parksunovo | `docs/readme` → `main` | ✅ 병합 | 2026-09-17 |

---

<a id="pr-1"></a>

## #1 chore: docker, postgresql 설정 추가

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 병합
- 브랜치: `chore/docker` → `develop`
- 생성: 2026-09-09 11:08
- 병합: 2026-09-09 11:20
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/1

> _(본문 없음)_

**댓글**

- [rladjwls02](https://github.com/rladjwls02) · 2026-09-09 11:10

  > 별로인데요 머지 안됩니다

- [swanhw](https://github.com/swanhw) · 2026-09-09 11:21

  > gg

- [ziezz767](https://github.com/ziezz767) · 2026-09-09 11:21

  > 확인했습니다

[↑ 목록으로](#목록)

---

<a id="pr-27"></a>

## #27 [김어진] feat: 전역 예외 처리 공통 구조 추가

- 작성자: [rladjwls02](https://github.com/rladjwls02)
- 상태: ✅ 병합
- 브랜치: `exception` → `develop`
- 생성: 2026-09-09 18:52
- 병합: 2026-09-09 18:53
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/27

> 전역 예외 처리 구조를 잡았습니다 확인 부탁드립니다.

**댓글**

- [joyejun](https://github.com/joyejun) · 2026-09-09 18:54

  > 확인했습니다.

[↑ 목록으로](#목록)

---

<a id="pr-28"></a>

## #28 feat: 가장 많이 사용될 예외타입 추가

- 작성자: [rladjwls02](https://github.com/rladjwls02)
- 상태: ✅ 병합
- 브랜치: `exception` → `develop`
- 생성: 2026-09-10 09:41
- 병합: 2026-09-10 14:15
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/28

> 가장 많이 사용될 예외타입 3개 추가했습니다 확인 후 머지 부탁드립니다

[↑ 목록으로](#목록)

---

<a id="pr-29"></a>

## #29 feat: C03 직원 통계 API 뼈대 및 임시 Entity 구현

- 작성자: [swanhw](https://github.com/swanhw)
- 상태: ⛔ 닫힘(미병합)
- 브랜치: `feature/c03-statistics` → `develop`
- 생성: 2026-09-10 13:07
- 닫힘: 2026-09-10 13:17
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/29

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-30"></a>

## #30 feat: 변경내역, 변경내용 엔티티 구현

- 작성자: [rladjwls02](https://github.com/rladjwls02)
- 상태: ⛔ 닫힘(미병합)
- 브랜치: `feat/changeLog` → `develop`
- 생성: 2026-09-10 13:10
- 닫힘: 2026-09-10 13:54
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/30

> 변경내역, 변경내용 엔티티 구현하고 JPA 작동 여부까지 확인했습니다

[↑ 목록으로](#목록)

---

<a id="pr-31"></a>

## #31 1 2joyejun

- 작성자: [joyejun](https://github.com/joyejun)
- 상태: ⛔ 닫힘(미병합)
- 브랜치: `1-2joyejun` → `develop`
- 생성: 2026-09-10 13:13
- 닫힘: 2026-09-10 13:22
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/31

> 필요한 엔티티 구현

[↑ 목록으로](#목록)

---

<a id="pr-32"></a>

## #32 Feature/c03 statistics

- 작성자: [swanhw](https://github.com/swanhw)
- 상태: ⛔ 닫힘(미병합)
- 브랜치: `feature/c03-statistics` → `develop`
- 생성: 2026-09-10 13:34
- 닫힘: 2026-09-10 13:35
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/32

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-33"></a>

## #33 feat: 변경이력, 변경내용 저장 구현

- 작성자: [rladjwls02](https://github.com/rladjwls02)
- 상태: ✅ 병합
- 브랜치: `feat/changeLog` → `develop`
- 생성: 2026-09-10 14:13
- 병합: 2026-09-11 16:28
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/33

> 변경내용, 변경내역 저장 기능 구현하고 테스트까지 완료했습니다

**댓글**

- [Smil-limS](https://github.com/Smil-limS) · 2026-09-10 17:55

  > 40번째 줄 매개변수
  > Employee employee도 지워주시면 감사하겠습니다!

[↑ 목록으로](#목록)

---

<a id="pr-34"></a>

## #34 feat: 직원 복합 검색 기능 구현

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 병합
- 브랜치: `feat/searchByCondition` → `develop`
- 생성: 2026-09-11 00:03
- 병합: 2026-09-11 16:36
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/34

> query dsl을 활용해서 직원 복합 검색 구현 및 가독성 향상을 위헤 코드 포맷 설정 변경했습니다(기존 줄 바꿈, 탭 간격 4칸 변경 후 2칸)

[↑ 목록으로](#목록)

---

<a id="pr-35"></a>

## #35 feat: 직원 상세 조회, 삭제 기능 구현

- 작성자: [Smil-limS](https://github.com/Smil-limS)
- 상태: ✅ 병합
- 브랜치: `feat/employee-detail` → `develop`
- 생성: 2026-09-11 12:58
- 병합: 2026-09-11 16:46
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/35

> 직원 상세 조회 기능 구현 완료했습니다.

**댓글**

- [parksunovo](https://github.com/parksunovo) · 2026-09-11 16:45

  > 확인했습니다~

[↑ 목록으로](#목록)

---

<a id="pr-36"></a>

## #36 feat: 부서 CRUD (미완성) 

- 작성자: [ziezz767](https://github.com/ziezz767)
- 상태: 🟢 열림
- 브랜치: `feat/department` → `main`
- 생성: 2026-09-11 18:13
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/36

> - controller
> - service
> - repository(JPA)
> - dto(create, update, response)
> - entity(Department)
> 까지 만들고 API 요청 시, 데이터가 DB에 잘 적재되는지 아직 확인 못함

[↑ 목록으로](#목록)

---

<a id="pr-37"></a>

## #37 feat: 변경이력 CRUD 구현

- 작성자: [rladjwls02](https://github.com/rladjwls02)
- 상태: ✅ 병합
- 브랜치: `feat/changeLog-read` → `develop`
- 생성: 2026-09-14 09:47
- 병합: 2026-09-14 09:49
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/37

> 변경이력 및 변경내용 기능구현 마무리

[↑ 목록으로](#목록)

---

<a id="pr-38"></a>

## #38 docs: readme.md 추가

- 작성자: [swanhw](https://github.com/swanhw)
- 상태: ✅ 병합
- 브랜치: `feature/c03-statistics` → `main`
- 생성: 2026-09-14 09:58
- 병합: 2026-09-16 16:05
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/38

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-39"></a>

## #39 Feat/employee page

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 병합
- 브랜치: `feat/employee-page` → `develop`
- 생성: 2026-09-14 10:00
- 병합: 2026-09-14 10:05
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/39

> 직원 페이지네이션 구현

[↑ 목록으로](#목록)

---

<a id="pr-40"></a>

## #40 feat: 부서 CRUD 구현, 부서 페이지네이션 구현

- 작성자: [Smil-limS](https://github.com/Smil-limS)
- 상태: ⛔ 닫힘(미병합)
- 브랜치: `feat/department-page` → `develop`
- 생성: 2026-09-14 10:27
- 닫힘: 2026-09-14 10:31
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/40

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-41"></a>

## #41 fix: EmployeeQRepositoryImpl 위치 변경

- 작성자: [rladjwls02](https://github.com/rladjwls02)
- 상태: ✅ 병합
- 브랜치: `fix/develop` → `develop`
- 생성: 2026-09-14 11:49
- 병합: 2026-09-14 11:50
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/41

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-42"></a>

## #42 fead: 파일 메타데이터 및 다운로드 구현 (테스트 미실행)

- 작성자: [ziezz767](https://github.com/ziezz767)
- 상태: 🟢 열림
- 브랜치: `feat/fileDownload` → `main`
- 생성: 2026-09-14 13:42
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/42

> 파일 엔티티 필드들 맞는지 확인 좀 부탁드립니다.

[↑ 목록으로](#목록)

---

<a id="pr-43"></a>

## #43 feat: 데이터 백업 생성(미구현)

- 작성자: [ziezz767](https://github.com/ziezz767)
- 상태: 🟢 열림
- 브랜치: `feat/employee-backup` → `main`
- 생성: 2026-09-14 13:45
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/43

> 구현하기 위해서 직원 수정 이력이나 변경내용 테이블 내용이 필요할 것 같습니다....

[↑ 목록으로](#목록)

---

<a id="pr-44"></a>

## #44 feat: 파일 관리 구현

- 작성자: [Smil-limS](https://github.com/Smil-limS)
- 상태: ✅ 병합
- 브랜치: `feat/file` → `develop`
- 생성: 2026-09-14 17:10
- 병합: 2026-09-14 17:41
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/44

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-45"></a>

## #45 feat: backup

- 작성자: [rladjwls02](https://github.com/rladjwls02)
- 상태: ✅ 병합
- 브랜치: `feat/backup` → `develop`
- 생성: 2026-09-14 17:40
- 병합: 2026-09-14 17:43
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/45

> 확인부탁드립니다.

[↑ 목록으로](#목록)

---

<a id="pr-46"></a>

## #46 컨트롤러 구현 및 develop 변경사항 반영 

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 병합
- 브랜치: `refactor/employee` → `develop`
- 생성: 2026-09-14 18:12
- 병합: 2026-09-14 18:15
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/46

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-47"></a>

## #47 feat: department controller 구현

- 작성자: [Smil-limS](https://github.com/Smil-limS)
- 상태: ✅ 병합
- 브랜치: `feat/department-controller` → `develop`
- 생성: 2026-09-14 18:36
- 병합: 2026-09-14 18:43
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/47

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-48"></a>

## #48 feat: 프론트코드 연동

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 병합
- 브랜치: `feat/front` → `develop`
- 생성: 2026-09-14 18:47
- 병합: 2026-09-14 18:48
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/48

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-49"></a>

## #49 프론트  연동 오류 수정

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 병합
- 브랜치: `feat/front` → `develop`
- 생성: 2026-09-15 11:03
- 병합: 2026-09-15 11:22
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/49

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-50"></a>

## #50 feat: 백업 성공, 실패시 csv, .log 파일 다운로드 구현

- 작성자: [rladjwls02](https://github.com/rladjwls02)
- 상태: ✅ 병합
- 브랜치: `feat/backup-csv-connect` → `develop`
- 생성: 2026-09-15 11:54
- 병합: 2026-09-15 13:23
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/50

> 확인부탁드립니다

[↑ 목록으로](#목록)

---

<a id="pr-51"></a>

## #51 feat: 백업 조회 및 페이지네이션

- 작성자: [Smil-limS](https://github.com/Smil-limS)
- 상태: ✅ 병합
- 브랜치: `feat/backup-search-pagination` → `develop`
- 생성: 2026-09-15 13:43
- 병합: 2026-09-15 14:27
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/51

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-52"></a>

## #52 feat: 자동 백업 스케줄러 구현 및 검증

- 작성자: [rladjwls02](https://github.com/rladjwls02)
- 상태: ✅ 병합
- 브랜치: `feat/backup-csv-connect` → `develop`
- 생성: 2026-09-15 14:14
- 병합: 2026-09-15 14:28
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/52

> -1시간 주기로 자동 백업하도록 설정

[↑ 목록으로](#목록)

---

<a id="pr-53"></a>

## #53 refactor: 백업 조회 서비스에 ISP 적용

- 작성자: [Smil-limS](https://github.com/Smil-limS)
- 상태: ✅ 병합
- 브랜치: `feat/backup-search-pagination` → `develop`
- 생성: 2026-09-15 17:33
- 병합: 2026-09-16 11:24
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/53

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-54"></a>

## #54 refactor: 변경 이력 서비스에 ISP 적용

- 작성자: [rladjwls02](https://github.com/rladjwls02)
- 상태: ✅ 병합
- 브랜치: `refactor/changelog` → `develop`
- 생성: 2026-09-16 09:13
- 병합: 2026-09-16 11:24
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/54

> dto명 변경과 인터페이스 및 구현클래스로 분리 했습니다 확인 부탁드립니다.

[↑ 목록으로](#목록)

---

<a id="pr-55"></a>

## #55 refactor: 에러 응답 형식 명세에 맞게 개선

- 작성자: [rladjwls02](https://github.com/rladjwls02)
- 상태: ✅ 병합
- 브랜치: `refactor/error` → `develop`
- 생성: 2026-09-16 09:16
- 병합: 2026-09-16 11:25
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/55

> api명세의 스키마와 응답형식 동일하게 변경했습니다 확인부탁드립니다

[↑ 목록으로](#목록)

---

<a id="pr-56"></a>

## #56 대시보드 구현

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 병합
- 브랜치: `feat/employeedashboard` → `develop`
- 생성: 2026-09-16 11:23
- 병합: 2026-09-16 11:35
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/56

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-57"></a>

## #57 fix: csv생성시 이스케이프 추가

- 작성자: [rladjwls02](https://github.com/rladjwls02)
- 상태: ✅ 병합
- 브랜치: `fix/csv` → `develop`
- 생성: 2026-09-16 13:43
- 병합: 2026-09-16 14:16
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/57

> 확인 부탁드리겠습니다

[↑ 목록으로](#목록)

---

<a id="pr-58"></a>

## #58 refactor: DepartmentController에서 service 주입 대신 인터페이스 주입으로 변경

- 작성자: [Smil-limS](https://github.com/Smil-limS)
- 상태: ✅ 병합
- 브랜치: `feat/backup-search-pagination` → `develop`
- 생성: 2026-09-16 14:01
- 병합: 2026-09-16 14:17
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/58

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-59"></a>

## #59 전반적인 코드 구조 개선

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 병합
- 브랜치: `feat/employeedashboard` → `develop`
- 생성: 2026-09-16 14:17
- 병합: 2026-09-16 14:25
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/59

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-60"></a>

## #60 HR Bank v1.0.0

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 병합
- 브랜치: `develop` → `main`
- 생성: 2026-09-16 14:37
- 병합: 2026-09-16 14:39
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/60

> release

[↑ 목록으로](#목록)

---

<a id="pr-61"></a>

## #61 docs: update readme

- 작성자: [swanhw](https://github.com/swanhw)
- 상태: ⛔ 닫힘(미병합)
- 브랜치: `swanhw-patch-2` → `main`
- 생성: 2026-09-16 14:41
- 닫힘: 2026-09-16 15:38
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/61

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-62"></a>

## #62 docs: readme.md 추가

- 작성자: [swanhw](https://github.com/swanhw)
- 상태: ⛔ 닫힘(미병합)
- 브랜치: `swanhw-patch-4` → `develop`
- 생성: 2026-09-16 15:42
- 닫힘: 2026-09-16 15:50
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/62

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-63"></a>

## #63 fix: Railway 배포 빌드 오류 해결을 위한 foojay toolchain 플러그인 추가

- 작성자: [Smil-limS](https://github.com/Smil-limS)
- 상태: ✅ 병합
- 브랜치: `feat/backup-search-pagination` → `develop`
- 생성: 2026-09-16 16:23
- 병합: 2026-09-16 16:26
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/63

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-64"></a>

## #64 fix: Railway 배포 빌드 오류 해결을 위한 foojay toolchain 플러그인 추가

- 작성자: [Smil-limS](https://github.com/Smil-limS)
- 상태: ⛔ 닫힘(미병합)
- 브랜치: `develop` → `main`
- 생성: 2026-09-16 16:31
- 닫힘: 2026-09-16 18:07
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/64

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-65"></a>

## #65 feat: Railway 배포 빌드 오류 해결을 위한 foojay toolchain 플러그인 추가

- 작성자: [Smil-limS](https://github.com/Smil-limS)
- 상태: ✅ 병합
- 브랜치: `feat/deploy` → `main`
- 생성: 2026-09-16 16:45
- 병합: 2026-09-16 16:47
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/65

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-66"></a>

## #66 refactor: employeeApp구조 개선

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 병합
- 브랜치: `refactor/employeeapp` → `main`
- 생성: 2026-09-17 09:24
- 병합: 2026-09-17 09:25
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/66

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-67"></a>

## #67 fix: CSV 생성시 깨지는 문제 해결

- 작성자: [rladjwls02](https://github.com/rladjwls02)
- 상태: ✅ 병합
- 브랜치: `fix/csv-excel-bom` → `main`
- 생성: 2026-09-17 11:40
- 병합: 2026-09-17 11:42
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/67

> 확인부탁드립니다.

[↑ 목록으로](#목록)

---

<a id="pr-68"></a>

## #68 readme.md 수정 

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 병합
- 브랜치: `docs/readme` → `main`
- 생성: 2026-09-17 18:15
- 병합: 2026-09-17 18:16
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/68

> _(본문 없음)_

[↑ 목록으로](#목록)

---

<a id="pr-69"></a>

## #69 fix: 버그수정

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 병합
- 브랜치: `docs/readme` → `main`
- 생성: 2026-09-17 18:45
- 병합: 2026-09-17 18:46
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/pull/69

> _(본문 없음)_

[↑ 목록으로](#목록)

---

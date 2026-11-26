# HR Bank — Issue

> 원본 레포지토리 https://github.com/sb14-turtles/sb14-HRBank-turtles 의 Issue 기록을 2026-11-26에 보관한 사본입니다. 원본이 비공개로 바뀌거나 삭제되어도 볼 수 있도록 이 레포에 함께 저장했습니다. 작성자·날짜는 원본 기준(KST)이고, 본문과 댓글은 원문 그대로 옮겼습니다.

[← 기록 목차로](README.md)

## 목록

| # | 제목 | 작성자 | 라벨 | 상태 | 생성일 |
|---|---|---|---|---|---|
| [#2](#issue-2) | [P01][공동] ERD·API·연동 계약 확정 | parksunovo |  | ✅ 완료 | 2026-09-09 |
| [#3](#issue-3) | [A01][1조] 공통 구조와 부서 등록·수정·삭제 구현 | parksunovo | 신상엽 | ✅ 완료 | 2026-09-09 |
| [#4](#issue-4) | [A02][1조] 부서 상세·검색·페이지네이션 구현 | parksunovo | 박성욱, 신상엽 | ✅ 완료 | 2026-09-09 |
| [#5](#issue-5) | [B01][1조] 직원 등록·수정 구현 | parksunovo | 박태양 | ✅ 완료 | 2026-09-09 |
| [#6](#issue-6) | [B02][1조] 직원 상세·삭제 구현, 부서·이력 연동 | parksunovo | 박태양 | ✅ 완료 | 2026-09-09 |
| [#7](#issue-7) | [C01][2조] 직원 복합 검색 구현 | parksunovo | 박태양 | ✅ 완료 | 2026-09-09 |
| [#8](#issue-8) | [C02][2조] 직원 정렬·페이지네이션 구현 | parksunovo | 박태양 | ✅ 완료 | 2026-09-09 |
| [#9](#issue-9) | [C03][2조] 직원 수·추이·분포 통계 구현 | parksunovo | 박태양 | ✅ 완료 | 2026-09-09 |
| [#10](#issue-10) | [D01][2조] 직원 변경 이력 기록 구현 | parksunovo | 김어진 | ✅ 완료 | 2026-09-09 |
| [#11](#issue-11) | [D02][2조] 변경 이력 검색·상세·건수 구현 | parksunovo | 김어진 | ✅ 완료 | 2026-09-09 |
| [#12](#issue-12) | [B03][1조] 직원·부서·변경 이력 연결 검증 | parksunovo | 신상엽 | ✅ 완료 | 2026-09-09 |
| [#13](#issue-13) | [F01][1조] 파일 메타데이터·다운로드 구현 | parksunovo | 박성욱, 신상엽 | ✅ 완료 | 2026-09-09 |
| [#14](#issue-14) | [F02][1조] 로컬 파일 저장·삭제 구현 | parksunovo | 신상엽 | ✅ 완료 | 2026-09-09 |
| [#15](#issue-15) | [F03][1조] 직원 프로필 이미지 연동 완료 | parksunovo | 박태양 | ✅ 완료 | 2026-09-09 |
| [#16](#issue-16) | [F04][1조] CI·배포 환경 구성 | parksunovo | 박태양, 신상엽 | ✅ 완료 | 2026-09-09 |
| [#17](#issue-17) | [E01][2조] 백업 필요 여부·진행 상태 구현 | parksunovo | 김어진 | ✅ 완료 | 2026-09-09 |
| [#18](#issue-18) | [E02][2조] 수동 백업·CSV 생성 구현 | parksunovo | 김어진 | ✅ 완료 | 2026-09-09 |
| [#19](#issue-19) | [E03][2조] 백업 성공·실패·로그 처리 완성 | parksunovo | 김어진 | ✅ 완료 | 2026-09-09 |
| [#20](#issue-20) | [E04][2조] 자동 백업 스케줄러 구현 | parksunovo |  | ✅ 완료 | 2026-09-09 |
| [#21](#issue-21) | [E05][2조] 백업 검색·페이지네이션·최근 백업 조회 | parksunovo | 신상엽 | ✅ 완료 | 2026-09-09 |
| [#22](#issue-22) | [E06][2조] 대량 CSV·메모리·경계값 검증 | parksunovo | 김어진 | ✅ 완료 | 2026-09-09 |
| [#23](#issue-23) | [F05][1조] 제공된 프론트엔드 연결 검증 | parksunovo | 박태양 | ✅ 완료 | 2026-09-09 |
| [#24](#issue-24) | [T01][공동] 전체 시나리오 통합 테스트 | parksunovo | 박태양, 김어진, 조예준, 박성욱, 신상엽, 정수환 | ✅ 완료 | 2026-09-09 |
| [#25](#issue-25) | [T02][공동] 통합 오류 수정·최종 배포 확인 | parksunovo |  | ✅ 완료 | 2026-09-09 |
| [#26](#issue-26) | [T03][공동] README·발표·제출 자료 정리 | parksunovo |  | 🟢 열림 | 2026-09-09 |

---

<a id="issue-2"></a>

## #2 [P01][공동] ERD·API·연동 계약 확정

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:31
- 닫힘: 2026-09-13 20:38
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/2

> ## 작업 정보
> - 담당 조: 공동
> - 담당 역할: 전원
> - 일정: 2026-09-10
> - 단계: 1단계 A~D
> - 선행 조건: 없음
> 
> ## 완료 기준
> - [x] ERD·ID·시간 타입·enum·공통 오류 응답 합의
> - [x] Swagger 기준 요청·응답 DTO와 페이지네이션 규칙 확정
> - [x] 직원 변경·이력의 트랜잭션 범위 합의
> - [x] 파일 저장·삭제 계약과 담당 클래스 합의
> 
> ## 진행 메모
> E·F는 계약만 합의합니다. 실제 구현은 M02 완료 후 시작합니다.
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-3"></a>

## #3 [A01][1조] 공통 구조와 부서 등록·수정·삭제 구현

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:32
- 닫힘: 2026-09-13 20:58
- 라벨: `신상엽`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/3

> ## 작업 정보
> - 담당 조: 1조
> - 담당 역할: 1조-①
> - 일정: 2026-09-10
> - 단계: 1단계 A~D
> - 선행 조건: [P01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/2)
> 
> ## 완료 기준
> - [x] Spring 기본 구조·공통 예외/응답 정리
> - [x] 부서 이름·설명·설립일 등록·수정
> - [x] 이름 중복 거절 및 소속 직원이 있는 부서 삭제 제한
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-4"></a>

## #4 [A02][1조] 부서 상세·검색·페이지네이션 구현

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:32
- 닫힘: 2026-09-13 20:37
- 라벨: `박성욱` `신상엽`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/4

> ## 작업 정보
> - 담당 조: 1조
> - 담당 역할: 1조-①
> - 일정: 2026-09-11
> - 단계: 1단계 A~D
> - 선행 조건: [A01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/3)
> 
> ## 완료 기준
> - [x] 부서 상세와 이름/설명 부분 검색
> - [x] 이름/설립일 정렬과 명세에 맞는 페이지네이션
> - [x] 동일 정렬값·빈 결과·마지막 페이지 확인
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-5"></a>

## #5 [B01][1조] 직원 등록·수정 구현

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:33
- 닫힘: 2026-09-13 20:36
- 라벨: `박태양`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/5

> ## 작업 정보
> - 담당 조: 1조
> - 담당 역할: 1조-②
> - 일정: 2026-09-10 ~ 2026-09-11
> - 단계: 1단계 A~D
> - 선행 조건: [P01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/2)
> 
> ## 완료 기준
> - [ ] 이메일 중복 검사·사번 자동 생성·재직 상태 초기화
> - [ ] 사번을 제외한 속성 수정 및 퇴사를 상태 변경으로 처리
> - [ ] 이미지 없는 요청 정상 동작과 선택적 이미지 연동 계약 확인
> 
> ## 진행 메모
> 프로필 실제 저장·다운로드는 F03에서 마무리합니다. 9/10에는 이력 연동에 필요한 최소 등록 경로를 먼저 공유합니다.
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-6"></a>

## #6 [B02][1조] 직원 상세·삭제 구현, 부서·이력 연동

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:33
- 닫힘: 2026-09-13 20:36
- 라벨: `박태양`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/6

> ## 작업 정보
> - 담당 조: 1조
> - 담당 역할: 1조-③
> - 일정: 2026-09-10 ~ 2026-09-11
> - 단계: 1단계 A~D
> - 선행 조건: [P01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/2)
> 
> ## 완료 기준
> - [x] ID로 직원 상세 조회와 미존재 오류 처리
> - [x] 직원 삭제 및 퇴사 상태 변경을 구분
> - [x] 삭제 이력에 필요한 사번·변경 전 정보를 확보
> 
> ## 진행 메모
> 프로필 동반 삭제의 실제 파일 연동은 F03에서 검증합니다. 공유 Employee 엔티티 변경은 B01·C01 담당자와 리뷰합니다.
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-7"></a>

## #7 [C01][2조] 직원 복합 검색 구현

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:33
- 닫힘: 2026-09-13 20:35
- 라벨: `박태양`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/7

> ## 작업 정보
> - 담당 조: 2조
> - 담당 역할: 2조-①
> - 일정: 2026-09-10
> - 단계: 1단계 A~D
> - 선행 조건: [P01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/2)
> 
> ## 완료 기준
> - [x] 이름/이메일·부서·직함·사번 부분 검색
> - [x] 입사일 범위와 상태 일치 조건 구현
> - [x] 여러 검색 조건의 AND 조합 검증
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-8"></a>

## #8 [C02][2조] 직원 정렬·페이지네이션 구현

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:33
- 닫힘: 2026-09-13 20:36
- 라벨: `박태양`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/8

> ## 작업 정보
> - 담당 조: 2조
> - 담당 역할: 2조-①
> - 일정: 2026-09-11
> - 단계: 1단계 A~D
> - 선행 조건: [C01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/7)
> 
> ## 완료 기준
> - [x] 이름·입사일·사번 중 선택 정렬
> - [x] 이전 페이지 마지막 ID를 활용하는 명세 준수
> - [x] 동일 정렬값에서 누락·중복 없이 다음 페이지 조회
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-9"></a>

## #9 [C03][2조] 직원 수·추이·분포 통계 구현

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:33
- 닫힘: 2026-09-16 13:03
- 라벨: `박태양`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/9

> ## 작업 정보
> - 담당 조: 2조
> - 담당 역할: 2조-②
> - 일정: 2026-09-10 ~ 2026-09-11
> - 단계: 1단계 A~D
> - 선행 조건: [P01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/2)
> 
> ## 완료 기준
> - [x] 총 직원 수와 이번 달 입사자 수 조회
> - [x] 최근 1년 월별 직원 수 추이
> - [x] 부서별·직무별 분포와 빈 데이터 결과 확인
> 
> ## 진행 메모
> 통계 기준일·기간 경계는 Swagger/화면 기준으로 합의합니다. 완료 후 D02 이력 검색·조회 구현을 지원합니다.
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-10"></a>

## #10 [D01][2조] 직원 변경 이력 기록 구현

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:33
- 닫힘: 2026-09-13 20:58
- 라벨: `김어진`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/10

> ## 작업 정보
> - 담당 조: 2조
> - 담당 역할: 2조-③
> - 일정: 2026-09-10 ~ 2026-09-11
> - 단계: 1단계 A~D
> - 선행 조건: [P01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/2)
> 
> ## 완료 기준
> - [x] 추가·수정·삭제 유형과 대상 사번 기록
> - [x] 변경된 속성만 이전·이후 값 기록
> - [x] 메모·서버에서 얻은 요청 IP·시간 저장
> 
> ## 진행 메모
> 9/10에 최소 등록 이력 경로를 공유하고, 9/11에 수정·삭제와 롤백 처리를 마무리합니다.
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-11"></a>

## #11 [D02][2조] 변경 이력 검색·상세·건수 구현

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:34
- 닫힘: 2026-09-14 09:24
- 라벨: `김어진`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/11

> ## 작업 정보
> - 담당 조: 2조
> - 담당 역할: 2조-③
> - 일정: 2026-09-11
> - 단계: 1단계 A~D
> - 선행 조건: [D01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/10)
> 
> ## 완료 기준
> - [x] 사번·메모·IP·시간·유형으로 검색
> - [x] IP/시간 정렬과 페이지네이션
> - [x] 목록에서 변경 상세 제외, ID로 상세 조회
> - [x] 최근 일주일 등 기간별 이력 건수 조회
> 
> ## 진행 메모
> 2조-②가 C03 완료 후 이력 목록·검색 구현을 지원합니다.
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-12"></a>

## #12 [B03][1조] 직원·부서·변경 이력 연결 검증

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:34
- 닫힘: 2026-09-13 20:35
- 라벨: `신상엽`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/12

> ## 작업 정보
> - 담당 조: 1조
> - 담당 역할: 1조-③
> - 일정: 2026-09-11
> - 단계: 1단계 A~D
> - 선행 조건: [A01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/3), [B01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/5), [B02](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/6), [D01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/10)
> 
> ## 완료 기준
> - [x] 직원 생성·수정·삭제가 적절한 이력을 남김
> - [x] 직원 변경 실패 시 이력만 남는 상황을 방지
> - [x] 부서 참조와 메모·IP 전달 확인
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-13"></a>

## #13 [F01][1조] 파일 메타데이터·다운로드 구현

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:34
- 닫힘: 2026-09-14 18:17
- 라벨: `박성욱` `신상엽`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/13

> ## 작업 정보
> - 담당 조: 1조
> - 담당 역할: 1조-①
> - 일정: 2026-09-14
> - 단계: 2단계 E·F
> - 선행 조건: [M02](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/milestone/2)
> 
> ## 완료 기준
> - [x] 파일명·형식·크기를 DB에 저장
> - [x] 메타데이터 ID로 파일 다운로드
> - [x] 이미지·CSV·로그에 공통으로 사용할 반환 형식 확인
> 
> ## 진행 메모
> F02와 같은 날 저장·다운로드 흐름을 연결합니다.
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-14"></a>

## #14 [F02][1조] 로컬 파일 저장·삭제 구현

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:34
- 닫힘: 2026-09-14 18:17
- 라벨: `신상엽`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/14

> ## 작업 정보
> - 담당 조: 1조
> - 담당 역할: 1조-②
> - 일정: 2026-09-14
> - 단계: 2단계 E·F
> - 선행 조건: [M02](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/milestone/2)
> 
> ## 완료 기준
> - [x] 실제 파일을 로컬 디스크에 저장
> - [x] 저장 경로·저장 결과를 F01과 연결
> - [x] 삭제·저장 실패 시 남은 파일 처리 방식 구현
> 
> ## 진행 메모
> E02가 생성하는 CSV를 메모리에 통째로 올리지 않고 저장할 수 있도록 연결합니다.
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-15"></a>

## #15 [F03][1조] 직원 프로필 이미지 연동 완료

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:34
- 닫힘: 2026-09-14 18:17
- 라벨: `박태양`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/15

> ## 작업 정보
> - 담당 조: 1조
> - 담당 역할: 1조-②
> - 일정: 2026-09-15
> - 단계: 2단계 E·F
> - 선행 조건: [F01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/13), [F02](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/14), [B01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/5), [B02](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/6)
> 
> ## 완료 기준
> - [x] 선택적 프로필 이미지 등록·조회
> - [x] 직원 수정의 이미지 처리 확인
> - [x] 직원 삭제 시 실제 프로필 파일도 삭제
> 
> ## 진행 메모
> 1단계에서 남긴 B의 파일 의존 부분을 여기서 완료합니다.
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-16"></a>

## #16 [F04][1조] CI·배포 환경 구성

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:34
- 닫힘: 2026-09-16 13:06
- 라벨: `박태양` `신상엽`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/16

> ## 작업 정보
> - 담당 조: 1조
> - 담당 역할: 1조-③
> - 일정: 2026-09-14 ~ 2026-09-15
> - 단계: 2단계 E·F
> - 선행 조건: [M02](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/milestone/2)
> 
> ## 완료 기준
> - [x] CI에서 빌드·테스트 실행
> - [x] 배포 환경에서 앱과 PostgreSQL 연결
> - [x] 업로드·백업 파일 경로와 저장 유지 방식 확인
> 
> ## 진행 메모
> Java/Spring Boot 버전과 배포 설정을 README에 기록합니다.
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-17"></a>

## #17 [E01][2조] 백업 필요 여부·진행 상태 구현

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:35
- 닫힘: 2026-09-14 18:18
- 라벨: `김어진`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/17

> ## 작업 정보
> - 담당 조: 2조
> - 담당 역할: 2조-③
> - 일정: 2026-09-14
> - 단계: 2단계 E·F
> - 선행 조건: [M02](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/milestone/2)
> 
> ## 완료 기준
> - [x] 최근 완료된 백업 이후 직원 변경 여부 판단
> - [x] 변경이 없으면 건너뜀 이력 저장
> - [x] 실행 중 API 조회에 진행중 상태가 보이도록 처리
> 
> ## 진행 메모
> 직원 삭제도 변경 판단에 반영할 수 있도록 D의 이력 정보를 검토합니다.
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-18"></a>

## #18 [E02][2조] 수동 백업·CSV 생성 구현

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:35
- 닫힘: 2026-09-16 14:31
- 라벨: `김어진`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/18

> ## 작업 정보
> - 담당 조: 2조
> - 담당 역할: 2조-①
> - 일정: 2026-09-14
> - 단계: 2단계 E·F
> - 선행 조건: [M02](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/milestone/2)
> 
> ## 완료 기준
> - [x] 전체 직원 정보를 CSV로 생성
> - [x] F01·F02와 연결해 수동 백업 파일 다운로드
> - [x] 처음부터 데이터를 나눠 읽고 순차 기록
> 
> ## 진행 메모
> 9/14에는 E01·F01·F02와 최소 성공 경로를 통합하고, 9/15 E06에서 대량·경계값 검증을 보강합니다.
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-19"></a>

## #19 [E03][2조] 백업 성공·실패·로그 처리 완성

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:35
- 닫힘: 2026-09-16 13:04
- 라벨: `김어진`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/19

> ## 작업 정보
> - 담당 조: 2조
> - 담당 역할: 2조-③
> - 일정: 2026-09-15
> - 단계: 2단계 E·F
> - 선행 조건: [E01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/17), [E02](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/18), [F01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/13), [F02](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/14)
> 
> ## 완료 기준
> - [x] 성공 시 완료·종료 시간·백업 파일 기록
> - [x] 실패 시 작업 중 파일 삭제
> - [x] 오류를 .log로 저장하고 실패·종료 시간·로그 파일 기록
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-20"></a>

## #20 [E04][2조] 자동 백업 스케줄러 구현

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:35
- 닫힘: 2026-09-16 13:04
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/20

> ## 작업 정보
> - 담당 조: 2조
> - 담당 역할: 2조-②
> - 일정: 2026-09-15
> - 단계: 2단계 E·F
> - 선행 조건: [E01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/17), [E02](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/18)
> 
> ## 완료 기준
> - [x] Spring Scheduler로 기본 1시간 주기 실행
> - [x] 주기를 애플리케이션 설정에서 주입
> - [x] 자동 백업 작업자는 system, 수동 작업자는 요청 IP
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-21"></a>

## #21 [E05][2조] 백업 검색·페이지네이션·최근 백업 조회

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:35
- 닫힘: 2026-09-16 13:04
- 라벨: `신상엽`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/21

> ## 작업 정보
> - 담당 조: 2조
> - 담당 역할: 2조-②
> - 일정: 2026-09-14 ~ 2026-09-15
> - 단계: 2단계 E·F
> - 선행 조건: [M02](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/milestone/2)
> 
> ## 완료 기준
> - [x] 작업자·시작 시간·상태 검색
> - [x] 시작/종료 시간 정렬과 페이지네이션
> - [x] 대시보드용 최근 백업 정보 API 확인
> 
> ## 진행 메모
> E01의 백업 이력 모델과 계약을 맞춰 병렬 구현합니다.
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-22"></a>

## #22 [E06][2조] 대량 CSV·메모리·경계값 검증

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:35
- 닫힘: 2026-09-16 18:08
- 라벨: `김어진`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/22

> ## 작업 정보
> - 담당 조: 2조
> - 담당 역할: 2조-①
> - 일정: 2026-09-15
> - 단계: 2단계 E·F
> - 선행 조건: [E02](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/18)
> 
> ## 완료 기준
> - [x] 대량 직원 데이터에서 메모리 사용 확인
> - [x] CSV의 쉼표·따옴표·줄바꿈·한글 처리 검증
> - [x] 빈 데이터·마지막 청크·행 누락/중복 확인
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-23"></a>

## #23 [F05][1조] 제공된 프론트엔드 연결 검증

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:36
- 닫힘: 2026-09-16 18:08
- 라벨: `박태양`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/23

> ## 작업 정보
> - 담당 조: 1조
> - 담당 역할: 1조-③
> - 일정: 2026-09-15
> - 단계: 2단계 E·F
> - 선행 조건: [F04](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/16), [F03](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/15), [E05](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/21)
> 
> ## 완료 기준
> - [x] 제공된 프론트엔드에서 직원·부서 화면 확인
> - [x] 대시보드가 C·D·E의 독립 API를 사용
> - [x] 백업 상태·파일 다운로드·오류 응답 표시 확인
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-24"></a>

## #24 [T01][공동] 전체 시나리오 통합 테스트

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:36
- 닫힘: 2026-09-16 18:07
- 라벨: `박태양` `김어진` `조예준` `박성욱` `신상엽` `정수환`
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/24

> ## 작업 정보
> - 담당 조: 공동
> - 담당 역할: 전원
> - 일정: 2026-09-16
> - 단계: 통합·제출
> - 선행 조건: [M04](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/milestone/4)
> 
> ## 완료 기준
> - [x] 부서 → 직원 등록·수정·퇴사·삭제 → 이력 확인
> - [x] 직원 변경 → 백업 → 파일 다운로드 → 대시보드 확인
> - [x] 중복·없는 ID·빈 결과·페이지 경계·백업 실패 검증
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-25"></a>

## #25 [T02][공동] 통합 오류 수정·최종 배포 확인

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: ✅ 완료
- 생성: 2026-09-09 17:36
- 닫힘: 2026-09-17 11:40
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/25

> ## 작업 정보
> - 담당 조: 공동
> - 담당 역할: 전원
> - 일정: 2026-09-16
> - 단계: 통합·제출
> - 선행 조건: [T01](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/issues/24)
> 
> ## 완료 기준
> - [x] 발견된 필수 기능 오류를 담당 조가 수정
> - [x] 수정 후 관련 흐름 재검증
> - [x] 제출용 main 병합과 배포 버전 동작 확인
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

<a id="issue-26"></a>

## #26 [T03][공동] README·발표·제출 자료 정리

- 작성자: [parksunovo](https://github.com/parksunovo)
- 상태: 🟢 열림
- 생성: 2026-09-09 17:36
- 원본: https://github.com/sb14-turtles/sb14-HRBank-turtles/issues/26

> ## 작업 정보
> - 담당 조: 공동
> - 담당 역할: 전원
> - 일정: 2026-09-16
> - 단계: 통합·제출
> - 선행 조건: [M04](https://github.com/sb14-HRBank-team2/sb14-HRBank-team2/milestone/4)
> 
> ## 완료 기준
> - [ ] 실행 방법·환경변수·배포 정보 정리
> - [ ] ERD·담당 역할·핵심 구현 및 검증 결과 정리
> - [ ] 시연 순서·제출 링크·버전 확인
> 
> ## 검증 및 연결
> - [ ] 완료 기준 검증 및 팀원 리뷰
> - [ ] 관련 문서 또는 PR 링크 기록
> 
> [노션 프로젝트](https://app.notion.com/p/3d672256d2ca81cbb423e72765f0a032) · [HR Bank 명세](https://codeit.notion.site/3186fd228e8d8014950edd8a71610a6c)

[↑ 목록으로](#목록)

---

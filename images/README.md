# 사진·영상 목록

사장님이 보내주신 사진·영상을 최적화(리사이즈·용량 축소)해서 넣어 두었습니다.
같은 파일명으로 덮어쓰면 교체됩니다.

## 사진 (`images/`)

| 파일명 | 어디에 나오나 | 현재 내용 |
|---|---|---|
| `logo.png` | 상단 로고 · 첫 화면 오버레이 | 소개 영상 엔딩 로고에서 추출한 THE CHAMP GYM 로고(투명 배경, v6 — 독수리 몸통까지 완전한 형태) |
| `favicon.png` | 브라우저 탭 아이콘 | 로고 기반 |
| `women-poster.jpg` | **첫 화면** 영상 poster·대체 이미지 + 데스크톱 흐린 배경, `#members` 하이라이트 poster | 헤비백 훈련 장면 정지 프레임 |
| `og-image.jpg` | 카카오톡·네이버 등 링크 공유 미리보기 (`og:image`, 1200×630) | 헤비백 훈련 장면 (가로 규격으로 재구성) |
| `hero-poster.jpg` | `#video` 섹션 큰 영상(`class-reel.mp4`) poster | 코치 미트 훈련 장면 |
| `entrance-poster.jpg` | `#video` 섹션 입구 워크스루 영상 poster | 영상에서 추출한 정지 프레임 |
| `welcome-poster.jpg` | `#coaches` 인사 영상 poster | 인사 영상에서 추출한 정지 프레임 |
| `coach-lim.jpg` | `#coaches` 임채민 관장 카드 | JTBC 소개 카드에서 잘라낸 관장님 사진 (방송 자막으로 본인 확인) |
| `gym-01.jpg` | `#members` 배경(흐림) + 단체 스냅 | 회원·코치진 단체 사진 |
| `gym-04.jpg` | `#contact` 배경(흐림) | 체육관 사진 |
| `gym-05.jpg` | `#community` 스냅 | 다이어트 콘테스트 |
| `gym-06.jpg` | `#schedule` 시설 스냅 | 운동복·수건 선반 |
| `gym-07.jpg` | `#schedule` 시설 스냅 | 탈의실·사물함 |
| `gym-08.jpg` | `#schedule` 시설 스냅 | 샤워실 |
| `m-evening.jpg` | `#members` 첫 카드 | 사람 많은 저녁 수업 |
| `m-action.jpg` | `#members` 스냅 | 코치가 미트 훈련 직접 지도 |
| `m-class-group.jpg` | `#members` 스냅 | 글러브 든 수업 단체 사진 |
| `m-smile.jpg` | `#members` 스냅 | 밝게 웃는 수업 단체 사진 |
| `c-competition.jpg` | `#community` 스냅 | 용산구청장배 출전 |
| `c-hiking.jpg` | `#community` 스냅 | 청계산 등산 크루 |
| `c-nightrun.jpg` | `#community` 스냅 | 나이트 러닝 크루 |
| `card-50min.jpg` | `#video` 스냅 | "50분 운동 700칼로리" 안내 카드 |
| `card-poster01.jpg` | `#video` 스냅 | "오래 다니는 이유" 안내 카드 |
| `card-grouppt.jpg` | `#video` 스냅 | "그룹 PT인데 개인 PT 같아요" 안내 카드 |
| `card-poster03.jpg` | `#video` 스냅 | "코치 수가 다릅니다" 안내 카드 |
| `card-review.jpg` | `#members` 스냅 | "재등록률이 말해줍니다" 안내 카드 |
| `card-jtbc.jpg` | `#coaches` JTBC 소개 카드 | JTBC 출연 소개 카드 |
| `card-trial.jpg` | `#community` 스냅 | 무료체험 안내 카드 |

> `hero.jpg`, `gym-02.jpg`, `gym-03.jpg` 는 현재 `index.html` 어디에서도 쓰이지 않는
> 미사용 파일입니다(과거 버전에서 남은 파일). 삭제해도 사이트에는 영향 없습니다.

권장: 한 장당 1MB 이하(JPG), 가로 1600px 정도면 충분합니다.
EVOTO 워터마크가 있는 사진(코치 프로필, 무료/체험 홍보컷 등)은 절대 올리지 마세요 —
최종 워터마크 없는 촬영본이 오면 그때 반영합니다.

## 영상 (`videos/`)

| 파일명 | 어디에 나오나 | 현재 내용 |
|---|---|---|
| `hero-reel.mp4` | **첫 화면** (자동재생·무음·반복) | 회원 헤비백 훈련 → 수업 마지막 다 같이 "화이팅" (4초) |
| `class-reel.mp4` | `#video` 섹션 큰 자리 (클릭 재생) | 코치와 미트 훈련하는 실제 수업 영상(HD) — 저녁 수업 영상 도착 시 교체 |
| `entrance-reel.mp4` | `#video` 섹션 스냅(클릭 재생) | 입구부터 한 바퀴 둘러보는 워크스루 영상 |
| `women-highlight.mp4` | `#members` 상단 하이라이트 (자동재생·무음·반복) | 입구 영상에서 편집한 5초 하이라이트 — 헤비백 훈련 → 케틀벨 → 다 같이 "화이팅" |
| `welcome.mp4` | `#coaches` 인사 영상 (클릭 재생) | 입구 영상에서 편집한 3초 인사 — "안녕하세요 더챔프복싱입니다" |

대기 중: **사람 많은 저녁 수업 영상** — `#video` 섹션 상단 큰 자리(`.video-main`)에
들어갈 예정이며, 도착하면 위와 같은 방식으로 `videos/` 에 추가하고 `index.html` 의
`[수정]` 주석 자리에 연결하면 됩니다.

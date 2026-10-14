# 수집 요청 (hntr 오피스)

이 폴더에 요청 파일을 올리면 「hntr 수집 (공개 저장소에서 무료로 실행)」 작업이 돌고,
결과는 비공개 저장소 hntrzip/threads-autopost 로 넘어간다. 처리한 요청 파일은 작업이 지운다.

| 파일 | 한 줄 형식 | 결과 (비공개 저장소) |
|---|---|---|
| photo_search.txt | `접두어 검색어` | posts/instagram/images/cand/ |
| fetch.txt | `파일명 URL` | posts/instagram/images/ |
| trend.txt | `이름 키워드1,키워드2` | posts/instagram/web/trend.txt |

공개 저장소라 요청 내용과 작업 기록은 누구나 볼 수 있다. 기사 본문 덤프(web.txt)는 여기서 하지 않는다.

# blog-assets

[윈도우 서버 보안 노트](https://winsec-notes.blogspot.com/) 에서 사용하는 이미지 저장소입니다.

블로그 본문에 들어가는 썸네일과 다이어그램을 여기에 두고, jsDelivr CDN으로 불러다 씁니다.
Blogger API에는 이미지 업로드 엔드포인트가 없어서 이런 구조가 됐습니다.

```
https://cdn.jsdelivr.net/gh/Woodee999/blog-assets@main/<파일명>
```

## 블로그 소개

Windows 클라이언트·서버 운영과 취약점 대응을 다룹니다.

- [전체 글 목차](https://winsec-notes.blogspot.com/p/blog-page_787.html)
- [소개](https://winsec-notes.blogspot.com/p/blog-page_02.html)

모든 글은 검증 환경(운영체제 버전과 빌드, 확인 시점)을 본문 앞부분에 밝히고,
CVE 번호·KB 번호·이벤트 ID처럼 틀리면 안 되는 값은 Microsoft Learn, MSRC, NVD, CISA에서
대조한 뒤에만 씁니다. 취약점은 방어 관점으로만 다루며 재현 절차나 공격 코드는 싣지 않습니다.

## 파일 이름 규칙

| 종류 | 형식 |
|---|---|
| 썸네일 | `{날짜}_{슬러그}_thumb.png` (1200×630) |
| 다이어그램 | `{날짜}_{슬러그}_diag{n}.svg` (800×450) |
| 차트 | `{날짜}_{슬러그}_chart{n}.png` |

썸네일은 글 프론트매터를 읽어 자동 생성하고, 다이어그램은 SVG로 직접 작성합니다.

## 라이선스

이미지는 모두 직접 제작한 것입니다. 출처를 밝히면 자유롭게 쓰셔도 됩니다.

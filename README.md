# ntc2027 — 정기 정수론 학회 2027

이 폴더는 학회 홈페이지 한 개의 원본입니다.

- `conference.json` — 홈페이지에 표시되는 모든 내용(한/영). 이 파일만 고치면 됩니다.
- `assets/` — 대표 사진(`hero.jpg`), 포스터(`poster.pdf`), 단체사진, 후원기관 로고 등
- `index.html` — 빌드 결과물. 직접 고치지 말고 아래 명령으로 다시 만듭니다.

```bash
python3 scripts/validate.py sites/ntc2027/conference.json   # 내용 검사
python3 scripts/build.py sites/ntc2027 --deploy dist/ntc2027  # 빌드 + 배포 폴더 생성
```

## 아직 채워야 할 항목

`conference.json` 맨 아래 `_todo` 목록을 보세요. `validate.py` 를 실행하면 `[확인 필요]` 경고로도 출력됩니다.

## 출처

- 행사 정보: 김도형 교수 안내 메일(2026-10)
- 조직위원 영문 표기: 각 대학 교수 소개 페이지·논문 저자 표기에서 확인 (미확인은 비워 둠)

배포(GitHub Pages) 방법은 저장소 루트의 `references/hosting.md` 를 참고하세요.

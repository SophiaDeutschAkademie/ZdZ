# Zwischen den Zeilen

Sophia Deutsch Akademie 독해 텍스트 모음입니다. `index.html`이 목차이고, 텍스트는 `texte/` 폴더에 있습니다.

- 텍스트에서 고른 답(빈칸, richtig/falsch)은 브라우저에 저장되어 다시 열면 되살아납니다(localStorage `zdz-ans:텍스트 파일 이름`, 각 텍스트의 `zsave()`). 새 텍스트도 같은 코드를 씁니다.
- 학습 포탈에 로그인한 학생의 답은 학습 저장(`<script id="soda-sync" src="/SODA-LERNPORTAL/sync.js"></script>`, 각 텍스트의 `<meta charset>` 바로 뒤)이 서버에 올려 다른 기기에서도 이어집니다. 자세한 내용은 SODA-LERNPORTAL README의 「학습 기록 자동 저장」에 있습니다.
- 레벨: 목차(`inhalt.html`)는 A2–B1 / B2 탭으로 나뉩니다. A2–B1은 `texte/01-…` ~ `14-…`, B2는 `texte/b2-01-…`처럼 `b2-` 접두어를 붙입니다(옛 `b2c1-` 주소는 새 주소로 자동 연결). 텍스트의 집 모양 버튼은 `../inhalt.html#a2-b1` 또는 `#b2`로 해당 탭에 돌아갑니다.
- B2 빈칸: 보기 4개, 한 텍스트에 내용·논리로 푸는 빈칸 4개 이상. 8편 전체에서 같은 정답 낱말과 같은 문법 항목이 겹치지 않도록 `b2-luecken.json`에 모든 빈칸(텍스트, 번호, 분류, 정답, 보기)을 기록합니다. 새 B2 텍스트를 만들 때 이 목록과 겹치지 않게 빈칸을 고르고 목록에 추가합니다.

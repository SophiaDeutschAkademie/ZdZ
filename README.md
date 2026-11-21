# Zwischen den Zeilen

Sophia Deutsch Akademie 독해 텍스트 모음입니다. `index.html`이 목차이고, 텍스트는 `texte/` 폴더에 있습니다.

- 텍스트에서 고른 답(빈칸, richtig/falsch)은 브라우저에 저장되어 다시 열면 되살아납니다(localStorage `zdz-ans:텍스트 파일 이름`, 각 텍스트의 `zsave()`). 새 텍스트도 같은 코드를 씁니다.
- 학습 포탈에 로그인한 학생의 답은 학습 저장(`<script id="soda-sync" src="/SODA-LERNPORTAL/sync.js"></script>`, 각 텍스트의 `<meta charset>` 바로 뒤)이 서버에 올려 다른 기기에서도 이어집니다. 자세한 내용은 SODA-LERNPORTAL README의 「학습 기록 자동 저장」에 있습니다.
- 레벨: 목차(`inhalt.html`)는 A2–B1 / B2–C1 탭으로 나뉩니다. A2–B1은 `texte/01-…` ~ `14-…`, B2–C1은 `texte/b2c1-01-…`처럼 `b2c1-` 접두어를 붙입니다. 텍스트의 집 모양 버튼은 `../inhalt.html#a2-b1` 또는 `#b2-c1`로 해당 탭에 돌아갑니다.

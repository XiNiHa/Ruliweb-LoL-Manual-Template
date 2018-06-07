# Ruliweb-LoL-Manual-Template
[(미리보기)](https://anesin1109.github.io/ruliweb-lol-manual-template/)
루리웹을 위한 롤 공략 틀입니다. 다른 곳에서 사용하셔도 문제는 없습니다.

## 사용 방법
1. [(공략 업로더)](https://anesin1109.github.io/manual-uploader/)에 접속합니다.
2. 아래 방법대로 내용을 수정합니다.
3. 챔피언을 선택하고, 이름을 정한 후 업로드를 누릅니다.
4. 잠시 후 나타나는 ID를 복사한 후, 메모장 등에 옮겨 저장합니다.(분실 시 공략 이름과 함께 저에게 메일 주세요 - anesin1109@naver.com)
5. 루리웹 글쓰기 창에서 좌측 하단의 <>를 눌러 소스 코드 편집 모드로 넘어간 후, 다음 소스를 기록합니다.
`<iframe src="https://us-central1-ruliweb-lol-manual-manager.cloudfunctions.net/getManual?id=<공략 ID>" style="width: 100%; height: 100%"></iframe>`
6. <공략 ID>를 아까 복사해둔 ID로 바꿉니다.
7. 나중에 공략을 수정할 시, 공략 업로더에 복사해둔 ID를 붙여넣은 후 업로드하면 글이 업데이트됩니다.

### 머리말 넣기
원본 기준 20번째 줄에 있는 "여기는 머리말입니다." 위치에 글을 써넣으시면 됩니다.

### 룬 넣기
룬 정보 생성기[(링크)](https://anesin1109.github.io/rune-generator/)으로 만든 룬 정보를 원본 기준 31번째 줄에 붙여넣으시고, 그 아래 "추가 설명은 여기 적으시면 됩니다."에 글을 써넣으시면 됩니다.

### 스펠 넣기
아래쪽에 있는 "각종 아이콘 삽입 방법"을 이용해 스펠 아이콘을 골라서, 원본 기준 38번째 줄에 붙여넣으시고 내용을 쓰시면 됩니다.

### 스킬 넣기
스킬 정보 생성기[(추후 업데이트 예정)](#)으로 만든 스킬 정보를 원본 기준 44번째 줄에 붙여넣으시고, 그 아래 추가 설명을 적으시면 됩니다.

### 아이템 넣기
아이템 정보 생성기[(추후 업데이트 예정)](#)으로 만든 아이템 정보를 원본 기준 52번째 줄에 붙여넣으시고, 그 아래 추가 설명을 적으시면 됩니다.

### 카운터픽 넣기
원본 기준 61번째 줄부터 68번째 줄까지가 1명의 챔피언을 나타냅니다. 원하는 수만큼 복사&붙여넣기하시고, 원본 기준 63번째 줄의 주소를 [챔피언 아이콘](http://leagueoflegends.wikia.com/wiki/Category:Champion_squares)에서 따온 주소로 바꾸시고(각종 아이콘 삽입 방법 참고), 이름을 바꿔 넣으신 후, 원본 기준 66번째 줄에 글을 적으시면 됩니다. 상대하기 쉬운 챔피언도 72번째 줄에서 79번째 줄까지의 부분으로 같은 방법으로 가능합니다.

### 챔피언별 상대법 넣기
원본 기준 84\~109번째 줄이 1명의 챔피언을 나타냅니다.
먼저 원본 기준 87번째 줄의 주소를 [챔피언 아이콘](http://leagueoflegends.wikia.com/wiki/Category:Champion_squares)에서 선택한 주소로 바꾸고, 챔피언 이름과 별 수를 바꿉니다.
92번과 93번의 주소를 [스펠 아이콘](http://leagueoflegends.wikia.com/wiki/Category:Summoner_spell_icons)에서 선택한 주소로 바꿉니다.
97\~102번의 주소를 [아이템 아이콘](http://leagueoflegends.wikia.com/wiki/Category:Item_icons)에서 선택한 주소로 바꿉니다.
107번에 상대법을 적으시면 됩니다.

### 추가 공략 넣기
113번째 줄에 넣으시면 됩니다.

### 각종 아이콘 삽입 방법
1. 업로더를 열고, 아이콘을 삽입하고자 하는 곳에 커서를 위치합니다.
2. 코드 부분 하단의 챔피언/스킬/스펠/아이템 중 원하는 것을 클릭합니다.
3. 아이템의 경우 원하는 챔피언을 선택합니다.
4. 나타나는 아이콘을 클릭합니다.
5. 삽입이 완료됩니다. 완료 버튼을 눌러 삽입 창을 닫습니다.

## 기여하고 싶다면?
이슈 등록, PR 환영합니다.
- Indentation은 2칸입니다.
- 클래스 이름 중복을 막기 위해 모든 클래스는 manual_로 시작합니다.
- 클래스 이름 띄어쓰기는 -로 표시합니다.
- 레이아웃에는 Flexbox 사용을 권장합니다.

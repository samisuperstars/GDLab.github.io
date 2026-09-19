# samisuperstars.github.io

samisuperstars.github.io
개인 홈페이지입니다. HTML/CSS를 몰라도 _data/portfolio.yml 파일만 수정하면 대부분의 내용을 바꿀 수 있도록 만들어져 있습니다.

기본 원리
화면에 보이는 글자, 사진 경로, 논문 목록, 메뉴 버튼 등은 모두 _data/portfolio.yml 안에 들어 있습니다.
index.html은 그 내용을 화면에 그려주는 "틀"이라서, 평소에는 건드릴 필요가 없습니다.
파일을 고치고 GitHub에 저장(commit)하면 1~2분 안에 실제 사이트(https://samisuperstars.github.io)에 자동으로 반영됩니다.
수정하는 방법 (공통)
GitHub 저장소 페이지에서 고치고 싶은 파일(_data/portfolio.yml 등)을 클릭합니다.
오른쪽 위 연필 아이콘(✏️, "Edit this file")을 클릭합니다.
내용을 수정합니다.
화면 아래로 내려가서 "Commit changes..." 버튼을 눌러 저장합니다.
1~2분 기다린 후 사이트를 새로고침하면 반영되어 있습니다.
컴퓨터에 git을 설치하거나 별도 프로그램을 깔 필요가 없습니다.

자주 하는 작업
1. 글(소개, 연구분야 설명 등) 수정
_data/portfolio.yml에서 해당 텍스트를 찾아 따옴표(" ") 안의 내용만 바꿔주세요. 예) hero_title, home_description, biography 등.

2. 사진 교체
assets/images 폴더로 들어갑니다.
새 사진을 같은 파일 이름(profile.jpg, lab.jpg 등)으로 업로드하면 자동으로 기존 사진을 덮어씁니다.
파일 이름을 다르게 하고 싶다면, _data/portfolio.yml의 profile_image / home_lab_image 값도 새 파일명으로 같이 바꿔주세요.

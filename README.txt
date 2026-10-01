변기즈 공식 홈페이지 배포 안내

1) index.html을 GitHub 저장소의 루트에 업로드합니다.
2) 단체 일러스트를 assets/group.jpg로 넣으려면 index.html의 갤러리 안내 영역을 실제 이미지 태그로 바꾸면 됩니다.
3) 배경음악 파일을 assets/bgm.mp3 경로로 추가하세요. 브라우저 정책상 자동 재생은 제한될 수 있어 방문자가 재생 버튼을 누르는 방식입니다.
4) index.html 하단 script의 profiles 객체에 각 멤버의 Spoon 프로필 URL을 입력하세요.
   const profiles = { kodiak: 'URL', okdal: 'URL', saengmyeong: 'URL' };
5) GitHub 저장소 Settings > Pages에서 배포 브랜치와 루트(/)를 선택하면 됩니다.

현재 프로필 URL과 실제 단체 일러스트/음원 파일이 제공되지 않아 연결용 자리표시자로 구성했습니다.
반응형 레이아웃, 방문 환영 애니메이션, 멤버 카드, BGM 버튼은 포함되어 있습니다.

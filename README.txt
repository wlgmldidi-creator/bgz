변기즈 공식 홈페이지 배포 안내

1) index.html과 assets 폴더 전체를 GitHub 저장소 bgz의 배포 루트에 함께 업로드합니다.
   이 버전은 GitHub Pages 주소 https://wlgmldidi-creator.github.io/bgz/ 를 기준으로 경로를 지정했습니다.
2) assets 폴더에 포함된 group-1.png~group-5.png와 kodiak.png, okdal.png, saengmyeong.png를 그대로 유지하세요.
3) 배경음악 파일을 assets/bgm.mp3 경로로 추가하세요. 브라우저 정책상 자동 재생은 제한될 수 있어 방문자가 재생 버튼을 누르는 방식입니다.
4) index.html 하단 script의 profiles 객체에 각 멤버의 Spoon 프로필 URL을 입력하세요.
   const profiles = { kodiak: 'URL', okdal: 'URL', saengmyeong: 'URL' };
5) GitHub 저장소 Settings > Pages에서 배포 브랜치와 루트(/)를 선택하면 됩니다.

방송 프로필 URL과 bgm.mp3는 아직 설정되지 않았습니다. 이미지 8장은 assets 폴더에 포함되어 있습니다.
반응형 레이아웃, 방문 환영 애니메이션, 멤버 카드, BGM 버튼은 포함되어 있습니다.

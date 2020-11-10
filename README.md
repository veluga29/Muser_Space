# "Muser Space" - Muser들의 음악공간
## * Muser: Music + User, 음악을 이용(Play or Listen)하는 모든 사람들
</br>
<div><img src="https://user-images.githubusercontent.com/26553265/98662608-619c6d80-238b-11eb-9884-da8ea62f8d7f.png" width=500></div>

### 사용한 기술 스택
- HTML / CSS
- Javascript
- Ruby on Rails 
- AWS S3, EC2

### 기능 구현
- 회원정보 및 음원, 영상, 댓글 등의 게시글 올리기 기능을 CRUD를 기반으로 구현
- AWS S3 Storage에 연결시켜 프로필 사진, 앨범 사진, 음원, 공연 영상들을 업로드할 수 있게 구현
- 오픈소스 오디오 라이브러리 Howler.js를 사용해, 음악 플레이어를 사용한 음원 감상 구현
- HTML 환경에서 영상 시청 구현
- 회원가입 및 로그인 기능 구현
- 조회수, 좋아요(Like) 기능 구현 및 조회수, 좋아요 개수를 기반으로 한 뮤즈 차트(랭킹 차트) 구현
- 음원 및 영상 상세페이지 댓글 구현 (감상평, 응원 등을 남길 수 있음)
- AWS EC2 서버에 배포

### 페이지 구현
- index(홈페이지)에서는 최신 음악, 뮤즈 차트, 인기영상으로 UI 구성
- 창작 / 커버(원곡 Cover 영상)/ 공연(공연 영상) 3가지 카테고리에서 음원 및 음악 영상을 올릴 수 있게 각각의 페이지 구현
- My page에서 프로필(사진, 닉네임, 상세정보)등을 업로드 및 수정하고, 게시글을 올린 다른 유저의 프로필 페이지도 볼 수 있게 구현
</br>

<div style="text-align : center;"><img src="https://user-images.githubusercontent.com/26553265/98434778-0d3c8800-2116-11eb-8f5e-b384d7ca830b.png" width=800 ></div></br></br>
<div style="text-align : center;"><img src="https://user-images.githubusercontent.com/26553265/98434794-365d1880-2116-11eb-9fd0-549dca9dde96.png" width=800></div></br></br>
<div style="text-align : center;"><img src="https://user-images.githubusercontent.com/26553265/98434799-44129e00-2116-11eb-871b-5370a01eed81.png" width=800></div></br></br>

# Group Project(SharePic)

1. 만들게 된 동기
   - 요즘에는 네컷 사진관이라 하여 많은 분들이 직접적으로 사진을 찍어 sns 등에 올리고는 합니다.
하지만 instagram이나 facebook 같은 종합적인 sns는 있어도, tictok 같은 동영상 위주의 sns 같은
사진관 위주의 sns나 홈페이지는 없을 거라는 생각에 만들게 되었습니다.
보다 쉽게 사용자 근처의 사진관을 검색하고, 보다 쉽게 브랜드 별로 다양한 프레임과 가격을 비교할 수 있으며,
촬영한 사진을 공유함으로써 요즘의 트렌드가 무엇인지 한 눈에 볼 수 있을 겁니다.

2. 초기 디자인
![KakaoTalk_20230531_152630736](https://github.com/Heo-sh/PhotoPreject-complete-/assets/117993171/45993b9a-d442-4cf7-9f5c-c2be798cbd34)
![KakaoTalk_20230531_150601624_04](https://github.com/Heo-sh/PhotoPreject-complete-/assets/117993171/c52f9800-62c3-462b-aac9-952e510fe177)
![KakaoTalk_20230531_150601624_03](https://github.com/Heo-sh/PhotoPreject-complete-/assets/117993171/c7a94c9e-2b86-4ec6-ab8f-a7dc83ffb51a)
![KakaoTalk_20230531_150601624_02](https://github.com/Heo-sh/PhotoPreject-complete-/assets/117993171/c0bcda7e-1ebb-46e5-8ad7-c2e14eaa9f4a)
![KakaoTalk_20230531_150601624_01](https://github.com/Heo-sh/PhotoPreject-complete-/assets/117993171/c0fef9c2-7411-4109-b14a-d49b1998c7fd)
![KakaoTalk_20230531_150601624](https://github.com/Heo-sh/PhotoPreject-complete-/assets/117993171/0f85bc72-01e2-4fb0-a1b3-292caaef9fa4)
처음 프로젝트 회의에서 나온 초기 디자인은 이렇습니다.
페이지는 크게는 6페이지로 분류됩니다.
메인과 소개, 위치, 프레임을 보여주는 페이지와, 게시판, 그리고 사진에는 보여지지 않지만
회원정보를 담고 있는 마이 페이지로 구성이 되어있습니다.
지금 보시는 사진과 비슷한 부분이 많이 보이실 겁니다.

3. 구현 설명
   - 기능의 구현 설명입니다.
기능을 구현하기 위해 6개의 Table을 만들었으며, primary key와 foreign key 등을 이용하여 관계성을 주었습니다.
다이어그램으로 보여지는 테이블들입니다.
회원관리를 위한 ProMember 테이블과
게시물을 위한 PBoard,
사진의 정보를 담기 위한 prophoto,
댓글을 위한 comment가 있으며,
저희가 원하는 장소의 위치만 띄워주기 위한 map 테이블과
브랜드만을 관리하기 위한 brandname 을 만들었습니다.
또한, 게시물과 사진의 data를 조인한 view를 만들어 게시물의 내용과 사진을 동시에 보여주게 만들었습니다.


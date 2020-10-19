# MLBPark Stylish Source Code

개인 Stylish 코드 저장용 (광고 제거, 스타일링 등)

<details>
<summary>코드 보기</summary>

```css
/* 맥에서 폰트 설정 */
#contentDetail, span {
    font-family: "돋움", Dotum, sans-serif, Arial;
}

/*광고 제거*/
.top_ad,
#left_ad,
#center_ad02,
.plus,
.naver_power,
#right_cont {
  display: none;
}

.list_search + div {
  display: none;
}

.view_context + div {
  display: none;
}

/*최하단 레이아웃제거

.footer {display: none;}*/
/*담장 제목 제거

.main_contents .tit_today {

display:none;

}*/
/*layout 크기*/
.index {
  width: 100%;

  min-width: 900px;
}

.index {
  background: #ffffff;
}

.index #PCHeader .bg .gnb {
  width: 900px;

  margin: auto;
}

.index #container {
  width: 900px;

  margin: auto;
}

.index #container .contents {
  width: 900px;

  margin: auto;
}

/*Today best bullpen 레이아웃*/
.main_contents .tit_today {
  width: 880px;

  /* "layout px"-20=width */
  height: 53px;

  line-height: 53px;

  color: #ec4908;

  font-size: 22px;

  font-weight: bold;

  border-bottom: 1px solid #ebebeb;

  background: #fafafa;

  vertical-align: middle;

  padding: 0 10px;

  letter-spacing: -1px;
}

/*상하단바 배경색*/
.footer,
.index #PCHeader .bg {
  background: #5181e3;
}

/*메뉴및 로고 */
.index #PCHeader .main_menu .logo {
  padding: 15px 0px 0 0;

  width: 50px;
}

/* 빅툰 상단 메뉴 제거 */
.index #PCHeader .main_menu .list_menu li .top09 {
  display: none;
}

/*상단 메뉴 넓이*/
.index #PCHeader .main_menu {
  width: 900px;

  position: relative;

  margin: auto;

  padding: 0 0 0 0;
}

/*상단 글쓰기 검색 버튼*/
.index #PCHeader .btn_box {
  width: 80px;

  position: relative;

  margin: auto;

  padding: 0 0 0 0;
}

/*글 상단 추천 조회 리플 위치*/
.index #container .contents .left_cont .view_head .text {
  width: 860px;
}

/*게시판 넓이*/
.left_cont table {
  width: 900px !important;
}

/*게시물 창 넓이*/
.index #container .contents .left_cont {
  /* position: relative; */
  /* float: left; */
  width: 900px;

  margin: auto;
}

/*담장*/
.today_layer_obj {
  width: 900px;

  position: relative;

  margin: auto;

  margin-bottom: 10px;

  /*하단 여백*/
  padding: 0 0 0 0;
}

.lists_today_contxt {
  width: 900px;
}

.lists_today_contxt > div {
  width: 100%;
}

.main_contents .nav li {
  width: 264px;
}

.lists_today {
  width: 264px;
}

/*담장 텍스트 조정*/
.lists_today .items .text .title a {
  width: 262px !important;

  /* ("layout px" -108)/3=width */
  text-overflow: ellipsis;

  overflow: hidden;

  white-space: nowrap;
}

/*이전 게시판*/
.prev_list {
  margin: 10px 1px;
}

/*텍스트조정*/
/*게시물번호색조정*/
.tbl_type01 tbody tr td {
  height: 36px;

  border-top: 1px solid #ededed;

  text-align: center;

  vertical-align: middle;

  color: #999;
}

.tbl_type01 tbody tr {
  height: 36px;
}

/*한줄씩 색깔구분*/
.tbl_type01 tr:nth-child(odd) {
  background-color: #fff;
}

.tbl_type01 tr:nth-child(even) {
  background-color: #f9f9f9;
}

.tbl_type01 tr:hover {
  background-color: #e0f0ff;
}

/*말머리 괄호*/
.tbl_type01 tbody tr td .word:before {
  content: "[";
}

.tbl_type01 tbody tr td .word:after {
  content: "]";
}

/*말머리 색 조정*/
.tbl_type01 tbody tr td .word,
.main_contents .nav .bestTitle {
  color: #25a;
}

/*게시물 제목*/
.tbl_type01 tbody tr td {
  padding: 0 4px 0 0;
}

.tbl_type01 tbody tr td:nth-child(3) {
  width: 110px;
}

.tbl_type01 tbody tr td a:visited {
  color: #999;
}

/*조회수 텍스트 설정*/
.tbl_type01 .viewV {
  padding-right: 5px;

  font-weight: bold;

  color: #242424;
}

/*댓글수 색 조정*/
.tbl_type01 .replycnt {
  color: #ec4908;

  font-weight: bold;
}

/*댓글입력박스*/
#contentTable {
  width: 95%;

  margin: 0 0 0 30px;
}

#center_ad01,
.right_menu,
.picture {
  display: none;
}

/*댓글 레이아웃 배경*/
.reply_list {
  padding: 10px 0px 10px 0px;
}

/*타인 댓글 설정*/
/*타인 댓글 한줄씩 색구분*/
.reply_list .other_reply .txt:nth-child(odd) {
  position: relative;

  float: left;

  max-width: 90%;

  padding: 15px 10px;

  background: rgba(255, 255, 255, 0);

  border-radius: 0 10px 10px 10px;

  text-overflow: ellipsis;

  text-align: left;

  font-family: "굴림", "Gulim";
}

.reply_list .other_con:nth-child(odd) {
  overflow: hidden;

  position: relative;

  margin: 0 0 0 0;

  padding: 6px 0 6px 55px;

  background: #f7f7f7;
}

.reply_list .other_con:nth-child(even) {
  overflow: hidden;

  position: relative;

  margin: 0 0 0 0;

  padding: 6px 0 6px 55px;

  background: #fff;
}

.reply_list .other_con .txt .icon_arr {
  display: none;
}

.reply_list,
#cmtFormTable td {
  background: #9bbad8 !important;
}

.reply_list .other_reply .txt span,
.tbl_type01 thead tr td {
  color: #000;
}

.reply_list,
#cmtFormTable td {
  background: #f7f7f7 !important;
}

.reply_list .other_reply .txt,
.reply_list .other_con .txt .icon_arr,
.reply_list .my_reply .txt {
  background: #f7f7f7;
}

/*타인 댓글 포토사진*/
.reply_list .other_con .photo img {
  position: absolute;

  left: 10px;

  border-radius: 20%;

  border: 1px solid #ddd;
}

.reply_list .other_con .photo {
  position: absolute;

  top: 10px;

  left: 0;

  width: 37px;

  height: 37px;

  border-radius: 100%;

  border: 0px solid #bfbfbf;
}

/*타인 댓글 경계선*/
.reply_list .other_con {
  border-bottom: 1px solid #ccc;
}

/*타인 닉네임 설정*/
.reply_list .other_reply .txt_box .name {
  color: #5181e3;

  font-weight: bold;
}

/*본인 댓글 설정*/
/*본인 닉네임 설정*/
.reply_list .my_reply .txt_box .name {
  color: #000;

  font-weight: bold;
}

.reply_list .my_con {
  border-bottom: 1px solid #ccc;
}

/*본인 댓글 배경색 및 위치*/
.reply_list .my_con {
  overflow: hidden;

  position: relative;

  margin: 0 0 0 0;

  padding: 6px 0 6px 55px;

  background: #ffffe4;
}

.reply_list .my_reply .txt {
  float: left;

  background: rgba(255, 255, 255, 0);
}

.reply_list .my_con .photo {
  position: absolute;

  top: 10px;

  left: 10px;

  width: 37px;

  height: 37px;

  border-radius: 20%;

  border: 1px solid #bfbfbf;
}

.reply_list .ip {
  display: inline;
}

.txt {
  margin-top: -10px;

  margin-bottom: -10px;
}

.tbl_type01 tbody tr td {
  height: 30px;
}

#contentDetail img {
  width: 80% !important;
}
```

</details>

# 인스타그램 예제

## 1. 기본구성 만들기

1. App과 Card컴포넌트를 작성하세요. Card 컴포넌트의 텍스트는 data에서 가져와서 작성하세요.(01.js)
2. 반복문을 이용하여 Card가 3개 나오도록 만들어보세요.(02.js)
3. Card의 좋아요를 클릭하면 좋아요 개수가 1개 증가하며 하트의 색이 바뀌게 하고, 좋아요가 이미 1일때 다시 클릭하면 0개가 되며 하트가 원래대로 되돌아오도록 만드세요.(03.js)
4. 하트의 개수에 따라 메뉴의 알림에 뱃지가 뜨며 숫자가 적혀지게 만드세요. (04.js)

## 2. route로 상세페이지 만들기

5. Detail.js 파일을 만들고, 라우트를 세팅하여 각 Card를 클릭시에 상세페이지가 팝업형태로 뜨게 해보세요. (05.js / 01.js)
   - 단, 팝업창이 열릴때 스크롤이 되지 않도록 해보세요.
   - swiper 라이브러리를 불러와서 이미지가 슬라이드 되게 해보세요.
   - 팝업창이 열렸을때 배경요소를 클릭하면, 팝업창이 닫히게 해보세요.

```bash
import { BrowserRouter } from "react-router-dom";
<BrowserRouter>
<App />
</BrowserRouter>
```

## 4. URL파라미터

6. url파라미터를 이용하여 각 페이지에 맞춰서 내용이 나오게 해주세요. (06.js / 02.js)
   <Link> 바꼈는지 확인

## 5. 리코일로 상태관리

7. 리코일로 Card와 Detail의 좋아요 정보를 연동해보세요.

8. 로딩바를 만들고 Detail페이지가 열릴때 1초동안 로딩바가 작동하며, 로딩바가 지나간 후에 Detail페이지가 열리게 해보세요.
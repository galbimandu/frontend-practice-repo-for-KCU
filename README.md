## FrontEnd Coding Test Template
안녕하세요,  frontend 연습용 template 입니다.🙏

해당 repository를 "클론" 하셔서 아래 명시된 항목들만 완성해 주시면 됩니다.  
과제에만 집중하실 수 있게 기본적인 세팅은 미리 되어있습니다.

### 📣 &nbsp; Instructions

테이블을 만들 때 사용할 맥주 리스트🍻 API 입니다 ➡️ &nbsp; https://api.punkapi.com/v2/beers

#### ✨ &nbsp; Styling

* Styled-Components 를 사용해 주세요
* Ant Design (https://ant.design/components/overview/) 의 기본 컴포넌트들을 사용하셔도 좋습니다 (선택)

#### ⚓ &nbsp; 아래 기능들을 구현해보세요 (필수)

* 유저가 처음 페이지를 열었을 때 ``/home`` 에 도착하도록 만들어 주세요
  - 개인적으로 추가하고 싶은 디자인은 자유롭게 추가하셔도 됩니다 😊
  - 홈페이지에서 ``/beerlist`` 로 링크 이동할 수 있어야 합니다

* material table library(https://material-table.com/#/docs/get-started) 를 사용해서 맥주 리스트 페이지(/beerlist)를 만들어 주세요
  - material UI의 컴포넌트를 사용하는것이 아닙니다. 위에 있는 링크의 라이브러리를 사용해주세요.

* 테이블의 column header 는 드래그로 순서 변경이 가능해야 합니다. 바뀐 column header 순서는 redux 에 저장되어 ``/home`` 와 ``/beerlist`` 사이 이동시에 유지되어야 합니다
  - 위 라이브러리에서 드래그 기능을 지원합니다.

* 맥주 리스트의 알콜 도수 ``(abv)`` 필터 기능을 만들어 주세요 [ 예) "5-6", "6-7" ]
  - 필터는 다중 선택이 가능해야 합니다
  - 필터 기능은 material table library 에 포함되어 있는 기능을 ``사용하지 말고`` 따로 제작해야 합니다

#### 💡 &nbsp; 추가 기능들

* 맥주 이름을 클릭했을 때 해당 맥주의 상세 정보를 볼 수 있는 modal 을 제작해 주세요

* 장바구니를 만들어 주세요 
  - 맥주를 장바구니에 추가하거나 삭제가 가능해야 합니다
  - 장바구니는 ``/home`` 또는 ``/beerlist`` 에서 접근 가능해야 합니다
 
 
* 추가적으로 넣고 싶은 기능이 있는 경우 자유롭게 추가해 주세요 


#### 🎈🤖&nbsp; 진행 중 추가적인 문의 사항이 있으실 경우, 언제든지 편하게 연락 주시기 바랍니다. &nbsp; 💌🎉
<br /><br />

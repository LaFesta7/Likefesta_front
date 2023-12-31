# Likefesta_front

lafesta front end

![logo](https://github.com/LaFesta7/Likefesta_front/assets/132440453/a8d27456-ff93-4817-b671-cfd742ce9609)


## 기술적 의사 결정

### React와 Vue의 공통점
* 가상 DOM을 활용한다.
* 반응적이고 조합 가능한 컴포넌트를 제공한다.
* 코어 라이브러리에만 집중하고 있고 라우팅 및 전역 상태를 관리하는 컴패니언 라이브러리가 있다.

### React와 Vue의 차이점
* React는 단방향 데이터 바인딩이고 Vue는 양방향 데이터 바인딩 방식을 이용한다.
* 리액트는 JSX(JavaScript XML) 형태로 코드를 작성하는데 자바스크립트만을 사용해 UI 로직과 DOM을 구현한다.
* Vue의 가상 DOM구현이 React보다 빠르며 오버 헤드가 적게 발생한다.
* React에서 모든 컴포넌트는 JSX를 사용해 JSX의 툴을 이용해 Vue의 템플릿보다 진보된 기능을 사용할 수 있다.
* Vue는 템플릿을 사용해 쉽고 빠르게 제작이 가능하며 진입장벽이 낮다.

### 정리
* React는 확장성이 좋으나 자바스크립트 문법에 능숙해야하며 커스터마이징 및 자유도가 높은편이다. 또한 커뮤니티 형성이 잘 되어있고 큰 프로젝트에 용이하다.
* Vue는 제공되는 html 기반의 템플릿이 있어 진입장벽이 낮고 프로젝트를 빠르게 만들 수 있다. 개발자간 코드가 통일성이 있으며 소규모 프로젝트에 용이하다.
* 사용 용도와 역량에 맞게 React나 Vue를 선택해서 사용하면 된다.

## 최종 의사 결정
### Vue
#### 선택사유
* HTML, CSS, JS만 알고 있어도 사용이 가능하며, 진입 장벽이 낮다.
* 코드의 통일성이 있어 소규모 프로젝트에 용이하다.
* 양방향 데이터 바인딩 방식으로 화면 표시 값과 데이터 값이 동기화되어 자동 변경된다. -> 유지보수와 재사용성이 높다.
* DOM 구현이 더 빠르고 오버 헤드가 적게 발생한다.

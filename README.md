# use-github-category-test

깃 허브의 각 기능들의 사용법을 연습하기 위한 용도

## Issues
각 템플릿을 만듬

- settings 항목에서 생성 가능
  - 조금 내려가면 `Features` 항목의 `Issue` 설정이 있음
  - `Set up templetes`  ->  `Add template: select`  ->  `Feature request` ->  `Preview and edit`  ->  연필 아이콘(수정)을 클릭해 내용 작성
  - 내용 작성 완료 후, `Propose changes` ->  `Commit changes` 클릭하면 완료
  - 정상적으로 완료 되었다면 **Updated issue templates for this repository** 라는 메세지가 상단바에 나타
- 생성한 이슈 템플릿을 확인하시려면 Issue 탭을 누른 후, New Issue 버튼을 누르시면 확인이 가능

## Project
칸반 보드를 활용하여 프로젝트 생성하는 과정

- 상단의 메뉴 중에 `Projects` 탭  ->  `Create a Project`
  - 프로젝트 이름과 설명 등을 적고, `Template` 에서 `Basic Kanban` 을 선택 후 `Create project`

- 성공적으로 프로젝트 생성을 하게 되면 **Project created from Basic kanban template** 라는 메세지가 상단바에 나타난다
프로젝트에 맞게 추가 column 을 형성하거나, column 에 이슈 태스크 카드를 드래그앤드롭하며 활용하면 된다

- 프로젝트 칸반보드 각 columns 설명
  - Todo: 앞으로 해야할 일
  - In Progress: 현재 작업중인 일
  - Done: 끝난 일

## Milestone
Milestone 은 이정표 역할을 하며, 태스크 카드(Issue)들을 그룹화하는데 사용

> Milestone에 연결된 태스크 카드(Issue)가 종료되면 Milestone마다 진행 상황이 업데이트되는 것을 볼 수 있습니다. 
> 이 Milestone 기능을 통해 연관된 이슈의 추적과 진행 상황을 한눈에 파악할 수 있는 장점이 있습니다. 
> Sprint 나 단계별 구현과 관련한 유사 이슈들을 하나하나 추적하며 살펴보기보다 Milestone을 이용해 간편히 관리합시다.

- `Issue` 탭 ->  `Labels` 버튼 오른쪽에 있는 `Milestones` 클릭
- `Create a Milestone` 또는 `New milestone` 하여 이정표를 작성
- `Title` 에는 원하는 이정표 이름 쓰거나 혹은 진행 중인 sprint의 이름을 쓰는 것을 추천
- `Due date`는 Milestone의 마지막 날을 의미(말 그대로 마감일)
- `Description`에 자유롭게 작성 후에 `Create milestone` 을 누르면 생성 완료

> 계획에 알맞은 갯수만큼 Milestone을 만들어서 프로젝트를 진행하는 것을 추천!

## 태스크 카드 활용
- Issue 카테고리에서 원하는 탬플릿(태스크 카드)로 작성 후에 이를 해당 프로젝트에서 드래그 앤 드랍하면 프로젝트에 적재 가능

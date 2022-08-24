# Glossary Wiki

## 개발 키워드
*	Language: `Java` `JavaScript` `MySql`
*	Design: `MSA` `REST API`
*	Framework / Library: `Spring Boot` `Spring Data JPA` `Spring Cloud Gateway` `JWT`
* CI/CD: `Github Action`

<br/>

## 개요
*	여러 유저가 내용 작성과 수정을 할 수 있는 Wiki 입니다. 개별 문서 페이지가 존재하는 일반적인 시중 Wiki 보다 가볍게 한 페이지로 사용 가능하도록 구성 하였습니다.
*	최초 개발 시 모든 서비스를 의도적으로 한 프로젝트로 구성한 뒤, 추후 각 서비스 별 MSA 형태로 분리하는 단계를 진행하였습니다.
*	분리된 모든 서비스에 대해 Github부터 AWS EC2 서버까지 자동으로 배포되는 CI/CD 라인도 구성하였습니다.


<br/>

## 미리보기

_[메인 페이지]_

<img width="871" alt="image" src="https://user-images.githubusercontent.com/86358502/167252789-3c5eafc8-4e66-4beb-849e-227066931aa8.png">

<br/>

_[작성 에디터]_

<img width="725" alt="image" src="https://user-images.githubusercontent.com/86358502/167253286-de0e779d-2a03-462a-ad1f-de202e8c456a.png">


<br/>

## 개발 동기
배우는 과정에 모르는 용어가 나오면 _'나중에 알아봐야지'_ 하고 잊혀지는 문제가 많다는 생각에 **출발**하였습니다,

블로그에 따로 포스팅 할 만큼 깊은 내용이 아닌, 간단한 용어 설명 수준의 정리를 위한 단어장을 만들고 싶었습니다.

<br/>

찾아가기 힘든 개별 문서가 아닌, 한 페이지로 구성하여 **[우선 등록, 이 후 입력]** 을 생각 했습니다.

모르는 용어가 나왔을때 현재의 배움에 방해가 되지 않도록 **'우선 등록'** 해놓고 **'나중에'** 채워넣을 수 있는 공간이며, 함께 공부하는 동료들과 같이 채워 나가는 공간을 원했습니다.

<br/>

## 개발 기록 (Link 클릭)
*	[위키 단어장 만들기 - 1.시작](https://deokhunkim.github.io/my%20project%20note/2022/04/30/%EC%9C%84%ED%82%A4-%EB%8B%A8%EC%96%B4%EC%9E%A5-%EB%A7%8C%EB%93%A4%EA%B8%B0-1.%EC%8B%9C%EC%9E%91.html)
*	[위키 단어장 만들기 - 2.API 설계](https://deokhunkim.github.io/my%20project%20note/2022/05/01/%EC%9C%84%ED%82%A4-%EB%8B%A8%EC%96%B4%EC%9E%A5-%EB%A7%8C%EB%93%A4%EA%B8%B0-2.API-%EC%84%A4%EA%B3%84.html)
*	[위키 단어장 만들기 - 3.API 구현](https://deokhunkim.github.io/my%20project%20note/2022/05/02/%EC%9C%84%ED%82%A4-%EB%8B%A8%EC%96%B4%EC%9E%A5-%EB%A7%8C%EB%93%A4%EA%B8%B0-3.API-%EA%B5%AC%ED%98%84.html)
*	[위키 단어장 만들기 - 4.클라이언트 구현](https://deokhunkim.github.io/my%20project%20note/2022/05/02/%EC%9C%84%ED%82%A4-%EB%8B%A8%EC%96%B4%EC%9E%A5-%EB%A7%8C%EB%93%A4%EA%B8%B0-4.%ED%81%B4%EB%9D%BC%EC%9D%B4%EC%96%B8%ED%8A%B8-%EA%B5%AC%ED%98%84.html)
*	[위키 단어장 만들기 - 5.서비스 분리(MSA) - 계획](https://deokhunkim.github.io/my%20project%20note/2022/05/03/%EC%9C%84%ED%82%A4-%EB%8B%A8%EC%96%B4%EC%9E%A5-%EB%A7%8C%EB%93%A4%EA%B8%B0-5.%EC%84%9C%EB%B9%84%EC%8A%A4-%EB%B6%84%EB%A6%AC(MSA)-%EA%B2%8C%ED%9A%8D.html)
*	[위키 단어장 만들기 - 6.서비스 분리(MSA) - 단어장 API 의 분리와 API Gateway 도입](https://deokhunkim.github.io/my%20project%20note/2022/05/04/%EC%9C%84%ED%82%A4-%EB%8B%A8%EC%96%B4%EC%9E%A5-%EB%A7%8C%EB%93%A4%EA%B8%B0-6.%EC%84%9C%EB%B9%84%EC%8A%A4-%EB%B6%84%EB%A6%AC(MSA)-%EB%8B%A8%EC%96%B4%EC%9E%A5-API-%EB%B6%84%EB%A6%AC%EC%99%80-API-Gateway-%EB%8F%84%EC%9E%85.html)
*	[위키 단어장 만들기 -7.서비스 분리(MSA) - JWT 인증 도입](https://deokhunkim.github.io/my%20project%20note/2022/05/06/%EC%9C%84%ED%82%A4-%EB%8B%A8%EC%96%B4%EC%9E%A5-%EB%A7%8C%EB%93%A4%EA%B8%B0-7.%EC%84%9C%EB%B9%84%EC%8A%A4-%EB%B6%84%EB%A6%AC(MSA)-JWT-%EC%9D%B8%EC%A6%9D-%EB%8F%84%EC%9E%85.html)
*	[GitHub - GlossaryAPI](https://github.com/DeokhunKim/GlossaryAPI)
*	[GitHub - API Gateway](https://github.com/DeokhunKim/KPP-Gateway)
*	[GitHub - JWT-Authorization](https://github.com/DeokhunKim/JWT-Authorization)


<br/>

## 이용 방법
### 신규 페이지 작성
(1) 좌측 Bar 의 **[+NEW]** 버튼을 누르거나

(2) 페이지 내용에 등로하고 싶은 단어나 문장을 스크롤 한 뒤 **[+Create Page]** 버튼을 누릅니다

### 에디터
에디터는 오픈소스 Toast UI 에디터를 채택하였습니다.

에디터 하단의 탭을 통해서 일반 `에디터 모드`와 `Markdown 편집기 모드` 중에 선택 가능 합니다.








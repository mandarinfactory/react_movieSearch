# react_movieSearch(무비써치)

## 🖥️ 프로젝트 소개
reactJS를 기반으로 영화진흥위원회(kofic), 한국영상자료원(kmdb), tmdb를 이용해서 만든 영화정보 및 검색 사이트입니다.

## 🧭 웹사이트
https://react-moviesearch-30490.web.app/

## 🕰️ 개발 기간
- 23.03월 - 23.05월

## ⚙️ 개발환경
- 바닐라JS
- React JS
- tailwind CSS
- firebase(베포)

## ⚙️ 사용API
- 영화진흥위원회API(https://www.kobis.or.kr/kobisopenapi/homepg/apiservice/searchServiceInfo.do)
- 한국영상자료원API(https://www.kmdb.or.kr/info/api/guide?menuIndex=115)
- tmdbAPI(https://developer.themoviedb.org/docs)
- firebase인증API(https://firebase.google.com/docs/auth?hl=ko)

## 📌주요 기능
### 박스오피스 / 상영예정작 - <a href="https://github.com/mandarinfactory/react_movieSearch/wiki/%EC%A3%BC%EC%9A%94%EA%B8%B0%EB%8A%A5(%EB%B0%95%EC%8A%A4%EC%98%A4%ED%94%BC%EC%8A%A4,--%EC%83%81%EC%98%81%EC%98%88%EC%A0%95%EC%9E%91)">위키</a>
- 박스오피스는 영화진흥위원회API를 이용해서 데이터를 가져와 구현했습니다.
- 상영예정작은 tmdbAPI를 이용해서 데이터를 가져와 구현했습니다.
- 해당 영화를 클릭하면 영화정보 박스가 나오게 구현했습니다.
- 해당 API에서 데이터가 없다면 데이터가 없어서 정보를 불러올 수 없다는 modal을 설정해놨습니다.

### 영화 검색칸 - <a href="https://github.com/mandarinfactory/react_movieSearch/wiki/%EC%A3%BC%EC%9A%94%EA%B8%B0%EB%8A%A5(%EC%98%81%ED%99%94%EA%B2%80%EC%83%89)">위키</a>
- 영화검색을 하면 아래 검색결과가 나오게 구현했습니다.
- 검색결과에 나온 영화를 클릭하면 마찬가지로 영화정보 박스가 나오게 구현했습니다.

### 영화 큐레이션 칸
- 하드코딩으로 장르별로 무작위로 나오게끔 구현했습니다.(장르만 하드코딩으로 넣어놓음)
- 무작위로 나온 장르 및 해당 영화들이 간단하게 나오게끔 구현했습니다.

### 로그인 칸
- firebase인증API룰 이용해서 간단한 회원가입 / 로그인 modal를 구현했습니다. 

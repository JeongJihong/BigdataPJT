# [LEAD ME]

## 서론

> 주제 선정 및 방향성 이야기

### 주제

- 추천 알고리즘를 활용한 영화 추천 플랫폼 
- 데이터 시각화를 이용해 사용자의 취향 분석 기능
- MBTI를 이용한 영화 추천 기능



### 도입 이유

기존의 영화 추천서비스는 영화, 배우에만 초점을 두고 추천을 해주기 때문에 단조로운 느낌을 받았는데 저희 영화 추천서비스는 MBTI를 이용해 유저간의 그룹을 만들고 이에 따라 다른 추천을 해주고 데이터 시각화로 자신의 취향을 바로 확인 할 수 있기 때문에 사용자들에게 흥미를 줄 수 있습니다.

![image-20211008134831456](README.assets/image-20211008134831456.png)
![image-20211008134846771](README.assets/image-20211008134846771.png)
![image-20211008135335827](README.assets/image-20211008135335827.png)
![image-20211008135422042](README.assets/image-20211008135422042.png)

## SUB 1 (08.30-09.03)

> 빅데이터 학습과 기본 알고리즘 공부 기간

## SUB 2 (09.06-09.17)

> 프로젝트 주제 선정과 기획, 기본적인 틀 구성



### :computer: 백엔드 진행사항

- 기능명세서 기술(notion)
- Entity 구현 및 Diagram 생성
- Django와 MySql를 이용하여 연동
- Restful API 구현
- 회원관리(로그인-jwt토큰인증방식, 회원가입, 중복검사) 기능 구현





#### :boxing_glove: 프론트엔드 진행사항

- 데이터 시각화 학습
- React 학습
- Material-UI 학습
- Main 페이지 구현
- Movie 상세 페이지 구현

- Figma로 와이어프레임 작성



## SUB 3 (09.18~10.08)

### :computer: 백엔드 진행사항

- 콘텐츠 기반 필터링 구현
- 사용자 기반 협업 필터링 + 콘텐츠 기반 필터링 구현
- 데이터 시각화를 위한 분석 구현
- MovieTI 기능 구현

- 검색 기능 구현



###  :boxing_glove: 프론트엔드 진행사항

- 데이터 시각화를 통한 취향 분석 페이지 구현 (recharts)
- ant-Icon을 이용한 디자인 개선
- 검색 기능 있는 nav-bar 구현 
- MovieTI 설문, 결과 페이지 구현
- 로딩 스피너 구현
- 메인페이지에서 백드롭을 이용한 캐러셀 구현



### 배포

- Ubuntu(Linux) AWS 제공 서버 내에 배포 진행

- 서버내 git clone후 통합빌드하여 배포 진행

  - 보안해야할 점 :도커 및 젠킨스를 활용한 CI/CD 배포환경으로의 발전이 필요

  

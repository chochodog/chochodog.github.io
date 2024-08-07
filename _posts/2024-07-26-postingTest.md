---
author: chanukPark
title: TestVideo
tags: [demo video, cafe, kotlin, android, node.js, react, html]
layout: post-material-sidebar-left
---
##### 카페 자리를 예약하고 예약된 자리를 관리하기 위한 시스템을 구축하기 위한 프로젝트입니다.

<iframe width="788" height="394" src="https://www.youtube.com/embed/RtJcPfuj_Wg" title="3일만 내가 하자는 대로 해줄래?" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<br><br>
#### 기능적 요구사항
* 카페 사용자는 자리를 선점하기 위해 카페 자리 예약을 한다.
* 카페 사용자는 예약한 자리를 변경 혹은 취소하기 위해 예약 취소한다.
* 카페 사장은 가게의 자리를 반영하기 위해서 자리를 설정한다.
* 카페 사장은 예약 정보를 관리하기 위해 예약 현황을 확인한다.
* 카페 사용자는 카페를 찾기 위해 원하는 카페를 검색한다.
* 카페 사용자는 카페 빈자리를 확인하기 위해 카페를 선택하여 빈자리를 확인한다.
* 카페 사장은 카페 정보를 반영하기 위해 카페 정보를 입력한다.
* 카페 사장은 카페 자리를 설정하기 위해 darg and drop으로 자리를 설정한다.



<br>
#### 품질적 요구사항
* 카페 사용자는 카페 목록을 확인하기 위해 카페 리스트 화면에서 스크롤 한다. 이때 카페 리스트 화면 출력은 0.2초 이내로 이루어져야 한다.
* 카페 사장은 예약 화면에서 예약 현황 데이터를 얻기 위해 2초에 평균 20개의 데이터를 요청한다. 이때 화면은 1초 이내로 출력이 되어야 한다.
* 인증되지  않은 사용자는 카페 설정 화면으로 접속하기 위해 url을 통한 접속을 시도한다. 이때 인증되지 않은 접근을 막고 인증된 사용자에게 0.5초 이내로 서비스를 제공해야 한다.


<br>
#### 제약사항
* 언어: Kotlin, nodeJS, JavaScript(React)
* 개발 인원: 4인
* 개발 기간: 1학기(약 3개월)


<br>
#### UseCase Diagram
![UseCase Diagram](/img/bookcafe_ucd.png "bookcafe UseCase Diagram")

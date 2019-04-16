# Programs For DSM Student

## DSMIP.exe
> 학교전용 아이피 설정과 집 전용 아이피 설정이 쉽게 가능합니다
  * 학년 반 번호 입력으로 간단하게 아이피 설정이 가능
  * 한번에 아이피 해제 가능

# 커스텀 트리거

## 커스텀 트리거란
> 마인크래프트 게임안에서 일어나는 모든 사건들을 이벤트라 부르는데,
>
> 이 이벤트들이 발생하였을때를 인식하고 구문을 실핼하는것이 커스텀 트리거입니다.

## 사용법
> 기본적으로 /trg custom 이벤트명 트리거이름 으로 생성하실수 있습니다.
>
> ex:) /trg custom onJoin 입장
>
>     위의처럼 하였을때 커스텀 트리거 폴더에 입장.trg와 입장.yml이 생성됩니다.
>
>     .trg 파일에는 구문이, .yml 파일에는 이벤트 이름과 동기모드 유뮤를 설정할수 있습니다.

## 예제
> /trg custom onJoin join
>
> join.trg
> ```
> #MESSAGE "황영합니다 "+$playername+"님"
> ```
>
> join.yml
> ```
> Sync: true
> Event: onJoin
> ```

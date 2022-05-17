![tabling-face-og](https://user-images.githubusercontent.com/55871108/168711756-3dd4153f-9e2e-4400-82ac-9878017c5a2b.png)
# 테이블링(Tabling)
본 예제는 MSA교육과정에서 배웠던 EventStorming 등의 내용을 포함한 실습 프로젝트입니다.

# Table of contents
- [서비스 시나리오](#서비스-시나리오)
- [체크포인트](#체크포인트)
- [분석/설계](#분석설계)
- [구현:](#구현-)
- [운영](#운영)
  - [CI/CD 설정](#cicd설정)


# 서비스 시나리오

1. 고객이 앱에서 가게를 검색한다.
2. 해당 가게의 이용가능한 좌석 수를 확인하고 줄서기를 누른다.
3. 줄서기를 누르면 가게에 이용 희망 내역이 전송된다.
4. 고객의 입장인원 수에 따라 대기 번호 부여 여부를 판단 후 그에 따라 카카오톡 메시지를 전달한다.


# 체크포인트
- [X] 이벤트 스토밍
- [ ] 운영
  - [ ] Gateway
  - [ ] Auto Scaling
  - [ ] Self-healing
  - [ ] Polyglot

# 분석설계
### 이벤트 스토밍
<img width="1582" alt="Screen Shot 2022-05-17 at 11 07 09 AM" src="https://user-images.githubusercontent.com/55871108/168713780-c3f5bab3-64f7-4e8e-b961-910da5f69433.png">
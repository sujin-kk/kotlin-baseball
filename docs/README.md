## 기능 목록 🚀

### Summary
`숫자 야구` -> 1부터 9까지 서로 다른 수로 이루어진 3자리의 수를 맞추는 게임이다.

같은 수가 같은 자리에 있으면 스트라이크, 다른 자리에 있으면 볼, 같은 수가 전혀 없으면 낫싱이란 힌트를 얻고, 그 힌트를 이용해서 먼저 상대방(컴퓨터)의 수를 맞추면 승리한다.
```
예) 상대방(컴퓨터)의 수가 425일 때
123을 제시한 경우 : 1스트라이크
456을 제시한 경우 : 1볼 1스트라이크
789를 제시한 경우 : 낫싱
```

---

### 게임 시작
- [ ] 게임 시작 문구를 출력한다.

### 게임 진행 - 입력
- [ ] 상대방의 역할을 컴퓨터가 하고, 컴퓨터는 1에서 9까지 서로 다른 임의의 수 3개를 선택한다. (플레이어는 이 숫자를 알 수 없다.)
- [ ] 플레이어 입력 차례가 되면 `숫자를 입력해주세요` 문구를 출력한다.
- [ ] 플레이어는 서로 다른 3자리 수만 입력할 수 있다.

### 게임 진행 - 출력
- [ ] 입력 수에 대한 결과를 볼, 스트라이크 개수로 출력한다.
- [ ] 같은 수가 같은 자리에 있으면 스트라이크 개수를 출력한다.
- [ ] 같은 수가 다른 자리에 있으면 볼 개수로 출력한다.
- [ ] 같은 수가 전혀 없으면 낫싱을 출력한다.
- [ ] 3개의 숫자를 모두 맞히면, 결과와 게임 종료를 알린다.

### 게임 종료
- [ ] 게임이 끝난 후 게임을 다시 시작하거나 완전히 종료할 수 있다.
- [ ] 게임이 끝난 경우 `재시작`/`종료` 구분을 `1`과 `2`중 하나의 수로 입력 받아 구분한다.
- [ ] 사용자가 3개의 서로 다른 숫자가 아닌 잘못된 값을 입력할 경우, `IllegalArgumentException` 를 발생시키고 게임을 종료시킨다.
- [ ] 사용자가 숫자를 모두 맞힌 뒤 1 또는 2 이외의 잘못된 값을 입력할 경우, `IllegalArgumentException` 를 발생시키고 게임을 종료시킨다.

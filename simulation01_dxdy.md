# 01. 시뮬레이션, 구현

    : 문제에서 제시한 상황을 알고리즘으로 수행해내도록  문제
 <br>

### 01-1 dx, dy 테크닉

    - 특정 방향에 대해 이동하는 경우에 대해서는 dx, dy 테크닉을 사용합니다.
    - 아래 사진은 상, 하, 좌, 우 4방향 일 경우 예시

<img src="https://contents.codetree.ai/problems/840/images/213f1612-9722-4a92-b52d-8fde58d8acb7.png" />

<br>

<img src="https://contents.codetree.ai/problems/840/images/c1a1b5b6-83cc-4ef2-b6cc-8eccfbc52b60.png" />

```c++
// 현재 좌표를 기준으로 가고자 하는 방향으로 dir_num의 값을 주어 좌표 이동
int dir_num = 2; 
int x = 1, y = 5;
int dx[4] = {1, 0, -1, 0}, dy[4] = {0, -1, 0, 1};
int nx, ny;

nx = x + dx[dir_num], ny = y + dy[dir_num];

```

<br>





# jungharin.github.io

# top, ps, jobs, kill 명령어 조사

## top
`top` 명령어는 실시간으로 CPU 사용률을 체크해주는 기능.
### 사용법
```sh
top
top -d [초] : 화면 갱신 주기 설정
top -u [사용자] : 특정 사용자의 프로세스만 표시
top -p [PID] : 특정 PID를 모니터
```
## ps
`ps` 명령어는 현재 실행중인 프로세스 목록과 상태를 출력하여 보여주는 기능.
### 사용법
```sh
ps
ps -e : 모든 프로세스 표시
ps -f : 풀 포맷으로 출력
ps -u [사용자] : 특정 사용자의 프로세스만 표시
ps -p [PID] : 특정 PID의 프로세스만 표시
```
## jobs
`job` 명령어는 작업의 상태를 표시해주는 기능.
### 사용법
```sh
jobs
jobs -l : 프로세스 ID 포함하여 출력
jobs -p : 각 작업의 프로세스 ID만 출력
```
## kill
`kill` 명령어는 특정 프로세스를 종료 시키는 기능.
### 사용법
```sh
kill
kill -9 [PID] : 강제 종료
kill -15 [PID] : 정상 종료
```
# 명령어 요약

| 명령어  | 설명                                                | 사용법           |
| ------- | --------------------------------------------------- | ----------------- |
| top     | 실시간으로 CPU 사용률을 체크                         | `top [옵션]`      |
| ps      | 현재 실행중인 프로세스 목록과 상태를 출력하여 보여줌  | `ps [옵션]`       |
| jobs    | 작업의 상태를 표시                                   | `jobs [옵션]`     |
| kill    | 특정 프로세스를 종료                                 | `kill [옵션] PID` |

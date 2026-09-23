# B4-2 컴퓨터가 갑자기 느려지거나 멈췄을 때 원인 찾아 고치기

코딧세이 AI 올인원 본과정 B4-2 미션 저장소입니다.

## 범위
OOM·CPU 과점유·Deadlock 3종 진단·ps/top 증거 추론·GitHub Issue 리포트 3건

## 개발 환경
제공된 프로그램을 실행할 수 있는 리눅스 실습 환경을 사용합니다. 배포판과 제공 파일 준비 상태는 착수 시 기록합니다.

### 새 환경에서 준비

Git을 설치한 뒤 새 기기에서 저장소를 받습니다.

```bash
git clone https://github.com/sarguments/b4-2-troubleshooting.git
cd b4-2-troubleshooting
```

실습에 사용할 리눅스 환경에 접속한 뒤, 그 안에서 확인합니다. macOS 호스트에서 실행한 결과는 리눅스 환경 확인으로 보지 않습니다.

```bash
uname -s
cat /etc/os-release
bash --version
```

`uname -s`가 `Linux`인지 확인하고, 제공된 실행 파일을 받은 뒤 안내에 따라 재현합니다. 현재 저장소에는 제공 파일이 없습니다.

## 준비 상태
Docker와 Colima 설치를 확인했습니다. 리눅스 실습 환경은 아직 실행하지 않았습니다. 장애 재현·진단·조치와 Issue 리포트는 실제 관찰 결과를 바탕으로 작성합니다.

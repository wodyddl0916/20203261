# 20203261
top:
top은 시스템의 실시간 프로세스 모니터링 도구입니다.
실행 중인 프로세스의 정보를 제공하며, CPU, 메모리, 실행 시간 등의 성능과 관련된 정보를 보여줍니다.
top 명령어를 실행하면 프로세스 목록이 업데이트되며, CPU 사용량이 높은 프로세스나 메모리 사용량이 큰 프로세스 등을 확인할 수 있습니다.
상호작용적으로 사용할 수 있어서, 일정 간격으로 프로세스 목록을 업데이트하고 실시간으로 모니터링할 수 있습니다.
ps:
ps는 현재 실행 중인 프로세스의 정보를 보여주는 명령어입니다.
ps 명령어를 실행하면 프로세스 ID (PID), 부모 프로세스 ID (PPID), CPU 사용량, 메모리 사용량 등과 같은 정보를 출력합니다.
ps 명령어에는 다양한 옵션을 사용하여 원하는 형식으로 출력하거나 특정 조건에 맞는 프로세스만 필터링할 수 있습니다.
jobs:
jobs는 백그라운드(background)에서 실행 중인 작업(job) 목록을 보여주는 명령어입니다.
백그라운드에서 실행 중인 작업은 일반적으로 사용자가 실행한 프로세스 중 일부를 백그라운드에서 실행하도록 지시한 경우입니다.
jobs 명령어를 실행하면 해당 쉘 세션에서 실행 중인 백그라운드 작업의 번호와 상태를 출력합니다.
백그라운드 작업을 관리하거나 작업을 중지(stop) 또는 재개(resume)하는 등의 조작을 할 수 있습니다.
kill:
kill은 실행 중인 프로세스를 종료하는 명령어입니다.
kill 명령어를 사용하면 프로세스에 특정 시그널을 보내어 프로세스를 종료시킬 수 있습니다.
일반적으로 kill 명령어는 프로세스 ID (PID)를 이용하여 특정 프로세스를 종료하는데 사용됩니다.
특정 시그널을 지정하지 않으면 기본적으로 TERM 시그널을 보내어 프로세스를 종료시킵니다. 다른 시그널을 사용하려면 옵션을 지정해야 합니다.

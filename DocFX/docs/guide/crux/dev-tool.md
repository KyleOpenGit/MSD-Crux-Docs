# The DevTool

`MSD.Crux.DevTool`은 셸 명령어 프로그램 개발을 위한 프로젝트입니다.

CLI 명령어용 프로그램은 셸명령어를 통해서 명령어 옵션(App arguments)과 함께 실행된 뒤 작업을 마치고 곧바로 종료되는 방식으로 작동하므로 IDE에서 단지 실행해보는 것은 의미가 없습니다.
IDE에서 RUN과 함께 명령어를 실행하고 싶다면 각 IDE의 RUN Configuration 설정에서 원하는 명령어를 설정해두고 RUN 하시기 바랍니다.

- Visual Studio: `Application arguments`
- JetBranins Rider: `Run/Debug Configuration`
- Visual Studio Code: `launch.json`에서 Arguments 설정

또는 직접 배포, Shell에 등록 후 배포환경에서 명령어를 실행 하세요.


## 지원 명령어 및 옵션

루트 명령어: `crux-dev-tool`

`System.CommandLine` 기본 명령어 옵션:
  - `--help`
  - `--version`

루트 명령어 추가 옵션
- `--app-version`


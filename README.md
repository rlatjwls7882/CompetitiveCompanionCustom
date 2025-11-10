BOJ 생성되는 파일 이름 변경 (문제 제목 -> 문제 번호).cpp

## Running locally
The following commands can be used to start working on Competitive Companion locally. Additionally, make sure you got [Node.js](https://nodejs.org/en/) and [PNPM](https://pnpm.io/) installed.

```bash
# Clone the repository
git clone https://github.com/rlatjwls7882/CompetitiveCompanionCustom.git

# cd into the extension folder
cd CompetitiveCompanionCustom

# Install the dependencies
pnpm install

# 파일이 디지털 서명되지 않았습니다. 현재 시스템에서 이 스크립트를 실행할 수 없습니다. 오류 발생 시
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

# Build the Chrome code to the build-chrome/ directory
pnpm build:chrome

# Build the Firefox code to the build-firefox/ directory
pnpm build:firefox
```

## Tools that use Competitive Companion
- [acmX](https://marketplace.visualstudio.com/items?itemName=marx24.acmx)
- [AI Virtual Assistant](https://github.com/Saurav-Paul/AI-virtual-assistant-python)
- [Assistant.nvim](https://github.com/A7Lavinraj/assistant.nvim)
- [AutoCp](https://pushpavel.github.io/AutoCp/)
- [Caide](https://github.com/slycelote/caide)
- [CHelper](https://plugins.jetbrains.com/plugin/7091-chelper)
- [Competitive Programming Gradle Plugin](https://github.com/saurabh73/competitive-programming)
- [Competitive Programming Helper](https://marketplace.visualstudio.com/items?itemName=DivyanshuAgrawal.competitive-programming-helper)
- [CompetiTest.nvim](https://github.com/xeluxee/competitest.nvim)
- [CP-Assist](https://github.com/tsych0/cp-assist)
- [CP Editor](https://github.com/coder3101/cp-editor)
- [cpbooster](https://www.npmjs.com/package/cpbooster)
- [cphelper.nvim](https://github.com/p00f/cphelper.nvim)
- [Fast Olympic Coding](https://github.com/sam20908/vscode-fastolympiccoding)
- [Hightail](https://github.com/dj3500/hightail)
- [JHelper](https://plugins.jetbrains.com/plugin/7541-jhelper)
- [Mind Sport](https://plugins.jetbrains.com/plugin/10688-mind-sport)
- [Red Panda Dev-C++](https://github.com/royqh1979/RedPanda-CPP)
- [rust-competitive-helper](https://github.com/rust-competitive-helper/rust-competitive-helper)
- Any other tool that can parse the data that is being sent, read more about that [below](#custom-tools)

## Supported websites
| Website                    | Problem parser | Contest parser |
|----------------------------|----------------|----------------|
| 33OJ                       | ✔              | ✔              |
| A2 Online Judge            | ✔              | ✔              |
| ACMP                       | ✔              |                |
| AcWing                     | ✔              |                |
| Aizu Online Judge          | ✔              |                |
| Algotester                 | ✔              |                |
| AlgoZenith                 | ✔              |                |
| Anarchy Golf               | ✔              |                |
| AtCoder                    | ✔              | ✔              |
| A.Y. Jackson Online Judge  | ✔              | ✔              |
| Baekjoon Online Judge      | ✔              |                |
| BAPS OJ                    | ✔              | ✔              |
| beecrowd                   | ✔              | ✔              |
| Bloomberg CodeCon          | ✔              |                |
| BUCTOJ                     | ✔              | ✔              |
| CodeChef                   | ✔              | ✔              |
| CodeDrills                 | ✔              |                |
| Codeforces                 | ✔              | ✔              |
| CodeMarshal                | ✔              | ✔              |
| CodeRun                    | ✔              | ✔              |
| CodeUp                     | ✔              |                |
| COJ                        | ✔              | ✔              |
| Contest Hunter             | ✔              | ✔              |
| CPython.uz                 | ✔              | ✔              |
| CS Academy                 | ✔              |                |
| CSES                       | ✔              | ✔              |
| CSGOJ                      | ✔              | ✔              |
| CSU-ACM Online Judge       | ✔              | ✔              |
| CYEZOJ                     | ✔              | ✔              |
| Daimayuan Online Judge     | ✔              | ✔              |
| Dimik OJ                   | ✔              |                |
| DMOJ                       | ✔              | ✔              |
| DOMjudge                   |                | ✔              |
| DotOJ                      | ✔              | ✔              |
| Eolymp                     | ✔              | ✔              |
| ECNU Online Judge          | ✔              | ✔              |
| FZU Online Judge           | ✔              | ✔              |
| Google Coding Competitions | ✔              |                |
| HackerEarth                | ✔              | ✔              |
| HackerRank                 | ✔              | ✔              |
| HDOJ                       | ✔              | ✔              |
| HIT Online Judge           | ✔              |                |
| hihoCoder                  | ✔              | ✔              |
| HKOI Online Judge          | ✔              | ✔              |
| HOJ                        | ✔              |                |
| Hrbust Online Judge        | ✔              |                |
| Hydro                      | ✔              | ✔              |
| ICPC Live Archive          | ✔              |                |
| InfoArena                  | ✔              |                |
| ITCoder HUTECH             | ✔              |                |
| Jutge                      | ✔              |                |
| Kattis                     | ✔              | ✔              |
| KEP.uz                     | ✔              | ✔              |
| Kilonova                   | ✔              | ✔              |
| Lanqiao                    | ✔              | ✔              |
| Le Quy Don Online Judge    | ✔              | ✔              |
| Library Checker            | ✔              |                |
| LibreOJ                    | ✔              | ✔              |
| LightOJ                    | ✔              | ✔              |
| LSYOI                      | ✔              |                |
| Luogu                      | ✔              | ✔              |
| MarisaOJ                   | ✔              | ✔              |
| Mendo                      | ✔              |                |
| Meta Coding Competitions   | ✔              |                |
| MOI Arena                  | ✔              | ✔              |
| mrJudge                    | ✔              |                |
| MSK Informatics            | ✔              |                |
| NBUT Online Judge          | ✔              | ✔              |
| Neps Academy               | ✔              |                |
| NerdArena                  | ✔              |                |
| Newton School              | ✔              |                |
| NOJ                        | ✔              | ✔              |
| NowCoder                   | ✔              |                |
| NYTD Online Judge          | ✔              | ✔              |
| oiClass                    | ✔              | ✔              |
| Olinfo                     | ✔              |                |
| Olympicode                 | ✔              |                |
| omegaUp                    | ✔              |                |
| OpenJudge                  | ✔              | ✔              |
| OTOG                       | ✔              |                |
| Panda Online Judge         | ✔              |                |
| PBInfo                     | ✔              |                |
| PEG Judge                  | ✔              | ✔              |
| POJ                        | ✔              | ✔              |
| PTA                        | ✔              |                |
| Public Judge               | ✔              | ✔              |
| QBXTOJ                     | ✔              |                |
| QDUOJ                      | ✔              | ✔              |
| QQWhale                    | ✔              |                |
| RoboContest                | ✔              | ✔              |
| SDUT OnlineJudge           | ✔              |                |
| SeriousOJ                  | ✔              | ✔              |
| Sort Me                    | ✔              |                |
| SPOJ                       | ✔              |                |
| SSOIER                     | ✔              |                |
| StarryCoding               | ✔              |                |
| TheJobOverflow             | ✔              |                |
| Timus Online Judge         | ✔              | ✔              |
| TLX                        | ✔              | ✔              |
| Toph                       | ✔              |                |
| uDebug                     | ✔              |                |
| Universal Cup              | ✔              | ✔              |
| UOJ                        | ✔              | ✔              |
| USACO                      | ✔              |                |
| USACO Training             | ✔              |                |
| UVa Online Judge           | ✔              |                |
| Virtual Judge              | ✔              | ✔              |
| VNOI Online Judge          | ✔              | ✔              |
| YACS                       | ✔              |                |
| Yandex                     | ✔              | ✔              |
| XXM                        | ✔              |                |
| X-Camp                     | ✔              |                |
| yukicoder                  | ✔              | ✔              |
| Yun Dou Xue Yuan           | ✔              | ✔              |
| ZOJ                        | ✔              |                |
| ZUFEOJ                     | ✔              | ✔              |

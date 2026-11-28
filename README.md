# 박성범 | 엔지니어 포트폴리오

**프로젝트: 반도체 디자인 자동화**

> 안녕하세요 성장하는 엔지니어 박성범입니다!  
> 반도체 설계를 목표로 C언어와 리눅스 기반 개발 환경을 익히고 있습니다.

**학교:** 가천대학교 반도체설계학과(계약학과) 1학년

**회사:** 아날로그에이아이

---

## About Me

- **현재:** 1학년 재학 중이며, 3학년부터 근무와 학업을 병행합니다
- **목표:** 3학년 현업 투입 전까지 C언어, 회로, 디지털 설계 기초를 갖춥니다
- **학습 중:**
  - 반도체 회로설계
  - 반도체산업기술
  - 반도체물리
  - C언어심화
  - 디지털설계
  - 기초공학설계

---

## Tech Stack
![C](https://img.shields.io/badge/C-00599C?style=flat) ![Git](https://img.shields.io/badge/Git-F05032?style=flat) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat)

---

## Course: C언어 심화

| 영역 | 개념 | 내용 |
|---|---|---|
| Linux | `pwd`, `cd` | 현재 경로를 확인(pwd)하고 이동(cd)하며, 절대 경로는 최상위(/)부터, 상대 경로는 현재 위치부터 표기합니다. |
| Linux | `ls -al` | 숨김 파일을 포함해 권한, 용량, 날짜를 자세히 출력합니다. |
| Linux | `mkdir -p`, `cp -r`, `rm -r` | mkdir -p는 없는 상위 경로 영역까지 한 번에 생성하고, cp -r·rm -r은 디렉터리 내부의 하위 영역까지 한 번에 복사·삭제합니다. |
| Linux | 하드 링크, 심볼릭 링크 | 원본을 삭제해도 하드 링크는 데이터(inode)가 유지되고, 심볼릭 링크는 대상 경로가 사라져 끊어집니다. |
| Linux | 파이프(`\|`), 리디렉션(`>`, `>>`) | 파이프(\|)는 앞 명령의 출력을 뒷 명령의 입력으로 넘기고, 리디렉션은 출력을 파일로 덮어쓰기(>), 덧붙이기(>>)합니다.|
| Linux | `chmod 755` | 읽기(4), 쓰기(2), 실행(1)을 더해 숫자로 권한을 설정합니다. 내 권한은 7(읽기+쓰기+실행), 그룹과 그 외 사용자는 5(읽기+실행)로 둡니다. |
| Shell | `alias`, `.cshrc` | 단축 명령(alias)을 등록하며, .cshrc(C 셸 계열) 등 셸 설정 파일에 적어 새 셸/로그인 환경에서 자동 적용합니다. |
| Git | `add` → `commit` → `push` | 변경 사항을 스테이징(add)해 로컬 저장소에 기록(commit)한 뒤, 원격 저장소(GitHub 등)에 반영(push)합니다. |
| Git | `pull` | 출근 후 팀의 변경분을 먼저 받아 내 작업 폴더와 동기화합니다. |

---

## Practice & Projects

### 반도체 디자인 자동화를 위한 기반 환경 구축

반복 작업을 줄이고 작업 이력을 남기는 것이 설계 자동화의 출발점.
이를 위해 수업에서 다음 기반 기술을 실습.

- **자동 실행 설정:** `.cshrc`에 명령을 등록해 로그인 시 자동으로 실행되게 했습니다.
- **단축 명령:** `alias`로 긴 명령을 짧게 줄였습니다.
- **버전 관리:** Git으로 파일 변경 이력을 관리했습니다.

```csh
alias cl 'clear'
alias l 'ls -al'
alias p 'pwd'
```

---

## Dev Environment & Workflow

### 구성

| 구분 | 내용 |
|---|---|
| 로컬 | Windows 노트북, Git Bash, VS Code |
| 원격 | GitHub 저장소 `gachon0304` |
| 인증 | SSH 키(RSA 4096) 방식, 공개키를 GitHub에 등록 |

### 작업 흐름

1. VS Code에서 `README.md`를 수정하고 저장합니다.
2. `git status`로 변경 상태를 확인합니다.
3. 아래 명령으로 GitHub에 반영합니다.

```bash
git add README.md
git commit -m "메시지"
git push
```

---

## Troubleshooting

<details>
<summary>학교 리눅스 서버에서 한글이 깨지는 문제</summary>

- **문제:** 학교 리눅스 서버에서 한글을 입력하면 글자가 깨집니다.

- **원인:** 서버가 한글을 지원하지 않는 설정으로 구성되어 있습니다.

- **해결:** 한글 작성은 Windows 노트북의 VS Code에서 하고, Git으로 GitHub에 반영하는 방식으로 작업 환경을 분리했습니다.

</details>

---

## Roadmap

- [x] Git, SSH 키 설정 및 GitHub 연동
- [x] README 포트폴리오 작성
- [ ] 3학년 현업 투입 전까지 C언어, 회로, 디지털 설계 기초 숙달

---

## Contact

- GitHub: [qkrtjdqja0304-boop](https://github.com/qkrtjdqja0304-boop)
- 이메일: [qkrtjdqja0304@gachon.ac.kr](mailto:qkrtjdqja0304@gachon.ac.kr)
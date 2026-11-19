# Foldy 개인정보 정책 / Privacy policy

Foldy는 사용자가 켜거나 직접 실행한 기능을 제외하면 어떤 정보도 다른 네트워크 시스템으로 보내지 않습니다.
Foldy will not transfer any information to other networked systems unless specifically requested by the user or the person installing or operating it, as listed below.

| 기능 / Feature | 보내는 곳 / Destination | 보내는 내용 / What is sent | 끄는 방법 / How to turn off |
| --- | --- | --- | --- |
| 업데이트 확인 / Update check | GitHub (`api.github.com`, `github.com`) | 일반 HTTPS 요청(최신 릴리스 정보 조회, 설치 파일 다운로드). 사용자 정보는 보내지 않음 / Plain HTTPS requests for the latest release and its installer; no user data | 설정 → 업데이트 → 끄기 / Settings → Update → Off |
| 오류 자동 보고 / Crash reports | Foldy crash relay (Cloudflare Worker) → GitHub 공개 이슈 / public GitHub issue | 앱·Windows 버전, 예외 종류, 스택 프레임. 보내기 전에 경로·사용자 이름·컴퓨터 이름·메일 주소를 지움 / App & Windows version, exception type, stack frames, with paths, user name, machine name and e-mail addresses removed | 기본 꺼짐. 보낼 때마다 묻고, 설정 → 오류 보고에서 끌 수 있음 / Off by default; asks before sending; Settings → Crash reports |
| 버그 신고 버튼 / Report a bug | 브라우저로 GitHub 이슈 페이지 / GitHub issue page in your browser | 사용자가 확인하고 직접 제출 / You review and submit it yourself | 누르지 않으면 아무것도 보내지 않음 / Nothing is sent unless you click it |
| SFTP·SSH, Git 원격 / SFTP, SSH, Git remotes | 사용자가 지정한 서버 / Servers you specify | 사용자가 요청한 파일·명령 / Only the files and commands you request | 사용하지 않으면 연결하지 않음 / No connection unless you use it |

- 색인 서비스(FoldyIndexer)가 만드는 파일 이름 색인은 이 컴퓨터에만 저장되며 밖으로 보내지 않습니다.
  The file-name index built by the FoldyIndexer service stays on this computer and is never uploaded.
- 광고, 사용 통계, 추적 기능은 없습니다. / There are no ads, analytics or tracking.
- 제거하면 프로그램과 서비스가 함께 지워집니다 (README의 제거 방법 참고). / Uninstalling removes the program and the service.

문의 / Contact: <https://github.com/chadolkr/Foldy-releases/issues>

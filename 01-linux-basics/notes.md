# Linux 서버 기초

Ubuntu Server 26.04 LTS를 VMware에 설치하고 기본 서버 운영을 실습했습니다.

## 진행 내용
- VMware에 Ubuntu Server 설치 (SSH 서버 포함 설치)
- 기본 명령어 실습: 파일/디렉토리 조작(cd, ls, mkdir), 텍스트 편집(nano)
- 시스템 확인: 프로세스(ps, top), 메모리/디스크(free, df)
- 권한 관리: chmod, sudo 개념
- 네트워크: IP 확인(ip addr), 포트 확인(ss -tuln)
- SSH 원격 접속 성공 (Windows 터미널 → Ubuntu Server)
  cmd에서 [ssh siyeon@192.168.223.133] 접속, 비밀번호 입력
  => 실무에서 서버 관리하는 방법(ssh가 원격 쉘 제공하는 프로그램이기 때문)

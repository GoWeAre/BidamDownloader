# Bidam's Video & Audio Downloader

유튜브 · 치지직(클립 / 다시보기) · SOOP 영상을 MP4 로 받거나 MP3(192k) 로 추출하는 Windows 앱입니다.

## 받기

[릴리스 페이지](https://github.com/goweare/BidamDownloader/releases/latest)에서 `BidamDownloader.exe` 를 받으세요. 설치 과정 없이 파일 하나만 실행하면 됩니다.

처음 실행할 때 "Windows의 PC 보호" 화면이 뜨면 **추가 정보 → 실행**을 누르세요. 코드 서명 인증서가 없는 개인 제작 프로그램이라 나오는 안내입니다.

## 쓰는 법

1. 실행하고 URL 을 붙여넣은 뒤 엔터 (또는 "다운로드 목록에 추가")
2. 최대 10개까지 동시에 진행되고, 완료된 파일은 "저장 위치" 폴더에 생깁니다

- 재생목록이 붙은 URL(`watch?v=...&list=...`)은 그 영상 하나만 받습니다.
- 취소하면 임시 파일까지 자동으로 정리됩니다. 중간 파일은 저장 폴더가 아니라 시스템 임시 폴더에만 생깁니다.
- 같은 영상을 다시 받으면 파일명 끝에 `(1)`, `(2)` 가 붙습니다.
- 실패한 작업은 원인이 표시되고, 클릭하면 로그(`%APPDATA%\GoWeAre\BidamDownloader\error.log`)가 열립니다.
- 치지직 파일명은 `[YYMMDD] 치지직_제목_클립` / `..._영상` 형식입니다.

## 이 저장소에 대해

배포 전용 저장소입니다. 실행 파일 릴리스와 버전 정보만 있고, 소스 코드는 들어 있지 않습니다.

## 사용 시 유의

내려받은 영상의 저작권은 원저작자에게 있습니다. 각 플랫폼의 이용약관과 저작권법이 허용하는 범위(개인적 이용 등) 안에서만 사용하세요. 이 프로그램은 아무런 보증 없이 있는 그대로 제공되며, 사용에 따른 책임은 사용자에게 있습니다.

## 라이선스

개인 사용은 무료입니다. 자세한 조건은 [LICENSE](LICENSE) 를 보세요.

## 서드파티 고지

포함된 제3자 소프트웨어와 각각의 라이선스는 [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) 에 정리되어 있습니다.

- [yt-dlp](https://github.com/yt-dlp/yt-dlp) — Unlicense
- [FFmpeg](https://ffmpeg.org/) — 실행 파일에 `ffmpeg.exe` 를 동봉합니다. 동봉한 빌드의 라이선스(LGPL 2.1+ 또는 GPL 2+, 빌드 옵션에 따라 다름)를 따르며, 해당 소스는 [ffmpeg.org](https://ffmpeg.org/download.html) 에서 받을 수 있습니다.

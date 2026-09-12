# 제3자 구성요소 고지

`BidamDownloader.exe` 에는 아래 소프트웨어가 포함되어 있습니다. 각 구성요소는 자신의
라이선스를 따르며, 이 프로젝트의 [LICENSE](LICENSE) 는 그 부분에 적용되지 않습니다.

## FFmpeg

- 출처: https://ffmpeg.org/
- 라이선스: 동봉한 빌드의 구성에 따라 **LGPL 2.1 이상 또는 GPL 2 이상**
- 용도: 영상·음성 합치기, MP3 추출
- 형태: 별도의 실행 파일(`ffmpeg.exe`)로 동봉되며, 앱이 별도 프로세스로 호출합니다.
- 소스 코드: https://ffmpeg.org/download.html 에서 받을 수 있습니다.
  동봉한 빌드에 해당하는 소스가 필요하시면 이 저장소의 이슈로 요청해 주세요.

FFmpeg 라이선스 전문: https://www.ffmpeg.org/legal.html

## yt-dlp

- 출처: https://github.com/yt-dlp/yt-dlp
- 라이선스: Unlicense (퍼블릭 도메인)
- 용도: 각 플랫폼에서 영상 정보와 스트림을 가져오는 핵심 기능

## Python

- 출처: https://www.python.org/
- 라이선스: PSF License
- 용도: 실행 파일에 포함된 런타임

---

빠진 고지나 잘못된 내용이 있으면 이슈로 알려 주세요. 바로 고치겠습니다.

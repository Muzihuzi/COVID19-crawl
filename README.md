# COVID19-crawl
Crawl COVID-19 data from Ministry of Health and Welfare Korea
- Made by [Jeongmin Park](https://github.com/Muzihuzi)
- Languages
	* [한국어](#한국어)
- OS
	* Windows 환경
	* Linux 환경

## 한국어
> 코로나바이러스 국내 감염자 웹크롤러

### 설치 방법
#### Windows 환경
1. 이 레포지토리를 내려받습니다.
1. [Python](https://www.python.org/downloads/) 인스톨러를 내려받아 설치(버전 2.6 이상)합니다. [pip](https://pypi.org/project/pip/)와 함께 설치되어야 합니다.
1. 명령 프롬프트에서 `pip install requests`를 입력해 [Requests](https://pypi.org/project/requests/)를 설치합니다.
1. 명령 프롬프트에서 `pip install bs4`를 입력해 [Beautiful Soup 4](https://pypi.org/project/beautifulsoup4/)를 설치합니다.
1. 배치 파일(`txt.bat`) 혹은 실행파일(`txt.exe`) 을 실행시킵니다. 
  * 두파일 다 같은 기능을 합니다
1. 결과가(`read.txt`)에 저장됩니다 감염자,완치자,사망자 순으로 정렬됩니다.

#### Linux 환경
1. 이 레포지토리를 내려받습니다.
1. [Python](https://www.python.org/downloads/) 인스톨러를 내려받아 설치(버전 2.6 이상)합니다. [pip](https://pypi.org/project/pip/)와 함께 설치되어야 합니다.
1. 터미널에서 `pip install requests`를 입력해 [Requests](https://pypi.org/project/requests/)를 설치합니다.
1. 터미널에서 `pip install bs4`를 입력해 [Beautiful Soup 4](https://pypi.org/project/beautifulsoup4/)를 설치합니다.
1. 배치 파일(`txt.bat`) 혹은 실행파일(`txt.exe`) 을 실행시킵니다. 
  * 리눅스에서 __윈도우즈 전용 파일__ 실행법은 [이 글을 참고해 주세요](https://sergeswin.com/1092)
1. 결과가(`read.txt`)에 저장됩니다 감염자,완치자,사망자 순으로 정렬됩니다.

### 라이선스
- CC BY-SA 2.0 KR




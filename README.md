# Documents Search Projects
* * *
Elasticsearch, Nori 형태소 분석기, FSCrawler로 구현한 문서 검색엔진 입니다.

참고한 문서, 주소 URL을 하단에 작성 하였습니다.

pptx, pdf, word 등의 문서를 엘라스틱서치에 노리 형태소 분석기를 통해 인덱싱 합니다.

FSCrawler로 주기적으로 업데이트 합니다.

***  

## Architecture
```xml
업데이트 예정
```

## Prerequisite
1. 로컬 혹은 서버에 [도커](https://docs.docker.com/get-docker/), [도커 컴포즈](https://docs.docker.com/compose/install/)가 설치 되어 있어야 합니다.
2. 본인은 Mac에서 개발 하였고, 도커가 설치 되는 모든 환경에서 가능 합니다.
3. web/index.html 수정이 필요할 수도 있습니다.

아래 참고한 블로그 2의 코드에서 ajax로 가져오는 json 타입의 data와 부트스트랩 CDN을 사용하도록 수정 하였고 

본인의 원하는 것에 맞게 퍼블리싱이 필요 할 수도 있습니다.

## How to Install 
```xml
1. 소스를 클론 한뒤 web 으로 사용되는 nginx를 빌드 합니다.
2. FSCrawler가 생성하는 Mapping에 사용되는 _settings.json을 본인이 사용할 형태소 분석기에 맞게 수정 합니다.
```
현재 이 레포지토리에 있는 [_settings.json](https://github.com/wsj31013/searchCrawler/blob/main/config/_default/7/_settings.json)은 노리, 엘라스틱서치7에 맞게 수정된 파일 입니다.



## How to Use
소스를 클론 받아 직접 구축 해보는 튜토리얼을 아래 저의 기술 블로그에 포스팅 하였습니다.

_사용법 : [내 블로그](https://cobain.me/2020/10/19/ElasticSearch-FSCrawler.html)_


## Ref
_FSCrawler Github URL : [FSCrawler Github](https://github.com/dadoonet/fscrawler)_

_FSCrawler Documents URL : [FSCrawler Readthedocs](https://fscrawler.readthedocs.io)_

_ElasticSearch Document URL : [Elasticsearch Official Home](https://www.elastic.co/guide/en/elastic-stack-get-started/current/get-started-docker.html)_

_참고한 블로그 1: [URL1](https://naggingmachine.tistory.com/830)_

_참고한 블로그 2: [URL2](https://blog.naver.com/icelemonteainkr/221828689765)_






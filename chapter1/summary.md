
# 1. 코딩스타일

## 1.1 읽기 쉬운 코드
- 축약적이거나 함축적인 변수명은 피한다
- 함수 인자의 이름들은 꼭 써준다
- 클래스와 메서드를 문서화한다
- 코드에 주석을 꼭 달도록 한다
- 재사용 가능한 함수 또는 메서드 안에서 반복되는 코드들은 리팩터링을 해둔다
- 함수와 메서드는 가능한 한 작은 크기를 유지한다. 어림잡아 스크롤 없이 읽을 수 있는 길이가 적합하다

## 1.2 PEP8
- PEP8: 파이썬 공식 스타일 가이드
- [flake8](http://flake8.pycqa.org/en/latest/user/configuration.html)을 이용하여 코드품질을 유지하자

## 1.3 임포트에 대해
- 표준 라이브러리 임포트, 코어 장고 임포트, 장고와 무관한 외부 앱 임포트, 프로젝트 앱 임포트 순으로 임포트 문들을 구성한다.

## 1.4 명시적 성격의 상대 임포트 이용하기
- 명시적 상대 임포트: from .models import WaffleCone
- 앱의 이름을 변경할 일이 생기거나, 이름이 충돌되는 경우를 피할수 있다.

## 1.5 import *는 피하자
- 다른 파이썬 모듈의 이름공간들이 현재 작업하고 있는 모듈의 이름공간에 추가로 로딩되거나 기존 것 위에 덮여 로딩되는 일이 발생할수 있다.

## 1.6 장고 코딩 스타일

### 1.6.1 [장고 코딩 스타일](https://docs.djangoproject.com/en/1.10/internals/contributing/writing-code/coding-style/)
- isort

### 1.6.2 URL 패턴 이름에는 대시대신 밑줄을 이용한다
- [smarturl](https://amitu.com/smarturls/)을 활용하여 url을 편하게 사용하자

### 1.6.3 탬플릿 블록 이름에 대시 대신 밑줄을 이용한다

## 1.7 자바스크립트, HTML, CSS 스타일 선택하기

### 1.7.1 자바스크립트 스타일 가이드
- 공식 스타일 가이드가 없으므로, 선호하는 것을 선택후 사용. 단, 특정 스타일 가이드를 포함한 자바스크립트 프레임워크를 사용한다면 해당 스타일 가이드를 따르기

## 1.8 통합개발환경이나 텍스트 편집기에 종속되는 스타일의 코딩은 지양한다.

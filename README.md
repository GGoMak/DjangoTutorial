# Django Tutorial

  - Django Document : 첫 번째 장고 앱 작성하기

## Part 1

  - Django 설치 및 프로젝트 생성
    - pip install django
    - django-admin startproject mysite
    
  - polls 앱 시작
    - python manage.py startapp polls
    
  - 첫 번 째 뷰 작성
    - view.py 작성
    - polls/urls.py 작성
    - mysite/urls.py 작성

## part 2

  - mysite/settings.py
    - 타임존 변경 ('UTC' -> 'Asia/Seoul')
    - INSTALLED_APPS 추가 (polls.apps.PollsConfig)
    
  - 모델 만들기
    - polls/models.py 작성(Question, Choice 클래스)
    
  - API를 이용하여 DB 추가
  
  - 관리 사이트에서 poll app을 변경가능하도록 만들기

## part 3

  - 뷰 추가하기
    - detail, results, vote
    - urls.py 수정
    - index.html, detail.html 작성
    
  - 404 에러 추가
    - get_object_or_404()
    
## part 4

  - Write a minimal form
    - detail.html 수정
  
  - vote, result API 작성
  
  - result.html 작성
  
  - views 수정
    - generic으로 변경

## part 5

  - 테스트 코드 작성
    - QuestionModelTests
    - QuestionIndexViewTests
    - QuestionDetailViewTests
    
  - View 개선
    - IndexView : get_queryset()
    - DetailView : get_queryset()

## part 6

  - 프론트 엔드 작성
    - style.css 작성
    - background 이미지 추가

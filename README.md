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

```
# oz-mini-be-12-team4

oz_form/                        # 프로젝트 폴더
├── .venv                       # 의존성 패키지를 모아두는 가상환경
├── .gitignore                  # github에 올리지 않을 파일들을 관리
├── app/                        # Flask 애플리케이션 코드 폴더
│   ├── __init__.py(제공)        # 앱 초기화 및 설정 파일
│   ├── routes/                 # view 및 route 정의
│   │   ├── __init__.py         # route의 blueprint 관리 파일
│   │   ├── stats_routes.py(제공)# answers 통계 관련 파일
│   │   ├── users.py            # users 테이블 관련 파일
│   │   ├── questions.py        # quetions 테이블 관련
│   │   ├── choices.py          # choices 테이블 관련
│   │   ├── images.py           # images 테이블 관련
│   │   └── answers.py          # answers 테이블 관련
│   ├── models.py               # SQLAlchemy 모델 정의
├── scripts/(제공)               # 배포 시 사용할 script 파일들
├── launch.sh(제공)              # 배포 환경에서 flask를 실행하기 위한 script
├── terminate.sh(제공)           # 배포 환경에서 flask를 종료하기 위한 script
├── config.py(제공)              # Flask 및 데이터베이스 설정 파일
├── requirements.txt(제공)       # 필요한 Python 패키지 목록
├── run.py(제공)                 # 개발환경에서 테스트 하는 실행 파일
├── wsgi.py(제공)                # 배포환경에서의 실행 파일
└── migrations/(자동 생성)        # Flask-Migrate를 위한 DB 마이그레이션 파일
```

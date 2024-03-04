# StudyFastAPI

## 설치 라이브러리
```
pip install fastapi
pip install "uvicorn[standard]"
```

## 실행 방법
```
uvicorn main:app --reload --host=0.0.0.0 --port=8000
```

1. secret.json에서 db 설정을 변경한다
2. 실행한다
3. 테이블 자동생성
4. 127.0.0.1:8080 에서 확인한다

## 참고
https://tech.osci.kr/fastapi-파이썬으로-간단하게-웹-api-만들기/

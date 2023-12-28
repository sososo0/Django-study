# Django-study
Django로 웹 애플리케이션 만들기

### Django 가상환경 구축 및 설치 

- **python은 3.x 버전으로 설치**

#### 가상환경 구축하기 

- 파이썬 모듈 중 venv라는 모듈을 사용하여 가상 디렉토리 생성 

```
python -m venv mywebsite 
```

#### Django 설치 

1) mywebsite 디렉토리로 이동

2) scripts 디렉토리로 이동  

3) activate.bat 실행 
    ```
    activate.bat
    ```

4) 가상환경 내부에서 

    ```
    pip install Django 
    ```

##### Django 설치 후 버전 확인 

```
python -m django --version 
```

##### 가상환경 빠져나오는 방법 

- deactivate 사용 

    ```
    deactivate
    ```
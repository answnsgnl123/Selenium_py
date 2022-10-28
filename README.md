# Selenium_py
Selenium_Crawling_AutoCode

## driver err
[이전 버전은 상관없지만 리눅스환경이나 높은버전은 config set 필수]</br>
```chrome_options = webdriver.ChromeOptions()```</br>
```chrome_options.add_argument('--headless')```</br>
```chrome_options.add_argument('--no-sandbox')```</br>
```chrome_options.add_argument("--single-process")```</br>
```chrome_options.add_argument("--disable-dev-shm-usage")```</br>
```driver = webdriver.Chrome(path, chrome_options=chrome_options)```</br>

### 참고사이트
- [크롬드라이버 환경변수에러](https://synkc.tistory.com/entry/Chromedriver-DevToolsActivePort-file-doesnt-exist-%EC%97%90%EB%9F%AC-%ED%95%B4%EA%B2%B0%EB%B2%95)</br>
- [크롬 드라이버 다운](https://sites.google.com/chromium.org/driver/)</br>
- [셀레니움 install](https://somjang.tistory.com/entry/Ubuntu-Ubuntu-%EC%84%9C%EB%B2%84%EC%97%90-Selenium-%EC%84%A4%EC%B9%98%ED%95%98%EA%B3%A0-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0)</br>
### 참고 명령어
```google-chrome --version ```
```[window] chrome://version/```

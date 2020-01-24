# practice-nodejs
### pm2 실행 참고
```sh
pm2 start main.js --watch --ignore-watch="data/*"
```
pm2를 실행할 때 --watch 옵션으로 파일이 변경되면 앱을 리로드하게
data 디렉토리의 파일이 수정되더라도 watch하지 않도록 함
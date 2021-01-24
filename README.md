# nodejs_study
node.js study with javascript

[생활코딩](https://opentutorials.org/module/3549)

[Node.js Documents]<https://nodejs.org/dist/latest-v14.x/docs/api/>

[PM2]<https://pm2.keymetrics.io/>

```
pm2 start main.js --watch

pm2 start main.js --watch --no-demon 
// (background 아니게 실행)

pm2 start main.js --watch --ignore-watch="data/*" --no-daemon
//파일 추가 시 재시작하기에 메모리에 문제가 생길 수 있기때문에 이를 무시하도록 설정
```

-> 바로 실시간 변경을 반영한다.


```
//에러사항 등을 보여 줌 (node main.js를 실행할 때 처럼 바로바로 보여주지 않기 때문에 log기능 사용 필요함

pm2 log

```

```
pm2 kill

pm2 stop <id>
```


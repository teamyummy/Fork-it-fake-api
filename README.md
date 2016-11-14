서버 설치
```shell
npm install -g json-server
```

서버 시작
```shell
npm start
```

다른 data json을 사용하고 싶을 때
```shell
json-server other.json --watch
```

맛집 목록 조회
```
http://localhost:3000/restaurants
```

맛집 상세 조회
```
http://localhost:3000/restaurants/1
http://localhost:3000/restaurants/2
```

맛집 리뷰 목록
```
http://localhost:3000/restaurants/1/reviews
http://localhost:3000/restaurants/2/reviews
```

리뷰 상세조회
```
http://localhost:3000/reviews/1
http://localhost:3000/reviews/2
http://localhost:3000/reviews/3
http://localhost:3000/reviews/4
```

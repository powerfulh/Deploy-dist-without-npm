### nm.tar

node_modules 압축 파일

압축 옵션
```
tar -cvzf nm.tar node_modules
```

옵션 설명
* c: 압축할래
* v: 압축 과정 콘솔로 보여줘
* z: 더 좋은 압축 옵션
* f: 압축 파일명 지정 (필수)

압축 풀기
```
tar -xvf nm.tar
```

옵션 설명
* x: 압축 풀래
* v: 푸는 과정 콘솔로 보여줘
* f: 풀 파일명 지정 (필수)

***

### web.js

웹서버 실행 파일

빌드된 dist를 루트에 위치시킨후 웹 서버를 기동한다
```
node web.js
```
# HTML Setting (Sass / autoprefixer)

## node_module 설치

```
$ npm install 
```

## Sass Comfile (--watch) / autoprefixer (--watch)

```
$ npm run sass:watch
$ npm run postcss:watch
```

## 개발모드 자동 실행

```
$ npm start [http://localhost:3000/]
```

## 디렉토리 구조

```
├── _node_modules
|
├── assets
|   ├── scss // 작업용 scss
|   ├── css // scss 컴파일 한 css
|   └── style // autoprefixer 적용된 최종 css
|
├── package.json
├── package-lock.json
└── .gitignore
```

---

> HTML 작업시 sass 및 autoprefixer 를 사용하기 위해 준비한 설정

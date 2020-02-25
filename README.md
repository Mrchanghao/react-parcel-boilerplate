# react-parcel-boilerplate

parcel bundler를 이용한 미니 프로젝트용 리액트 boilerplate

## Getting Started 

```cmd
git clone https://github.com/Mrchanghao/react-parcel-boilerplate.git
```

start dev mode
```cmd
npm run dev or yarn dev
```

bundle the app
```cmd
npm run build or yarn build
```

## package

- [babel-plugin-module-resolver](https://github.com/tleunen/babel-plugin-module-resolver)

```js
/// 사용법
import reactImage from '@images/react.png'
// not required
import reactImage from '../../assets/react.png'
```

.babelrc에 지정된 디렉토리를 입력 해 준다. 
```js
[
      "module-resolver",
      {
        "root": ["./src"],
        "alias": {
          "@images": "./assets"
        }
      }
    ]
```


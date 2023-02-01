# TS_nextJs_RTK

- typescript
- Next.js
- redux-tookit
- redux-logger
- redux-persist
- next-redux-wrapper
- styled-component
- redux-thunk

나중에 tsconfig.json 설정은 따로 해줘야함!

### Layout 컴포넌트 사용시

props.chidren 쓸 때 타입을

```tsx
type Props = {
  children: React.ReactNode;
};
```

이렇게 추가해주어야함

### window.ethereum 사용시

- index.d.ts에 interface 정의 해준 후 사용해야 인식함

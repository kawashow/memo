オブジェクトの型定義

[key: string]でキーの型を定義できる

```javascript
type DynamicProps = {
  [key: string]: {
    value1?: string,
    value2?: number,
  },
};
```

---

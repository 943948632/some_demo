>��װ

�����windows�£�Ϊ������ʹ��tsc����������ȫ�ְ�װһ��ts

```
npm install --save-dev --g typescript
```

����Ҫȫ�ְ�װ�Ļ���ȥ�� ``--g`` ������

```
npm install --save-dev typescript
```

>���� tsconfig.json

```
tsc --init
```

[��������ļ���˵����Ӣ�İ棩](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)

Ҳ����ֱ�ӿ����ļ�ÿ�е�ע�͡�

> ת��ָ���ļ�

tsc �ļ������·���������ִ�� tsc �����·����

ʾ����

```
tsc src/app.ts
```

���Զ����� ``src/app.js`` �ļ���


> webpack �� ts

��װ loader ����Ϊ�� ``.ts`` ��β���ļ���

```
npm install ts-loader
```

ע�⣬webpack��ʹ�� ts��Ҳ����ȻҪ��װ ts �ġ�

```
npm install typescript
```

ע��

1. ֻ��Ҫ��װ ts-loader �� typescript��
2. Ȼ���� ``webpack.config.js`` ����һ�� loader��
3. �Ϳ����� webpack ��ʹ�� ts �ˣ�
4. ���ر� DEMO ����ֱ�Ӳ鿴Ч����

> ts ��� react

����������� webpack �Ļ����Ͻ��н�һ�������á�

�� ``tsconfig.json``���������ã�

[TypeScript�����ļ�tsconfig����.md](https://github.com/hstarorg/HstarDoc/blob/master/%E5%89%8D%E7%AB%AF%E7%9B%B8%E5%85%B3/TypeScript%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6tsconfig%E7%AE%80%E6%9E%90.md)

```
"sourceMap": true,
"noImplicitAny": true,
"module": "commonjs",
"target": "es5",
"jsx": "react",
"allowSyntheticDefaultImports": true
```
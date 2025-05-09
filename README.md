# @kspace-trk/remix-vercel-adapter

これは[@vercel/remix](https://github.com/vercel/remix)のフォークで、@remix-run/dev 2.16系との互換性を持たせるために更新しました。

## 変更点
- パッケージバージョンを2.15.3から2.16.6に更新
- @remix-run/devを2.16.6に更新
- @remix-run/nodeを2.16.6に更新
- @remix-run/server-runtimeを2.16.6に更新

## 使用方法
```bash
npm install @kspace-trk/remix-vercel-adapter
```

```js
// vite.config.ts
import { vercelPreset } from "@kspace-trk/remix-vercel-adapter/vite";
```

## ライセンス
このパッケージは元のRemixリポジトリと同じくMITライセンスの下で公開されています。

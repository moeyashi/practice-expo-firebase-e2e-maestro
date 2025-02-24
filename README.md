# Expo maestro

0. 事前準備

- (Windowsの場合) 浅いディレクトリにクローンする。
    - 深いディレクトリの場合、`ninja: error: mkdir(*): No such file or directory`のエラーが出る
- 環境変数に`ANDROID_HOME`を設定
- `npm i`
- `maestro`のinstall

1. build

```bash
npm run android:prebuild
```

2. run maestro

```bash
npm run android
# 別ターミナルで
maestro test ./maestro/expand_test.yml
```
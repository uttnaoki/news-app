## sec2

- キャッシュをクリアして expo start
  - `expo start -c`
- Android シミュレーターのインストール
  - https://docs.expo.io/versions/v36.0.0/workflow/android-studio-emulator/
- エミュレーターで起動できない
  1. expo を一度落として再起動する
  2. expo start したターミナルにて ctrl + c で終了できます。
  3. 再起動する際 expo start -c と-c オプションを追加するとキャッシュクリアして再起動できます。
  4. node_modules をクリアしてみる

## sec4

- Lorem Picsum(ダミー画像の表示サービス)
  - https://picsum.photos/
- テキストレイアウト
  - alignItems: flexDirection の垂直方向に対する位置
  - justifyContent: flexDirection の方向に対する位置

## sec6

- News Api
  - https://newsapi.org/
- expo install expo-constants

## sec7

```sh
# React Navigation インストール
npm install @react-navigation/native

# Installing dependencies into an Expo managed project
expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view

# createStackNavigator
npm install @react-navigation/stack

# react-native-webview
expo install react-native-webview
```

## sec8

```sh
# Redux
npm install redux react-redux

# react-native-debugger
brew update && brew cask install react-native-debugger

# redux-devtools-extension
npm install --save redux-devtools-extension
```

- React Native Debugger
  - `cmd+space`でアプリを検索し、起動
  - 最初は 8081 ポートで立ち上がるため、ポートを変更
    - 上部バーから`Debugger > New Window > confirm`(自動で 19001 に設定される)

```sh
# react-navigation/bottom-tabs
npm install @react-navigation/bottom-tabs
```

# これは何？
Xcode用コードジェネレータ[Generamba](https://github.com/rambler-digital-solutions/Generamba)のためのVIPERテンプレートです。
命名や構成は[こちら](https://github.com/pedrohperalta/Articles-iOS-VIPER)に沿っています。

# 使い方(git)
1) プロジェクトのルートディレクトリで`generamba setup`
2) `Rambafile`のテンプレートの部分を以下のように変更

```
### Templates
catalogs:
- 'https://github.com/Yaruki00/GenerambaVIPERTemplate'
templates:
- {name: my_viper}
```

3) `generamba gen [モジュール名] my_viper`でモジュール作れます

# 使い方(ファイル)
1) プロジェクトのルートディレクトリで`generamba setup`
2) このリポジトリの`my_viper`ディレクトリを適当な場所に配置
3) `Rambafile`のテンプレートの部分を以下のように変更

```
### Templates
templates:
- {name: my_viper, local: '/絶対パス/my_viper/'}
```

3) `generamba gen [モジュール名] my_viper`でモジュール作れます
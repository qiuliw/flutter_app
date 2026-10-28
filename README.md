# flutter_app

跨平台 flutter 模板工程（仅包管理，不含具体工程）。

flutter 版本 取 mise 和 devenv 短的一方。

## 创建工程

```sh
flutter create . --project-name xxx
```

## Linux

nix [devenv](https://devenv.sh/) + nixGL

```sh
devenv shell
linux-run
# 或: nixGL flutter run -d linux
```

## Windows

[mise](https://mise.jdx.dev/) + flutter 默认支持。

```sh
mise install
flutter run -d windows
```

## Android

[mise](https://mise.jdx.dev/) + android-cli + jdk + just

```sh
mise install
just emu-start
flutter run
```

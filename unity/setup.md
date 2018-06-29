# Unityのセットアップガイド

## はじめに

Oculusアプリから開発者モードを有効にする。Webからの登録作業は私が済ませたので不要なはず。

## インストールするもの

* [Android Studio](https://developer.android.com/studio/?hl=ja#downloads)
  * Windows (64-bit)
* [JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
  * Java SE Development Kit 8u172
  * Windows x64
* [Unity Hub](https://unity3d.com/jp/get-unity/download)
* Unity
  * Unity Hub経由でのインストールがおすすめ
  * Unity 2018.1.4f1

## 各種セットアップ

### JDK

インストールするだけ

### Android Studio

* SDKのインストール
  * 右下の歯車アイコンからSDK Managerを選択
    <div style="text-align:center">
      <img src="./img/select_sdk_manager.png" alt="SDK Managerを開く"/>
    </div>
  * 以下の画像の通りにSDKを追加(最後にApplyを押してインストールする)
    <div style="text-align:center">
      <img src="./img/sdk_platforms.png" alt="SDK Platforms"/>
      <img src="./img/sdk_tools.png" alt="SDK Tools"/>
    </div>

### Unity

* プラットフォームをAndroidにする。
  * FileからBuild Settingsを開く
    <div style="text-align:center">
      <img src="./img/open_build_settings.png" alt="Build Settingsを開く"/>
    </div>
  * Androidを選択
    <div style="text-align:center">
      <img src="./img/select_android.png" alt="Androidを選択"/>
    </div>
  * Switch Platformをクリック
    <div style="text-align:center">
      <img src="./img/click_switch_platform.png" alt="Switch Platformをクリック"/>
    </div>
* Player Settingsの変更
  * Player Settingsをクリック
    <div style="text-align:center">
      <img src="./img/click_player_settings.png" alt="Player Settingsをクリック"/>
      <img src="./img/is_player_settings.png" alt="右側にある"/>
    </div>
  * Company NameとProduct Nameの変更
    * お好みの名前に変更する
      <div style="text-align:center">
        <img src="./img/change_name.png" alt="名前の変更"/>
      </div>
  * Package Nameの変更
    * 設定したCompany NameとProduct Nameをもとにして "com.{Company Name}.{Product Name}" の形にする
      <div style="text-align:center">
        <img src="./img/change_package_name.png" alt="Packege Nameの変更"/>
      </div>
  * Minimum API Levelの変更
    * "Android 7.1 'Nougut' (API level 25)" にする
      <div style="text-align:center">
        <img src="./img/change_minimum_api_level.png" alt="Minumum API Levelの変更"/>
      </div>
  * XR Settingsの変更
    * XR Settingsを選択する(下のほうにスクロールするとある)
    * Virtual Reality Supportedにチェック
      <div style="text-align:center">
        <img src="./img/check_virtual_reality_supported.png" alt="Virtual Reality Supportedにチェック"/>
      </div>
    * Virtual Reality SDKsでOculusを追加(クリック)
      <div style="text-align:center">
        <img src="./img/add_oculus.png" alt="Oculusの追加"/>
      </div>
* JDKとAndroid SDKのパスを設定する。
  * EditからPreferencesを開く
    <div style="text-align:center">
      <img src="./img/open_preferences.png" alt="Preferencesを開く"/>
    </div>
  * External Toolsからパスを設定する
    <div style="text-align:center">
      <img src="./img/path.png" alt="パスの設定"/>
    </div>

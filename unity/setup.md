# Unityのセットアップについて

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

### Unity

* JDKとAndroid SDKのパスを設定する。
  * EditからPreferencesを開く
    ![Preferencesを開く](./img/open_preferences.png)
  * External Toolsからパスを設定する
    ![パスの設定](./img/path.png)
* プラットフォームをAndroidにする。
  * FileからBuild Settingsを開く
  ![Build Settingsを開く](./img/open_build_settings.png)
  * Androidを選択
    ![Androidを選択](./img/select_android.png)
  * Switch Platformをクリック
    ![Switch Platformをクリック](./img/click_switch_platform.png)
* Player Settingsの変更
  * Player Settingsをクリック
    ![Player Settingsをクリック](./img/click_player_settings.png)
    ![右側にある](./img/is_player_settings.png)
  * Company NameとProduct Nameの変更
    * お好みの名前に変更する
      ![名前の変更](./img/change_name.png)
  * Package Nameの変更
    * 設定したCompany NameとProduct Nameをもとにして "com.{Company Name}.{Product Name}" の形にする
      ![Packege Nameの変更](./img/change_package_name.png)
  * Minimum API Levelの変更
    * "Android 7.1 'Nougut' (API level 25)" にする
      ![Minumum API Levelの変更](./img/change_minimum_api_level.png)
  * XR Settingsの変更
    * XR Settingsを選択する(下のほうにスクロールするとある)
    * Virtual Reality Supportedにチェック
      ![Virtual Reality Supportedにチェック](./img/check_virtual_reality_supported.png)
    * Virtual Reality SDKsでOculusを追加(クリック)
      ![Oculusの追加](./img/add_oculus.png)

### JDK

インストールするだけ

### Android Studio
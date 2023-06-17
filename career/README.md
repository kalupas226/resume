# 職務経歴詳細

## NOT A HOTEL 株式会社(2022/06〜現在)

### 雇用形態

業務委託

### 概要

ホテルに関する機能がある「NOT A HOTEL」の iOS アプリや、ホテルで利用できるスマートホーム機能が搭載された iPad アプリの開発に業務委託として関わっています。

- 役割
  - 設計
  - コーディング
  - コードレビュー
- プロジェクト詳細
  - 以下の技術を利用した機能開発
    - The Composable Architecture
    - Combine・Swift Concurrency
    - SwiftUI (一部 UIKit)
    - SwiftPM
    - SwiftPM によるマルチモジュール・マルチプロジェクト
    - gRPC
    - Firebase Authentication, Firestore
  - The Composable Architecture のキャッチアップ、アップデートに追従するための方法の提案
  - Swift Package Plugins の導入
  - CI / CD (GitHub Actions, Bitrise) の整備
    - 複数のプロダクトが含まれるモノリポにおいて差分から適切なプロジェクトのテストを実行する workflow の作成
      - 将来的には Xcode Cloud を利用することでよりシンプルにしたいと考えている
    - Renovate で適切に更新されない依存関係を更新するための workflow の作成
  - iOS アプリおよび iPad アプリの機能開発、テストコードの整備
  - Remote Config による Feature Flag の導入

## Cookpad 株式会社(2022/05〜現在)

### 雇用形態

正社員

### 概要

料理レシピ検索アプリの「クックパッド」iOS アプリの開発や開発基盤の整備を行っています。

- 役割
  - 機能検討
  - 設計
  - コーディング
  - コードレビュー
- プロジェクト詳細
  - 以下の技術を利用した機能開発
    - UIKit・SwiftUI
    - VIPER
    - RxSwift・Combine・Swift Concurrency
    - Framework によるマルチモジュールプロジェクト
    - GraphQL
  - クックパッド iOS アプリにおける「買い物機能」の企画・開発・運用
  - 開発基盤の整備
    - fastlane Spaceship や App Store Connect API を用いて APNs 証明書更新作業の自動化を行うための調査
    - ライブラリの整備
    - RxSwift → Swift Concurrency への一部置き換え
    - The Composable Architecture の導入
      - The Composable Architecture を社内に広める活動
      - UIKit + SwiftUI なプロジェクトで問題なく動作する形式の模索
      - 画面遷移の方法についても独自の実装方法を考案 (内部的には UIKit の仕組みを利用するが、SwiftUI ライクに遷移できる形)
  - 採用系業務

## 株式会社 RAN(2022/03〜現在)

### 雇用形態

業務委託

### 概要

美容室向けの iOS アプリの開発に業務委託として関わっています。

- 役割
  - 設計
  - コーディング
  - コードレビュー
- プロジェクト詳細
  - 以下の技術を利用した機能開発
    - UIKit・SwiftUI
    - RxSwift・Combine・Swift Concurrency
  - RxSwift → Combine・Swift Concurrency への置き換え
  - SwiftUI の導入
  - SwiftUI でアプリを快適に開発するための各種ライブラリの導入
    - swiftui-navigation, swift-dependencies など
  - Bitrise, fastlane が用いられている CI / CD の整備

## Sansan 株式会社（2020/04〜2022/04）

### 雇用形態

正社員

### 概要

法人向け名刺管理サービス「Sansan」iOS アプリの開発や運用を行っていました。

- 役割
  - 機能検討
  - 設計
  - コーディング
  - コードレビュー
- プロジェクト詳細
  - 以下の技術を利用した機能開発
    - UIKit
    - VIPER
    - RxSwift
  - iOS プロジェクトへの XcodeGen の導入
  - iOS プロジェクトのマルチモジュール化
  - Bolt framework(Slack Bot), GitHub Actions を用いたリリースプロセスの自動化
  - Google Calendar API を利用した Google Calendar 連携機能の開発
  - テスト工数を削減を目的とした MagicPod の導入
  - Bitrise・fastlane の運用

# 学歴

公立はこだて未来大学システム情報科学部を卒業。同学の大学院システム情報科学研究科に進学しましたが、大学院 1 年の終わり頃に中退しました。  
大学では、情報工学について講義で学びながら、モバイルアプリケーションの開発を課外活動で行ったり、アルバイトで Web サイトを開発したりしていました。

## 大学時代にやっていたこと

### Flutter, Python を用いた地域学習システムの開発

大学の研究で、[北海道の地域史資料を活用した地域学習システム](https://ipsj.ixsq.nii.ac.jp/ej/?action=pages_view_main&active_action=repository_view_main_item_detail&item_id=197326&item_no=1&page_id=13&block_id=8)を開発しました。

- 役割
  - 機能検討
  - 設計
  - コーディング
- プロジェクト詳細
  - 北海道の地域史についてまとめられている 4 つの Web サイトを Python でスクレイピングした
  - スクレイピングした情報を DB に保存し、Python で自然言語処理を行い資料の関連付けを行った
  - 関連付けられた資料を取得できる簡易な API サーバーを Flask を用いて開発した
  - Flask サーバーを利用したタブレット用アプリケーションを Flutter Web を用いて開発した

### Flutter を用いたアプリの開発

大学の課外活動の一環で、北海道おさかな図鑑というサイトを利用した「[おさかな日和](https://play.google.com/store/apps/details?id=jp.co.osakana)」という簡易なアプリをリリースしました。

- 役割
  - プロジェクトリーダー
  - 機能検討
  - 設計
  - コーディング
- プロジェクト詳細
  - 少ない課外活動時間の中でアプリのリリースまで行いつつ、メンバーの教育も行った
  - アプリは Flutter で開発した

### Ruby on Rails を用いた Web サイトの開発

大学の開発アルバイトの一環で、「[市立函館博物館デジタルアーカイブ](https://hakohaku-archives.c.fun.ac.jp/)」という Web サイトの開発に携わっていました。

- 役割
  - 機能検討
  - コーディング
- プロジェクト詳細
  - 開発メンバーとして Ruby on Rails で構築された Web サイトの構成の理解、軽微な修正を行った

### 自治体用 iOS / Android アプリの開発

大学のプロジェクト学習という 1 年間を通して行われるプロジェクト型の講義で、とある自治体で開催されるイベントの管理やお知らせの掲載などを行うことができる iOS アプリを開発しリリースしました。また、リーダとしても活動し Android アプリ開発チームとコミュニケーションを取りながら、Android アプリのリリースも行いました。

- 役割
  - プロジェクトリーダー
  - 機能検討
  - コーディング
- プロジェクト詳細
  - プロジェクトリーダーとして iOS チーム、Android チーム、デザイナーとコミュニケーションを取りながら開発を主導し、自身も iOS アプリの開発を担当した

---
title: SpaceTab Privacy Policy
---

<!-- Source: ryocookie/spacetab docs/privacy-policy.md. Edit there and copy here. -->

# SpaceTab Privacy Policy

Last updated: October 3, 2026

SpaceTab is a Chrome extension that replaces your new tab page with your own links, notes, to-dos, clocks, timers, calendar events and weather. This policy explains what data SpaceTab handles and where it goes.

## Summary

- SpaceTab has no account and no server of its own. The developer does not receive any of your data.
- Everything you create is stored only in your browser on your device.
- SpaceTab contains no analytics, tracking or advertising, and never sells or shares data.

## Data stored on your device

SpaceTab stores the following in your browser's extension storage (`chrome.storage.local` and `localStorage`). It never leaves your device unless you export it yourself.

- Your spaces, cards, links, notes, to-dos, timer settings and display preferences
- Automatic backups of the above (up to the latest 12, plus one per day for 30 days)
- How often and when you open each link, used to sort "Frequent" links and search results. You can clear this at any time in Settings → Link history.
- The secret address of your Google Calendar, if you add a calendar card. It is excluded from exports.
- The result of the latest broken link check

Uninstalling the extension deletes all of this data.

## Network requests

SpaceTab only connects to other services for the features you choose to use:

| Feature | Service | What is sent |
| --- | --- | --- |
| Weather card | [Open-Meteo](https://open-meteo.com/) (geocoding and forecast APIs) | The place name you search for, and the latitude/longitude of the place you choose |
| Calendar card | Google Calendar (`calendar.google.com`) | A request to the secret iCal address you entered, to download your events |
| Broken link check | The websites in your links | A request to each link's URL to see whether the page still exists. Only runs when you press "Check" |
| Link icons | Chrome's built-in favicon service | The URLs of your links, handled locally by Chrome |

These requests go directly from your browser to those services and are subject to their own privacy policies. Open-Meteo does not require an API key or account.

## Permissions

- **storage, unlimitedStorage**: to save your data and backups on your device
- **favicon**: to show website icons next to your links
- **Access to calendar.google.com** (optional, asked when you add a calendar): to download your calendar events
- **Access to all sites** (optional, asked each time you run a broken link check and released afterwards): to check whether your links still work

## Changes

If this policy changes, the updated version will be published at this address with a new date.

## Contact

Questions about this policy: ryo19960220@gmail.com

---

# SpaceTab プライバシーポリシー

最終更新日: 2026年10月3日

SpaceTab は、新しいタブに自分のリンク・メモ・ToDo・時計・タイマー・カレンダーの予定・天気を表示する Chrome 拡張機能です。このポリシーでは、SpaceTab が扱うデータとその行き先を説明します。

## 要約

- SpaceTab にはアカウントも独自のサーバーもありません。開発者があなたのデータを受け取ることはありません。
- 作成したデータはすべて、あなたの端末のブラウザ内にだけ保存されます。
- 利用状況の分析・追跡・広告は一切含まず、データの販売や共有もしません。

## 端末に保存するデータ

次のデータを、ブラウザの拡張機能用の保存領域（`chrome.storage.local` と `localStorage`）に保存します。自分でエクスポートしない限り、端末の外には出ません。

- スペース・カード・リンク・メモ・ToDo・タイマーの設定・表示の設定
- 上記の自動バックアップ（新しい 12 件と、過去 30 日の各日 1 件）
- 各リンクを開いた回数と時刻（「よく使う」リンクと検索結果の並べ替えに使用。設定の「開いた記録」からいつでも消去できます）
- カレンダーのカードを追加した場合の、Google カレンダーの非公開アドレス（エクスポートには含めません）
- 直近のリンク切れチェックの結果

拡張機能をアンインストールすると、これらのデータはすべて削除されます。

## 外部への通信

SpaceTab は、あなたが使う機能のためにだけ外部のサービスに接続します。

| 機能 | 接続先 | 送る内容 |
| --- | --- | --- |
| 天気のカード | [Open-Meteo](https://open-meteo.com/)（地名検索・天気予報 API） | 検索した地名と、選んだ地点の緯度・経度 |
| カレンダーのカード | Google カレンダー（`calendar.google.com`） | 予定を取得するための、入力された非公開 iCal アドレスへのリクエスト |
| リンク切れチェック | リンク先の各サイト | ページが残っているか確かめるための、各リンクの URL へのリクエスト（「チェック」を押したときだけ） |
| リンクのアイコン | Chrome 内蔵のファビコン機能 | リンクの URL（Chrome が端末内で処理します） |

これらの通信はブラウザから各サービスへ直接行われ、各サービスのプライバシーポリシーが適用されます。Open-Meteo の利用に API キーやアカウントは不要です。

## 権限

- **storage・unlimitedStorage**: データとバックアップを端末に保存するため
- **favicon**: リンクの横にサイトのアイコンを表示するため
- **calendar.google.com へのアクセス**（任意。カレンダーを追加するときに確認します）: 予定を取得するため
- **すべてのサイトへのアクセス**（任意。リンク切れチェックのたびに確認し、終わったら返します）: リンクが開けるか確かめるため

## 変更

このポリシーを変更した場合は、日付を更新してこのアドレスで公開します。

## 連絡先

このポリシーに関するお問い合わせ: ryo19960220@gmail.com

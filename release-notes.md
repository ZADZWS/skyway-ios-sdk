# SkyWay iOS SDK release notes

[English](./release-notes.en.md)

## [Version 1.0.6](https://github.com/skyway/skyway-android-sdk/releases/tag/v1.0.6)

### Fixed

- v.1.0.5とは別の要因により、サーバへの接続失敗時に稀にクラッシュする不具合を解消しました。

## [Version 1.0.5](https://github.com/skyway/skyway-ios-sdk/releases/tag/v1.0.5)

### Fixed

- サーバへの接続失敗時に稀にクラッシュする不具合を解消しました。
- getAudioTrack実行時に正常にTrack数が取得出来ない不具合を解消しました。

## [Version 1.0.4](https://github.com/skyway/skyway-ios-sdk/releases/tag/v1.0.4)

### Fixed

- disconnectメソッド後にdestroyメソッドを呼ぶとクラッシュする不具合を解消しました。
- switchCameraメソッドが動作しない不具合を解消しました。

## [Version 1.0.3](https://github.com/skyway/skyway-ios-sdk/releases/tag/v1.0.3)

### Added

- bitcode を有効化しました。
- 1つのstreamを同時に複数のSKWVideo viewにレンダリングできるよう対応しました。

### Fixed

- reconnectメソッドが正しく動作しない不具合を解消しました。
- listAllPeersメソッドのAPIエラー時の不具合を解消しました。
- DataConnectionのメモリリークを解消しました。
- DataConnectionの確立時にクラッシュする事がある不具合を解消しました。
- MeshRoomから退室後、再入室できない事がある不具合を解消しました。
- SFURoomで`SKW_ROOM_EVENT_REMOVE_STREAM` が発火しない不具合を解消しました。

## [Version 1.0.2](https://github.com/skyway/skyway-ios-sdk/releases/tag/v1.0.2)

### Fixed

- IPv6環境下での動作不具合を解消しました。

## [Version 1.0.1](https://github.com/skyway/skyway-ios-sdk/releases/tag/v1.0.1)

### Fixed

- Media/DataConnectionクラスのmetadataオプションが設定されない不具合を解消しました。

## [Version 1.0.0](https://github.com/skyway/skyway-ios-sdk/releases/tag/v1.0.0)

- first release

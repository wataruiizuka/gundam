# プロジェクトのディレクトリ構成

## adapter ディレクトリ

- 各種アダプタのコードが含まれています。

## controller ディレクトリ

- 特定のAPIエンドポイントに対応するコントローラーが含まれ、各コントローラーは異なる機能やエンドポイントに対するリクエストを処理する役割を持ちます。

  - `acst_controller.go`: 
    - ACSTに関連するAPIリクエストを処理するためのコントローラー。
    - 特定のACST情報をAttrIDに変換する機能を持つ2つのメソッドが定義されています。

  - `attr_id_controller.go`: 
    - AttrIDControllerコントローラー。
    - HTTPリクエストを処理してsystemAuIDとattrIDを取得する機能を提供します。
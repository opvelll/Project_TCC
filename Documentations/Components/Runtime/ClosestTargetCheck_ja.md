﻿# ClosestTargetCheck

#### **Namespace**: Unity.TinyCharacterController.Check
---

## 概要:
`ClosestTargetCheck` は、特定の範囲内で最も近いターゲットを検索するコンポーネントです。

## 機能と操作:
- **検索対象のタグの指定**: 検索の対象となるタグを指定します。
- **検索範囲の指定**: 検索する範囲（半径）を指定します。
- **検索対象のレイヤー指定**: 検索対象のレイヤーを指定します。
- **最も近いターゲットの検出**: 指定された範囲内で最も近いコライダーを検出し、ターゲットとして設定します。
- **ターゲット変更時のイベント発火**: ターゲットが変更されたときに、`OnChangeClosestTarget`イベントを発生させます。

## プロパティ
| 名前 | 説明 |
|------------------|------|
| `_tag` | 検索対象となるタグを指定します。 |
| `_radius` | 検索範囲（半径）です。 |
| `_layer` | 検索対象のレイヤーを指定します。 |
| `Target` | 検索結果として見つかったコライダーです。 |
| `PreTarget` | 前フレームで検出されたコライダーです。 |
| `OnChangeClosestTarget` | ターゲットが変更されたときに呼び出されるイベントです。 |

## メソッド
- 公開されているメソッドはありません。

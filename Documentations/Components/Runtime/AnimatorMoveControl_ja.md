﻿# AnimatorMoveControl

#### **Namespace**: Unity.TinyCharacterController.Control
---

## 概要:
`AnimatorMoveControl` は、キャラクターの移動と回転を制御するコンポーネントです。このコンポーネントは、`WorkThisFrame()` が実行されたフレームにのみアクティブになります。アニメーションのルートモーションを利用した動きを実現し、`AnimatorMoveBehaviour` と連携して使用されることを意図しています。

## 機能と操作:
- **移動と回転の優先度設定**: `MovePriority` と `TurnPriority` で移動と回転の優先度を設定できます。
- **地面の正規化利用**: 地面の傾斜に合わせてキャラクターの移動ベクトルを計算します。
- **アニメーションルートモーションの受け取り**: 異なる階層のオブジェクトがアニメーターを所有する場合の動作を管理します。
- **Warpによる位置の更新**: `_isFixedPosition` が有効な場合、Warpを使用してキャラクターの位置を更新します。

## プロパティ
| 名前 | 説明 |
|------------------|------|
| `MovePriority` | 移動に関する優先度を設定します。 |
| `TurnPriority` | 回転に関する優先度を設定します。 |
| `UseGroundNormal` | 地面の傾斜を考慮した移動をするかどうかを設定します。 |

## メソッド
| 名前 | 機能 |
|------------------|------|
|  ``public void`` Rebuild( )  | アニメーターとの接続を再構築します。 |

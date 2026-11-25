<sub>[Enigma_01 ビルドガイド](build-guide.md) ＞ 人によって行う作業</sub>

# 親指キーの配列

> [!NOTE]
> **使う人**：配列を選ぶ人（[2-2](build-guide.md#2-2-ファームウェアの用意)）、組み上げた後に配列を変える人  
> **使う道具**：プラスドライバー（+0）・キープラー（変えるときだけ）  
> **難しさ**：低

親指キー（最下段の中央）は、親指キーのトッププレートを差し替えて、3つの配列から選べます。

## 3つの配列

| 配列 | キースイッチの数 | ファーム（.uf2） |
|:-|-:|:-|
| 1.0u | 42個 | `Enigma_01 layout_a` |
| 1.5u | 41個 | `Enigma_01 layout_b` |
| 2.0u | 41個 | `Enigma_01 layout_c` |

- 1.5u 配列には 1.5u のキーキャップが2個、2.0u 配列には 2.0u のキーキャップが1個要ります
- Choc v1 のキースイッチは、1.0u 配列だけで使えます（[Choc v1 の注意事項](choc_v1.md)）
- 迷ったら 1.0u で始めて、後から変えてもかまいません

<!-- 絵 draw_thumb_a/b/c（自動生成）：親指キーのトッププレート（青みの部分）を真上から -->
**1.0u 配列**

<img src="img/draw_thumb_a.png" alt="1.0u 配列" style="width: 100%; max-width: 600px; height: auto;">

**1.5u 配列**

<img src="img/draw_thumb_b.png" alt="1.5u 配列" style="width: 100%; max-width: 600px; height: auto;">

**2.0u 配列**

<img src="img/draw_thumb_c.png" alt="2.0u 配列" style="width: 100%; max-width: 600px; height: auto;">

## 組み上げた後に変える

1. 親指キーのキーキャップとキースイッチを外す
2. 本体を分解する（[分解の手順](disassembly.md#分解の手順)）
3. メイントッププレートから、親指キーのトッププレートをスライドさせて外し、使う配列の1枚をはめる
4. 組み立て直す（[組み立て直しの手順](disassembly.md#組み立て直しの手順)）
5. 配列に合うファームを書き込む（[ファームウェアの書き込み](firmware.md)）
6. 親指キーのキースイッチとキーキャップを付ける

---

[← ビルドガイド 2-2 に戻る](build-guide.md#2-2-ファームウェアの用意) ｜ [← 6-1 に戻る](build-guide.md#6-1-親指キーの配列を選ぶ) ｜ [目次](build-guide.md#目次)

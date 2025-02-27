---
marp: true
size: 16:9
paginate: true
header: <b>東京医療センター総合内科資料</b> 
style: |

    section::after {
        content: attr(data-marpit-pagination) " / " attr(data-marpit-pagination-total);
        bottom: 10px;
        font-size: 20px;
        color:rgb(160, 160, 160);
        font-family: "Noto Serif Japanese"
    }

    section.title {
        background-color: rgb(17, 85, 204);
        color: rgb(255, 255, 255);
    }
    section.title h1 {
        font-size: 80px;
        color: rgb(255, 255, 255);
    }
    section.title h3 {
        color: rgb(255, 255, 255);
    }
    section.title header {
        font-weight: bold;
        top: 5px;
        left: 10px;
        font-size: 20px;
        color:rgb(255, 255, 255);
    }

    h1 {
        color: rgb(17, 85, 204);
    }
    h2 {
        color: rgb(17, 85, 204);
    }
    header {
        top: 5px;
        left: 10px;
        font-size: 20px;
        color:rgb(160, 160, 160);
    }
    footer {
        left: 10px;
        bottom: 10px;
        font-size: 20px;
        color:rgb(160, 160, 160);
    }
    section.main {
        # background-image: url(../ロゴ画像/サンプルロゴ_small.png);
        background-position: right 10px top 10px;
        background-size: 8%;
        background-repeat: no-repeat;
    }

    section.last_page {
        background-color: rgb(37, 37, 37);
        color: rgb(255, 255, 255);
        font-size: 40px;
    }

---
<!--- _class: title --->

<br>

> # 低血糖についての覚書
>
> ### 低血糖の考え方

<br>
<br>

2025年 2月 24日
**Nozomi Niimi**

---
# Agenda

1. 見出しサンプル
1. 箇条書きリストサンプル
1. 番号付きリストサンプル
1. 引用・ハイパーリンクサンプル
1. テーブルサンプル
1. コード挿入サンプル
1. 数式挿入サンプル
1. 文字装飾サンプル
1. Mermaidサンプル
1. 画像の挿入サンプル

---
# 症例

* 78歳男性
* 繰り返す低血糖で入院

<div style="font-size: 18px; text-align:right"><em>JAMA intern Med</em>. 2023</div>


---

# 低血糖の診断


* 78歳男性
* 繰り返す低血糖で入院


---

# 低血糖の診断 at glance

![height:200](./figure/flowchart.svg)


---

# テーブルサンプル

| 見出し1 | 見出し2 | 見出し3 | 見出し4 |
|------|:-----|:----:|-----:|
| 指定なし | 左寄せ<br>(:----) | 中央寄せ<br>(:---:) | 右寄せ<br>(----:) |
| 1       | 2     | 3       | 4      |
| 10      | 20    | 30      | 40     |
| 100     | 200   | 300     | 400    |



---

# 文字装飾サンプル (2/2)

<center>中央寄せ</center>

<div style="text-align:center">中央寄せ</div>

<div style="text-align:right">右寄せ</div>

<span style="font-size: 40px;">文字のサイズ 40px</span> <span style="font-size: 15px;">文字のサイズ 15px</span>

<span style="font-size: 40px;">文字のサイズ 40px</span> <span style="font-size: 15px;">文字のサイズ 15px</span>

<span style="color: rgb(233, 71, 9);">テキスト色変更</span>

## 研究結果

この研究の結果について述べる。

---
<!---
class: last_page
--->

<center>
<b>
ご清聴ありがとうございました
</b>
</center>

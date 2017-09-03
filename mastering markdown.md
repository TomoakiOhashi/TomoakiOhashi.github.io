Mastering Markdown

**Text**

markdownでとても簡単に言葉を**ボールド**（強調）や*イタリック*にできる

**ナンバリングリスト**


1.One
2.Two
3.Three

**箇条書き**

* アスタリスク
* profit!



- 1
    - 2 
         - 3
         - 小項目はスペース
         - こんな感じ  

**画像を使いたいとき**

![image](C:\Users\智顕\Pictures\スクショ\zippo.png)


# 見出しを付けたいときはシャープ

## シャープの数が多いほど

#### 小さくなる

これが普通の大きさ


> 等号＞でなんか線がでる
> （引用）
> >二重引用
>>おお　ゆうしゃよ　死んでしまうとは
>>なさけない

バッククオート'で囲むことでコードの一部を表示
'var example = true' 

バッククオート×3の後に言語名（javascriptなど)
で対象シンタックスの言語名を記述（よく意味がわからない


GFM (github flavored markdown)

シンタックスハイライト

コードを整える？

'''javascript
function fancyalert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
'''


function fantasy alert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  } 
}


def foo():
  if not bar:
    return True
    
**Table**

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column


Any URL (like http://www.github.com/) 

strikethorough
打消し線

any word wrapped with two tildes (like ~~this~~)will appear crossed out.

Emoji

Github suppots emoji! imp: star: aleien:

# memo

> joey推薦兩本書：單元測試藝術、實例化需求

## 快捷鍵

wox
vimnum

## VIM

ctrl+shift+F12

## round 1

- 快速建立test：在class裡面輸入“,c”（VIM的功能） -> 選testfeature
- 字串逗號左右如何直接換？
- zn？
- zae?
- run test的快速鍵？

## round 2

- 如何切換檔案？回到上一個檔案？zk?
- 如何移動整行代碼？

## round 3

- what is expectedObject plugin?
- alt+enter直接import
- 都還不知道需求（測試）是什麼，怎麼可以去產代碼出來？
- ```expected.ToExpectedObject.ShouldMatch(actual)```是？
- 字串相比，"3" vs "11" , "3"比較大
- String 可以直接用index當作char array 用

## round 4

- 先綠燈，再重構
- 先宣告後復值，怎麼快速鍵

## round 5

- ,c是VIM的嗎？
- new class().var 用法？
- alt + ->

## round 6

- Ctrl + J ?
- Ctrl + W  -> 往外展開選取
- Return Enum是什麼意思？想看範例
- internal method turn to public -> alt+enter 選topublic
- ctrl + alt + enter 排版是用哪一個？

## round 7

- ctrl + d 複製本行到下一行
- 時間壓力之下，明知道有問題卻繼續寫進度，後面要重構就要花更多時間
- 在class name 上 alt + enter 就可以把class移出去另一個檔案

## round 8

- ctrl + t 可以找要去哪裡
- ctrl + - 回去上一個地方

## round 9

- 要從production code產生新的測試案例 可用 ,t

## round 10

- 宣告變數的地方要在用的地方附近，不要離太遠or在最上面

## round 11

- 怎麼跨行選取改動？

## round 12

- 要new CardTypeParser 可以打 CTP就好
- new ... 要宣告成變數，選擇new 到() 選起來，Ctrl + R + V就可以抽出來
- ctrl + L 去掉本行
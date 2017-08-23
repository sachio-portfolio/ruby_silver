#### 問題1. 選択肢の中からRubyの予約語ではないものを2つ選択してください。
- A.super
- B.begin
- C.try
- D.goto
---
#### 問題2. 以下のコードを実行した出力として正しいものを1つ選択してください。
```
def foo (a, *b)
　p a
end
foo(1,2,3,4)
```
- A.nil
- B.1
- C.エラーが発生   *構文エラー、例外などは、一律「エラーが発生」と表記する。
- D.[]
- E.[1]
---
#### 問題3. 以下のコードを実行した時の出力として正しいものを1つ選択してください。
```
puts({"members" => 193, "year" => 2014}.size)
```
- A.15
- B.6 
- C.4
- D.2
---
#### 問題4. 以下のコードを実行した時の出力として正しいものを1つ選択してください。
```
t = Time.now + (60*60*24)
p t
```
- A.実行時の日時が表示される
- B.実行時の日時から24時間後(86400秒後)の日時が表示される
- C.エラーが発生
- D.nil
---
#### 問題5. ローカル変数の名前として正しいものをすべて選択してください。
- A._365
- B.z
- C.7years
- D.break
- E.latitude
---
#### 問題6. 以下のコードを実行した時の出力として正しいものを選択してください。
```
(5..8).each_with_index do |val,i|
puts "#{i} #{val}"
end
```

A. 
```
1 5
2 6
3 7
4 8
```
B.
```
0 5
1 6
2 7
3 8
```
C.
```
5 1
6 2
7 3
8 4
```
D.
```
5 0
6 1
7 2
8 3
```
E.
```
エラーが発生
```
---
#### 問題7. 以下のコードを実行した出力として正しいものを１つ選択してください。
```
p 100.downto(90).select{|x| x%2==0}
```
- A.[100,99,98,97,96,95,94,93,92,91,90] 
- B.[90,92,94,96,98,100]
- C.[100,98,96,94,92,90]
- D.[]
---
#### 問題8. 以下のコードを実行した時の出力に対して__（１）__に入る適切な記述を２つ選択してください。
```
p [1,1,2,3,5,8].__(1)__｛|x| x*2}
[出力]
[2,2,4,6,10,16]
```
- A.compact
- B.collect
- C.map
- D.flatten
- E.join
---
#### 問題9. 以下のコードを実行した出力として正しいものを１つ選択してください。
```
puts "Ruby on Rails".delete("Rails")
```
- A.エラーが発生
- B.Ruby on
- C.Rails
- D.uby on
- E.Ruby
---
#### 問題10. ヒアドキュメントを使用して文字列を作成しようとしたが実行時エラーになった。正しく動かすための修正点を2パターン選択してください。
```
doc = <<EOF
 The quick brown fox 
 jumps over the lazy dog
      EOF
```
- A.1行目は、doc = <<-EOFと書く
- B.最後のEOFは>>EOFと書く
- C.最後のEOFは行頭におく
- D.1行目は、doc = << EOFと書く
---
#### 問題11. 以下の__(1)__に入る適切な記述を１つ選択してください。
```
h = {1=>2, 3=>4}
h.__(1)__
p h   #=>{}

ary = [1, 2]
ary.__(1)__
p ary     #=>[]
```
- A.clear
- B.remove
- C.destroy
- D.empty?
---
#### 問題12. 以下の__(1)__に入る適切な記述を2つ選択してください。
```
a = [1,2,3,4,5]
p __(1)__    #=>[1,2,3]
```
- A.a[0..2]
- B.a[1..2]
- C.a.slice(0,3)
- D.a.slice(0...2)
---
#### 問題13. 以下のコードを実行したときの出力として適切な物を1つ選択してください。
```
str = "RubyAssociation".chomp
```
- A."RubyAssociation\r"	
- B."RubyAssociation"	
- C."RubyAssociation\r\n"	
- D."RubyAssociation\r\n\r\n"
---
#### 問題14. 以下のコードを実行したときの出力として適切な物を1つ選択してください。
```
str = "RubyAssociation\r\n".chop
```
- A."RubyAssociation"	
- B."RubyAssociation\r"	
- C."RubyAssociation\r\n"	
- D."RubyAssociation\r\n\r\n"
---
#### 問題15. 以下のコードにおける4行目io.rewindについて正しい説明を１つ選択してください。
```
File.open("foo.txt","r") do |io|
puts io.gets
 puts io.read
  io.rewind
  p lines = io.readlines
end
```
- A.データを全て読み込んで、その各行を要素としてもつ配列を返す
- B.ファイルポインターをファイルの先頭に移動する
- C.IO から1バイトを読み込み整数として返す
- D.レシーバと同じ IO を参照する新しい IO オブジェクトを返す
---
#### 問題16. 以下のコードを実行した時の出力に対して__（１）__に入る適切な記述を1つ選択してください。
```
mozart = ["Symphony","Piano Concerto", "Violin Concerto","Horn Concerto","Violin Sonata"]
listend = ["Symphony","Violin Concerto","Horn Concerto"]
p mozart__(1)__listend
[出力]
["Piano Conerto","Violin Sonata"]
```
- A.|	
- B.&	
- C.-	
- D.+	
---
#### 問題17. 以下のコードを実行したときの出力として適切な物を1つ選択してください。
```
odd = [1,3,5]
even = [2,4,6]
num = odd + even
p num.sort
```
- A.nil
- B.[]
- C.[1,3,5,2,4,6]
- D.[1,2,3,4,5,6]
---
#### 問題18. 下記の正規表現にマッチする文字列を2つ選択してください。
```
/^[hc].*o$/i
```
- A.Hello
- B.holland
- C.Cello
- D.h35L320
---
#### 問題19. 以下のコードを実行したときの出力として適切な物を1つ選択してください。
```
Greeting = "Hello Ruby"
Greeting = "Hi Ruby"
p Greeting
```
- A.エラーが発生
- B.Greetingは定数のためwarningが発生するが、"Hi Ruby"と出力される
- C.Greetingは定数のため"Hello Ruby"が出力される
- D.Greetingは定数のためwaringが発生して"Hello Ruby"と出力される






























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
---
#### 問題20. 以下のコードを実行したときの出力として適切な物を1つ選択してください。
```
p File.join("ruby", "exam","silver")
```
- A."./ruby"
- B."./ruby/exam/silver"
- C."rubyexamsilver"	
- D."ruby/exam/silver"
---
#### 問題21. 以下のコードを実行したときの出力として適切な物を1つ選択してください。
```
class Surface
  attr_reader :s
  def initialize(x,y)
   @s = x * y
  end
end

class Volume < Surface
  attr_reader :v
  def initialize(x,y,z)
    super(x,y)
   @v = x * y * z
  end
end
 
a = Volume.new(2,5,5)
puts "#{a.v},#{a.s}"
```
- A.50,10
- B.エラーが発生
- C.50,50
- D.10,10
---
#### 問題22. 以下のコードを実行したときの出力として適切な物を1つ選択してください。
```
string = "test code"
string.slice(0,4)
p string
```
- A."test"
- B."test code"
- C.nil
- D.""
---
#### 問題23. 以下のコードを実行したときの出力として適切な物を1つ選択してください。
```
puts "ruby".encoding.name
```
- A.UTF-8
- B.エラーが発生
- C.US-ASCII	
- D.ASCII-8BIT
---
#### 問題24. ハッシュ内にキーが存在するかどうか調べるメソッドの使いかたとして、*誤っている*ものを1つ選択してください。
```
cc = {"nz"=>"New Zealand", "ru"=>"Russia", "ar"=>"Argentina"}
```
- A. p cc.has_key?('nz')
- B. p cc.contain?('nz')
- C. p cc.key?('nz')
- D. p cc.include?('nz')
- E. p cc.member?('nz')
---
#### 問題25. 以下のコードを実行したときの出力として適切な物を1つ選択してください。
```
p "Hello there".class
p String.superclass

class Foo; end
class Bar < Foo; end
p Foo.superclass
p Bar.superclass	
```
A.
```
String
Kernel
Module
Module  
```
B.
```
Object
Module
Object
FooClass
```
C.
```
String
Module
String
FooClass
```
D.
```
String
Object
Object
Foo   
```
E.
```
Object
Object
Module
Kernel
```
---
#### 問題26.	以下のコードを実行して文字列sの単語毎の出現回数を出力させたい。__(1)__,__(2)__に入る最適な組み合わせを１つ選択してください。
```
s = "To be or not to be, that is the question."
hash = Hash.new(0)
s.__(1)__(__(2)__) {|i| hash[i] += 1}
p hash["be"] #=>2
```
- A. (1)match  (2)/\w+/
- B. (1)sub   	(2)/\w+/
- C. (1)scan  	(2)/\w+/
- D. (1)search	(2)/\w+/
---
#### 問題27. 組み込みライブラリ、Integer#chr（encoding)についての説明として正しいものはどれか、2つ選択してください。
- A.引数を指定しなかった場合はエラーが発生する。
- B.指定されたエンコーディングでselfを正しく解釈できない場合はnilが返される。
- C.引数で与えられたencodingにおいて、selfを文字コードと見なし、それに対応する一文字からなる文字列を返す。
- D.指定されたエンコーディングでselfを正しく解釈できない場合はエラーが発生する。
---
#### 問題28. 以下のプログラムがerrorと出力する場合__(1)__,__(2)__に入る最適な組み合わせを１つ選択してください。
```
s = "foo"
___(1)___
  s[4] = ?b
___(2)___
  puts "error"
end
```
- A. ___(1)___は「try」、___(2)___は「catch NameError」である	
- B. ___(1)___は「try」、___(2)___は「catch IndexError」である
- C. ___(1)___は「begin」、___(2)___は「rescue NameError」である
- D. ___(1)___は「begin」、___(2)___は「rescue IndexError」である
---
#### 問題29. 以下のコードを実行したときの出力として適切な物を1つ選択してください。
```
ary = []
ary << 1 && false
true || ary << 2
false && ary << 3
false || ary << 4
p ary
```
- A. [1, 4]	
- B. [1, 2, 3, 4]
- C. [1]
- D. [1, 2, 3]
---
#### 問題30. 以下のコードを実行したときの出力として適切な物を1つ選択してください。
```
p "foo" * 2 **2
```
- A.エラーが発生
- B."foo4"	
- C."foofoofoofoo"	
- D."foofoo"
---
#### 問題31. 以下のコードを実行したときの出力として適切な物を1つ選択してください。
```
foo = [1,2,3]
bar = foo
baz = foo.dup

bar[3] = 4
p foo
p bar
p baz
```
A.
```
[1,2,3] 
[1,2,3,4]          
[1,2,3]
```
B.
```
[1,2,3,4]
[1,2,3,4]
[1,2,3,4]
```
C.
```
[1,2,3,4]
[1,2,3,4]
[1,2,3]
```
D.
```
エラーが発生
```
---
#### 問題32. テキストファイルを読み込んだファイルオブジェクトから一行ずつ読み込み表示したい。目的に一致するIOクラスのメソッドを２つ選択してください。

- A.readlines
- B.read
- C.gets
- D.readline
- E.find
---
#### 問題33. 以下のコードを実行したときの出力として適切な物を1つ選択してください。
```
str = "a,b,c,d" 
p str.split(/,/, 2)
```
= A.["a", "b,c,d"]
- B.["a","b","c","d"]	
- C.["a", "b,c,","d"]	
- D."abcd"
---
#### 問題34. 以下のコードを実行したときの出力として適切な物を1つ選択してください。
```
class Object
  def greeting 
    print "How are you?\n"
   end
end

[1,2].greeting
```
A.エラーが発生	
B.nilが表示される	
C.How are you?	
D.[1,2]
---
#### 問題35. 以下の正規表現とマッチするものを1つ選択してください。
```
/[0-9]{3}-[0-9]{4}/
```
- A.0x000000	
- B.0-93-0-94	
- C.93094	
- D.333-4421
---
#### 問題36. 以下のコードを実行した際の出力として正しいものを選択してください。
```
/[0-9]{3}-[0-9]{4}/
```
- A.[]	
- B.["a", "b", "c", "d", "e", "f"]	
- C.nil	
- D."abcdef"
---
#### 問題37. 以下のコードを実行した時にIOErrorが発生した。理由として考えられるものはどれか１つ選択してください。
```
File.open("foo.txt") do |io|
  io.write(Time.now.strftime("%Y/%m/%d"))
end
```
- A.書き込みモードでファイルが開かれているため	
- B.読み込み可能なfoo.txtが存在しなかったため。	
- C.読み込みモードでファイルが開かれているため	
- D.読み書き両用モードでファイルが開かれているため
---
#### 問題38. 次のメソッドでDirクラスのクラスメソッドではないものをすべて選択してください。(2つ選択)
- A.Dir.rmdir	
- B.Dir.basename	
- C.Dir.pwd	
- D.Dir.extname	
- E.Dir.getwd
---
#### 問題39. 以下のコードを実行した時の正しい出力結果を1つ選択してください。
```
puts "0123456789".delete("0-58-")
```
- A.234679
- B.9	
- C.679	
- D.123458	
- E.12345
---
#### 問題40. 下のコードを実行した時の出力に対して__(1)__,__(2)__に入る最適な組み合わせを１つ選択してください。
```
p "100,200,300,400,500".___(1)___.___(2)___
[出力]
"100\n200\n300\n400\n500"
```
A.(1)split(",") (2)join("\n")
B.(1)to_a(",") (2)join("\n")
C.(1)split(",") (2)concat("\n")
D.(1)concat(",") (2)join("\n")
---
#### 問題41. 以下のコードを出力した時の出力として正しいものを1つ選択してください。
```
a = "foo"
b = "foo"

puts a.eql?(b)
puts a.equal?(b)
```
A.
```
true
true
```
B.
```
true
false
```
C.
```
false
true
```
D.
```
false
false
```
---
#### 問題42. 以下のコードを実行した時の正しい出力結果を1つ選択してください。
```
numbers = [3,89,40,39,29,10,50,59,69]
num = numbers.inject do |i,j|
  i > j ? i : j
end
p num
```
- A.89	
- B.40	
- C.10	
- D.59
---
#### 問題43. 以下のコードを実行した時の正しい出力結果を1つ選択してください。
```
p String.instance_methods.grep(/strip/)
```
- A.[:strip, :lstrip, :rstrip, :strip!, :lstrip!, :rstrip!]	
- B.nil	
- C.[:strip]	
- D.[]	
- E.エラーが発生
---
#### 問題44. Hashの生成でエラーが発生するものを1つ選択してください。
```
A.capital ={:Sweden =>"Stockholm", :Norway=>"Oslo", :Finland=>"Helsinki"}	
B.capital = {Sweden: "Stockholm", Norway: "Oslo", Finland: "Helsinki"}	
C.capital = {"Sweden" = "Stockholm", "Norway" = "Oslo", "Finland" = "Helsinki"}
D.capital = Hash[:Sweden,  "Stockholm", :Norway ,"Oslo", :Finland, "Helsinki"]
```
---
#### 問題45. 以下の出力になる時の___(1)___に入るものとして適切なものを1つ選択してください。
```
___(1)___ 'uri'
uri = URI::HTTP.build({host:'www.ruby.or.jp', path:'/ja/certification/examination/'})
puts uri

[出力]
http://www.ruby.or.jp/ja/certification/examination/
```
- A.require	
- B.include	
- C.extend	
- D.import
---
#### 問題46. 以下の出力になる時の___(1)___に入るものとして適切なものを1つ選択してください。
```
class Foo                                                                   
  ___(1)___= 0
  def self.count
    ___(1)___ += 1
  end
end
  
class Bar < Foo
end
 
puts Foo.count
puts Bar.count

[出力]
1
2
```
- A.num
- B.@num	
- C.@@num





































	














































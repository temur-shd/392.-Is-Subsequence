# 392.-Is-Subsequence
392. Alt dizi


Bu bir dinamik programlama sorusudur ve LCS ile çözülür (LCS Algoritması, İki küme arasındaki ortak elamanların (sıralı olmak şartıyla) en uzun ortaklığını arar.)
Örneğin: <br>
x = abcdef <br>
y = acbcf <br>
LCS = abcf

Soruda bize s ve t stringleri veriliyor. Eğer s, t'nin alt kümesi ise doğru, değilse yannlış dönmesi isteniyor.
Bunun için i,j ve while döngüsü kullanarak karmaşıklığı olabildiğince azaltmaya çalışıyoruz. 

Input: s = "abc", t = "ahbgdc"
Output: true

Input: s = "axc", t = "ahbgdc"
Output: false

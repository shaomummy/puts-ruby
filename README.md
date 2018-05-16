# Ruby on Railsの初識

先簡單介紹下自己，_資管系_ 畢業，在學時接觸過 _VB_、_C_、_PHP_、_Processing_、_ActionScript3_...#(*&$%
許多語言，在這其中，只有對程式之母的C語言還有PHP很感興趣。在畢業前一年聽到了一堂講座 [Ruby 入門](https://tonytonyjan.net/slides/2014-08-ntunhs/) ，這是第一次接觸到Ruby，但說實話已經忘得差不多了😂

工作三年來，只要是不會的功能甚至語言，就是往Google上找，可以說是位稱職的 _CMD+CV工程師_ 。在年初很徬徨的回顧幾年來的檔案，想把以前沒打好的基礎好好紮好。

在PreA的最後，Scaffold的快速生成讓我記憶猶新，因為真的好快，Rails把很多東西都已經寫好了，自己在PHP的開發上都是自己寫Api、自己做模組，沒有接觸過Laraval

而實際的開始上課後，很不適應Ruby的自由，幾年來都活在PHP跟Javascript裡，() {} $$$$$ var let 各種省略，但是在編寫上面很直覺

像是奇偶數在 **PHP裡**
>#### $temp = array(); 
>#### for($i=1;$i<=100;$i++) { 
>#### &nbsp;&nbsp;if($i%2) { 
>#### &nbsp;&nbsp;&nbsp;&nbsp;array_push($temp, $i); 
>#### &nbsp;&nbsp;} 
>#### } 
>#### print_r($temp);

而在 **Ruby**
>#### p [*1..100].select{ |x| x.odd? }

這精簡的一行打發了，寫了七行的PHP。
學習當中的轉換很痛苦，但是在實際練習寫Ruby的時候，真的很開心，因為少了宣告、少了$$$，滿滿的$符號，但是薪水沒有一樣有錢啊🤮

不說了，我先繼續練習了

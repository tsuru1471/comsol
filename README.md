# 5/23

・接触解析(非線形)と振動解析(線形)は同居できない

→振動を正弦波としてとらえられないから

https://blog.altairjp.co.jp/yomoyama023/


・周波数応答解析

→ 線形解析ノミっぽい?

https://www.cybernet.co.jp/ansys/product/analyse/structure/

・過渡応答解析

非線形解析もできるらしい。特に直接法によって(modealは線形?)

http://jikosoft.com/cae/vibration_ana05.html


solver

![image](https://user-images.githubusercontent.com/92427575/169868424-c60a671a-5d24-416a-b95f-01174471b272.png)



・接触問題

![image](https://user-images.githubusercontent.com/92427575/169816676-2f0b3058-23a5-40c0-9c83-eb6dd84fdaaf.png)

定常解析or過渡応答解析 p172より


➀・接触解析と過渡応答解析

p182にて、接触解析は厳密には静解析で行い、条件次第で過渡応答解析もできるとあるが、粘弾性材料などの応答が時間に依存する材料の接触解析は自由に行えないのか？

→　おそらく準静的つまり慣性項無視すれば接触問題の過渡応答解析溶ける！！！



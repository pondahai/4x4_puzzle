# 4x4_puzzle  
![image](https://github.com/user-attachments/assets/dede0d2a-46e5-4ce1-84c8-bbf166b18cf8)

這次要練習4x4數字拼圖  
本來以為可以讓qwen2.5-coder一次做到好  
於是我一開始就跟AI說要做數字拼圖  
他的外觀是一次到位  
但是運作邏輯卻是亂七八糟  
沒想到改來改去都無法解決AI搞不清楚上下左右的移動問題  
總是無法讓空格正確移動  
AI無法換位思考  
當你跟他說數字拼圖的遊戲邏輯  
他總是認知錯誤  
最後看著那個灰色空格想到  
我重頭來過  
先跟AI說只要做一個空白的4x4  
然後裡面放一個灰色方塊可以讓我用方向鍵移動  
這個就一次OK  
然後我再跟AI說把1到15數字隨機放進去白色格子  
這次竟然也一次OK  
而且是猜對我的意圖  
直接完成數字拼圖  
哇咧~~~  
#反向思考  
#就直接跟AI說表象  
#家樂福的C  

可是我剛剛用LMSTUDIO跑qwen2.5-coder-7B 卻又是一次到位:  
"生成HTML遊戲: 4x4數字拼圖 單一檔案"  
我需要比對一下  
模型來源不一樣(待確認)前面來自qwen 後面來自lmstudio  
前面是用llama.cpp在jetson的編譯 後面是lmstudio(底層也是llama.cpp)  
還有可能執行參數也不同  

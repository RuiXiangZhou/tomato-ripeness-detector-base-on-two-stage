
tomato ripeness detector base on two stage
# 番茄成熟度辨識模型_分級2類
## tomato-ripeness-detector-base-on-two-stage
此模型能夠將照片中的番茄自動辨識出來  
並且分成兩種，成熟與未熟

電腦需求: 需配有Nvidia 顯卡，並已安裝cuda、anaconda  
輸入: 照片  
輸出: 框選完之照片  
## 使用步驟:  
0. 使用anaconda建立一個虛擬環境  
1. 根據安裝的cuda版本下載pytorch，網址:https://pytorch.org/get-started/locally/  
2. 於連結下載檔案並解壓縮獲得一資料夾  
3. 將anaconda終端所在位置移動至檔案資料夾  
4. 執行pip install -r requirement.txt  
5. 將欲辨識的照片放在"sourse"資料夾中  
6. 執行python chicken_test.py  
7. 辨識結果的照片將存在"result"資料夾中  
  
## 模型可視化展示如下圖:  
![圖片4](https://hackmd.io/_uploads/S1cXjgziC.jpg)

## Acknowledgements
https://github.com/WongKinYiu/yolov7/

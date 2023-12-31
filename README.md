final_project

data visual
![image](https://github.com/Carly-Yang/2022_ai_final_project_auto/assets/110595051/9d649418-40a3-41ea-94f6-bde81490f835)

資料前處理(data preprocessing)
檢查資料，擬定方式與簡易的除錯。

1.PassengerId *(設定id)

2.Cabin       *(需要轉換)

3.Name        *(不重要的資料)

4.Transported *(設定label)


資料處理(data processing)
將data轉換成可以使用的樣式。

轉換Cabin並使用One-Hot Encoding，
將資料使用Normalize以減輕壓力。
![image](https://github.com/Carly-Yang/2022_ai_final_project_auto/assets/110595051/d86735c3-1727-4754-81d3-5049917ba2c9)


資料探勘(data mining)
套入設定模型的寬度與尋找較佳的參數。

首先利用AutoKeras Classifier快速找出較適合的範圍超參數，
設定的層數使用relu做為激勵函數，並且使用dropout以避免過擬合。
![image](https://github.com/Carly-Yang/2022_ai_final_project_auto/assets/110595051/1b46912f-d180-440e-b4f9-2dd510653911)


解釋與評估(evaluation)
![image](https://github.com/Carly-Yang/2022_ai_final_project_auto/assets/110595051/0b26460b-738d-4260-bccd-0b5824d509c2)
![image](https://github.com/Carly-Yang/2022_ai_final_project_auto/assets/110595051/6ff6c782-74aa-4776-8384-a31fb2595f3a)


當日於kaggle中的成績
![image](https://github.com/Carly-Yang/2022_ai_final_project_auto/assets/110595051/365a7b37-8ef6-41f5-88b9-1641dda284b2)

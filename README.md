# DSAI_HW2
問題討論:

training size以及training epoch對於準確度的提升是相輔相成的，當training size夠大但是epoch不夠大，重複學習的次數不夠，準確度會無法提升;
當training epoch夠大但size不夠大，則對於訓練的準確度會提升非常快且高，但遇到測試資料正確率完全無法反應在上面，應該是為overfitting(嘗試epoch=1000,size=200
,準確度大約400次epoch時就百分之一百,但遇到測試資料20筆,完全沒有任何一題答對)

對於乘法的使用

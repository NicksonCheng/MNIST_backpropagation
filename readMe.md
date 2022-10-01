# Layer implementation
sigmoid numpy overflow
# Forward / Backward
# Accuracy loss plot
# Difficaulty
## Sigmoid function
利用sigmoid function去實作back propagation weight會一直不斷增加，最後在計算過程中會overflow導致輸出nan，推測可能是vanishing gradient，也有可能是我code寫錯，最後換成ReLu function則可以正常運行
## 
# mermaid
2022年新春大禮包， Github的**Markdown**開始支援**Mermaid**語法，以下就根據官方提供的語法來測試一下。   
參考資料來源：https://mermaid-js.github.io/mermaid/#/  
使用時只需在Mermaid指令前面加上一行「\`\`\`mermaid」表示程式開始，最後再加上一行「\`\`\`」來結束。  
這裡的「\`」符號指的是鍵盤左上角，ESC鍵下方那個按鍵。

## 流程圖(Flowchat)  
```
graph TD;
    程序A-->程序B;
    程序A-->程序C;
    程序B-->程序D;
    程序C-->程序D;
```  
```mermaid
graph TD;
    程序A-->程序B;
    程序A-->程序C;
    程序B-->程序D;
    程序C-->程序D;
```

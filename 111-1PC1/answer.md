# 第1次練習-練習-PC1
>
>學號：109111101
><br />
>姓名：邱韋翔
><br />
>作業撰寫時間：10 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2022/09/13
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x]說明內容
- [x]個人認為完成作業須具備觀念

## 說明程式與內容

一開始我的想法是不用動到Test.aspx檔，直接修改Test.aspx.cs檔即可，然後根據
readme.md檔裡面的提示在Page_Load輸入程式碼，輸出文字我使用Response.Write()
用來輸出文字，下段程式碼則為使用後結果:

```csharp
        protected void Page_Load(object sender, EventArgs e)
        {
            Response.Write("Hello App");
        }
```

## 個人認為完成作業須具備觀念

首先須先了解IDE的環境，先做清除方案的部分避免之後執行上出錯誤，
再來需知道Web 表單新增的位置，後續則是輸出文字的部分，根據readme.md檔裡面的提示
在Page_Load輸入可以讓文字輸出的程式碼`Response.Write()`以此來完成作業需求


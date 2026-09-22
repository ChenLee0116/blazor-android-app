# Blazor Android App

這是一個使用 .NET MAUI Blazor Hybrid 建立的 Android Hello World 專案。

## 執行 Android

先安裝 .NET MAUI workload 與 Android SDK，接著在專案目錄執行：

```bash
dotnet workload install maui-android
dotnet build BlazorAndroidApp/BlazorAndroidApp.csproj -f net10.0-android
dotnet build BlazorAndroidApp/BlazorAndroidApp.csproj -t:Run -f net10.0-android
```

首頁位於 `BlazorAndroidApp/Pages/Index.razor`。
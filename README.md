# BlazorRoleBasedAuthExample 
Blazor Role-Based Authorization Example
以 Blazor 搭配 Identity 實作 Role-Based Authorization 範例

Development environment 開發環境
- Visual Studio 2019
- Blazor 5
- Local SQL Server

Repositories 有三個目錄：
- **BlazorSerRoleAuth** - Blazor Server App 專案類型, 按教學影片 [Basic Authentication and Authorization in Blazor Server: Carl Franklin's Blazor Train ep 26](
https://youtu.be/mbNFscKBsy8) 實作
- **BlazorWasmRoleAuth** - Blazor WebAssembly App 專案類型, 參考微軟官方文件實作
[Secure an ASP.NET Core Blazor WebAssembly hosted app with Identity Server](https://docs.microsoft.com/en-us/aspnet/core/blazor/security/webassembly/hosted-with-identity-server?view=aspnetcore-3.1&tabs=visual-studio)
- **IdentityManagerUI** - Clone from [IdentityManagerUI](https://github.com/mguinness/IdentityManagerUI) 僅用來建立 Role 測試授權，沒有修改。

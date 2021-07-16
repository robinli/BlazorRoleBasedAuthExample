# BlazorRoleBasedAuthExample 
Blazor Role-Based Authorization Example
以 Blazor 搭配 Identity 實作 Role-Based Authorization

開發環境
- Visual Studio 2019
- Blazor 5
- Local SQL Server

專案下有三個目錄：
- BlazorSerRoleAuth : Blazor Server Application
- BlazorWasmRoleAuth : Blazor WebAssembly
- IdentityManagerUI : Identity Manager, Clone from [IdentityManagerUI](https://github.com/mguinness/IdentityManagerUI)

第一個 Balzor Server 專案是完全按 [Basic Authentication and Authorization in Blazor Server: Carl Franklin's Blazor Train ep 26](
https://youtu.be/mbNFscKBsy8) 教學實作

第二個 Blazor WebAssembly 專案，參考微軟官方文件
[Secure an ASP.NET Core Blazor WebAssembly hosted app with Identity Server](https://docs.microsoft.com/en-us/aspnet/core/blazor/security/webassembly/hosted-with-identity-server?view=aspnetcore-3.1&tabs=visual-studio)

第三個 IdentityManagerUI 專案是用來建立 Role 測試授權，沒右修改。

### Star Gemini

[![Hack Together: Microsoft Graph and .NET](https://img.shields.io/badge/Microsoft%20-Hack--Together-orange?style=for-the-badge&logo=microsoft)](https://github.com/microsoft/hack-together)

- Use Microsoft Graph to keep your workspace in one place
- Check latest emails, to-do lists, calendar to stay productive

### Pre-requisite
- [Microsoft 365 developer tenant](https://developer.microsoft.com/office/dev-program?ocid=MSlearn&WT.mc_id=m365-30352-cxa "Microsoft 365 developer tenant")
- [Microsoft 365 Developer Program](https://aka.ms/m365developers) account
- [.NET 5.0.405 SDK](https://dot.net/?WT.mc_id=m365-30352-cxa ".NET 5.0.405 SDK") installed

### Installation guide

1. After getting an account in the Developer Program, [register the app in the portal](https://learn.microsoft.com/en-us/graph/tutorials/dotnet?tabs=aad&tutorial-step=1 "register the app in the portal")
2. Clone this repository
3. Add credentials to the repository
```
dotnet user-secrets init
dotnet user-secrets set "AzureAD:ClientId" "Your_Azure_AD_Client_Id"
dotnet user-secrets set "AzureAD:ClientSecret" "Your_Azure_AD_Client_Secret"
```
4. Run the application using MS Visual Studio using `F5` key or ```dotnet run```

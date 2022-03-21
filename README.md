# NetDesktopWinFormsWAM

This is an advanced developer app which allows app developers to test their integration with MSAL for public clients (desktop apps). In particular, it focuses on WAM integration. 
This is not an official Microsoft sample!

## Important security notice

This tool saves access tokens in plaintext for easier debugging. This is a big security hole. You must encrypt your token cache at rest - see https://docs.microsoft.com/en-us/azure/active-directory/develop/msal-net-token-cache-serialization?tabs=desktop

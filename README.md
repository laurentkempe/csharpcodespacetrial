# C# Github Codespaces trial

This is a repository to make some expirements with Github Codespaces and C#.

It is working perfectly with 

    dotnet new webapp
    dotnet new blazorwasm 

Here is the Github action build status
![.NET Core](https://github.com/laurentkempe/csharpcodespacetrial/workflows/.NET%20Core/badge.svg)

You can also launch the applications and see the results in your own browser hosted on my [Blog](http://laurentkempe.com/csharpcodespacetrial/).

The Blazor Web Assembly single page application is built using [Github Actions](https://github.com/laurentkempe/csharpcodespacetrial/blob/master/.github/workflows/build-deploy.yml) and deployed to Github pages.


Also works with Azure Functions, you need first to install from the terminal

    npm i -g azure-functions-core-tools@3 --unsafe-perm true

Then you can create a new Azure Function from the Azure Functions VS Code extension.
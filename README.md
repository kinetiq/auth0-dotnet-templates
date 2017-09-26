# Auth0 Templates for .NET Core

The Auth0 Templates for .NET Core allows you to quickly bootstrap a .NET Core Web application that works with Auth0. 

## Requirements

* An Auth0 account 
* .NET Core 2.0 SDK

## Installing the templates

You can install the templates by running the following command

```bash
dotnet -i Auth0.Templates
```

Once installed your will have to new templates available to create either and MVC or Web Api application.

## Using the templates

### Auth0 MVC Application

To create a new MVC application, you can run the following command

```
dotnet new auth0mvc [options]
```

This will create a new MVC application in the current folder. The following template-speficic options are available:


Option | Description | 
---------|----------
`-sa` or `--signature-algorithm` | The algorithm with which tokens returned from Auth0 are being signed. Can be either `RS256` or `HS256`. The default value is `RS256`
`-st` or `--save-tokens` | If specified, saves the tokens returned from Auth0. Can be either `true` or `false`. The default is `false`
`-pp` or `--include-profile-page` | If specified, adds a page which allows you to view the user's profile. Can be either `true` or `false`. The default is `true`
`-cp` or `--include-claims-page` | If specified, adds a page which allows you to view the user's claims. Can be either `true` or `false`. The default is `false`

### Auth0 Web API Application

To create a new Web API application, you can run the following command

```
dotnet new auth0api [options]
```

This will create a new MVC application in the current folder. The following template-specific options are available:


Option | Description | 
---------|----------
`-sa` or `--signature-algorithm` | The algorithm with which tokens returned from Auth0 are being signed. Can be either `RS256` or `HS256`. The default value is `RS256`
`-st` or `--save-tokens` | If specified, saves the tokens returned from Auth0. Can be either `true` or `false`. The default is `false`


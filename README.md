#&nbsp;![alt tag](http://dotnetify.net/content/images/greendot.png) dotNetify 
![alt build](https://ci.appveyor.com/api/projects/status/github/dsuryd/dotnetify?svg=true)

DotNetify is a free, open source project that lets you create amazing real-time web and mobile apps using HTML5 and C# on cross-platform .NET Core backend. 

##Features

* Simple and lightweight - no JS client-side framework, no REST API controllers.
* Integrate SignalR and KnockoutJS to support .NET back-end MVVM architecture.
* Built-in real-time across WebSockets, perfect for IoT consumer apps.
* Full support for single-page apps, including client-side and server-side deep routing.
* Run on [ASP.NET Core](http://asp.net/core), ASP.NET 4.5 and [Nancy](https://github.com/dsuryd/dotNetify-Nancy-demo).
* Modern tooling: Visual Studio 2015,  [Typescript](https://www.typescriptlang.org/), [NPM](https://www.npmjs.com/), [WebPack](https://webpack.github.io/).

##Documentation

Documentation and live demo can be found at [http://dotnetify.net](http://dotnetify.net).

##Code Examples

Want a super simple example to try out?  See the [Live Chart Example](https://github.com/dsuryd/dotNetify-example-livechart).    

For close-to-real-world example, see the [Web/Mobile App Template](https://github.com/dsuryd/dotNetify-app-template).

##NuGet

ASP.NET 4.5:  
*PM> Install-Package DotNetify*

ASP.NET Core:  

On .NET Core class library projects:  
*PM> Install-Package DotNetify.Core -pre* 

On ASP.NET Core web projects:  
*PM> Install-Package DotNetify.SignalR -pre*  
*npm install dotnetify* (on web application project)

See the [Configuring Your Project](http://dotnetify.net/index/Installing) section.

##License
Licensed under the Apache License, Version 2.0.

##Contributing
All contribution is welcome; reach out to find out how you can help.  If you like the idea behind this project, please let others know about it! 

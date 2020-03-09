# cheatsheet

HTML
---
HTML Validation - https://validator.w3.org/

ASP.Net CORE
---
Implementation of User Login And Authentication - https://docs.microsoft.com/en-us/aspnet/core/security/authorization/secure-data?view=aspnetcore-3.0   
Configure SQLite - https://docs.microsoft.com/en-us/ef/core/get-started/?tabs=netcore-cli    
Get User when using .net core Identity 3:
```
var id = User.FindFirst(ClaimTypes.NameIdentifier).Value;

var user = await _userManager.FindByIdAsync(id);
```    
Implementing Blazor in a ASP.NET Core MVC application - https://chrissainty.com/using-blazor-components-in-an-existing-mvc-application/   
Scaffolding Identity pages in a spa app - 
```


    Create project using template : dotnet new react --auth Individual and build the project .

    If you have not previously installed the ASP.NET Core scaffolder, install it in terminal in vs code :

    dotnet tool install -g dotnet-aspnet-codegenerator

    Add required NuGet package references to the project :

    dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design

    dotnet add package Microsoft.EntityFrameworkCore.SqlServer

    You can list the files that can be scaffolded with dotnet aspnet-codegenerator identity --listFiles

    Run the Identity scaffolder with the options you want , use --files to scaffold specific files ,use the correct fully qualified name for your DB context:

    dotnet aspnet-codegenerator identity -dc ProjectName.Data.ApplicationDbContext --files "Account.Register;Account.Login"

    If you run the Identity scaffolder without specifying the --files flag or the --useDefaultUI flag, all the available Identity UI pages will be created in your project.

Now if you want to modify the login UI , you can modify relevant page in your project --> Areas-->Identity -->Pages-->Account -->Login.cshtml page .
```
JavaScript
---
Redux visual guide - https://levelup.gitconnected.com/an-unforgettable-way-to-learn-redux-f36afd38c966    
React Native Local Dev Environment - https://expo.io/    

CSS
---
Flexbox & CSS Grid - https://css-tricks.com/       
Resetting default styling - https://meyerweb.com/eric/tools/css/reset/

HTTP
---
Creating new Axios instance with headers - axios.create({baseURL: "", headers:{})

Datbases
---
SQL cheat sheet - https://gist.github.com/hofmannsven/9164408

Git
---
Git Cheat Sheet - https://www.git-tower.com/blog/git-cheat-sheet.   
When You've really messed up the repo - http://ohshitgit.com/    
Create .gitignores - https://www.gitignore.io/

Markdown
---
Markdown Cheat Sheet - http://packetlife.net/media/library/16/Markdown.pdf

Jekyll
---
Deploying Jekyll to gh-pages - https://learn.cloudcannon.com/jekyll-cheat-sheet/

Colours
---
Colour finder - https://picular.co/
Color Scheme picker - https://coolors.co/

Misc Usefull Tools
---
Quick syntax finding for many languages and tooling - https://devdocs.io/

Regex
---
Regex cheat sheet - https://gist.github.com/nerdsrescueme/1237767       
Testing and checking Regex - https://regexr.com/

Wireframing
---    
Online wireframing tool - https://mockflow.com/app/#Wireframe

Study    
---    
Free Programming books - https://ebookfoundation.github.io/free-programming-books/free-programming-books.html
Little ASP .NET Core book - https://nbarbettini.gitbooks.io/little-asp-net-core-book/content/   

Algorithms   
---
Dijkstra’s Algorithm (Most Efficent route on graph) - https://medium.com/@adriennetjohnson/a-walkthrough-of-dijkstras-algorithm-in-javascript-e94b74192026

NHibernate
---
Configuring NHibernate with ASP.NET core 2/3 - https://gunnarpeipman.com/aspnet-core-nhibernate/    

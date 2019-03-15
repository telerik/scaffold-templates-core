# Template logic

The template logic for ASP.NET 2.2+ is as follows.

1. Scaffolding checks for the Bootstrap version number under the path `wwwroot\lib\bootstrap\dist\js\bootstrap.js`.
2. The process attempts to discern the existing bootstrap version and provide appropriate content. If no bootstrap version is detected, the generated default content is for bootstrap 4.
3. The bootstrap 4 content goes into the directory: Templates\ViewGenerator\
4. The bootstrap 3 content goes into the directory: Templates\ViewGenerator_Versioned\Bootstrap3\

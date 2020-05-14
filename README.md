# SiteViewCounterMiddleware
this is a middleware in asp.net core , for save Ip users come in site and counting all


you can use this middleware in startup class and in Configure method like this:

app.UseMiddleware<SiteViewMiddleware>();

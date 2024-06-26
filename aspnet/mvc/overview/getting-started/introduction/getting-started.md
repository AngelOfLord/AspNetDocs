---
uid: mvc/overview/getting-started/introduction/getting-started
title: "Getting Started with ASP.NET MVC 5 | Microsoft Docs"
author: Rick-Anderson
description: "This tutorial teaches you the basics of building an ASP.NET MVC 5 web app using Visual Studio 2017"
ms.author: riande
ms.date: 10/04/2018
ms.assetid: f3d8adbe-55e7-4fd4-84a8-7155bc45c676
msc.legacyurl: /mvc/overview/getting-started/introduction/getting-started
msc.type: authoredcontent
---
# Getting started with ASP.NET MVC 5

by [Rick Anderson](https://twitter.com/RickAndMSFT)

[!INCLUDE [consider RP](../../../../includes/razor.md)]

This tutorial teaches you the basics of building an ASP.NET MVC 5 web app using [Visual Studio 2017](https://visualstudio.microsoft.com/downloads/?utm_medium=microsoft&utm_source=learn.microsoft.com&utm_campaign=button+cta&utm_content=download+vs2017). The final source code for the tutorial is located on [GitHub](https://github.com/dotnet/AspNetDocs/tree/main/aspnet/mvc/overview/getting-started/introduction/sample/MvcMovie/MvcMovie).

This tutorial was written by [Scott Guthrie](https://weblogs.asp.net/scottgu/) (twitter[@scottgu](https://twitter.com/scottgu) ), [Scott Hanselman](http://www.hanselman.com/blog/) (twitter: [@shanselman](https://twitter.com/shanselman) ), and [Rick Anderson](https://twitter.com/RickAndMSFT) ( [@RickAndMSFT](https://twitter.com/#!/RickAndMSFT) )

You need an Azure account to deploy this app to Azure:

- You can [open an Azure account for free](https://azure.microsoft.com/pricing/free-trial/?WT.mc_id=A443DD604) - You get credits you can use to try out paid Azure services, and even after they're used up you can keep the account and use free Azure services.
- You can [activate MSDN subscriber benefits](https://azure.microsoft.com/pricing/member-offers/msdn-benefits-details/?WT.mc_id=A443DD604) - Your MSDN subscription gives you credits every month that you can use for paid Azure services.

## Get started

Start by [installing Visual Studio 2017](https://visualstudio.microsoft.com/downloads/?utm_medium=microsoft&utm_source=learn.microsoft.com&utm_campaign=button+cta&utm_content=download+vs2017). Then, open Visual Studio.

Visual Studio is an IDE, or integrated development environment. Just like you use Microsoft Word to write documents, you'll use an IDE to create applications. In Visual Studio, there's a list along the bottom showing various options available to you. There's also a menu that provides another way to perform tasks in the IDE. For example, instead of selecting **New Project** on the **Start page**, you can use the menu bar and select **File** > **New Project**.

![Screenshot that shows the Visual Studio Start Page. Create new project is circled in red.](getting-started/_static/image1.png)

## Create your first app

On the **Start page**, select **New Project**. In the **New project** dialog box, select the **Visual C#** category on the left, then **Web**, and then select the **ASP.NET Web Application (.NET Framework)** project template. Name your project "MvcMovie" and then choose **OK**.

![Screenshot that shows the New Project window. Web and A S P dot NET Web Application dot NET Framework are selected.](getting-started/_static/image2.png)

In the **New ASP.NET Web Application** dialog, choose **MVC** and then choose **OK**.

![Screenshot that shows the New A S P dot NET Web Application dialog. M V C is selected.](getting-started/_static/image3.png)

Visual Studio used a default template for the ASP.NET MVC project you just created, so you have a working application right now without doing anything! This is a simple "Hello World!" project, and it's a good place to start your application.

![Screenshot that shows the M V C Movie window open to the Overview page.](getting-started/_static/image4.png)

Press **F5** to start debugging. When you press **F5**, Visual Studio starts [IIS Express](/iis/extensions/introduction-to-iis-express/iis-express-overview) and runs your web app. Visual Studio then launches a browser and opens the application's home page. Notice that the address bar of the browser says `localhost:port#` and not something like `example.com`. That's because `localhost` always points to your own local computer, which in this case is running the application you just built. When Visual Studio runs a web project, a random port is used for the web server. In the image below, the port number is 1234. When you run the application, you'll see a different port number.

![Screenshot that shows the A S P dot NET Home Page.](getting-started/_static/image5.png)

Right out of the box this default template gives you `Home`, `Contact`, and `About` pages. The image below doesn't show the **Home**, **About**, and **Contact** links. Depending on the size of your browser window, you might need to click the navigation icon to see these links.

![Screenshot that shows the A S P dot NET Home Page in a smaller display window. The three lines indicating the navigation menu are circled in red.](getting-started/_static/image6.png)

The application also provides support to register and log in. The next step is to change how this application works and learn a little bit about ASP.NET MVC. Close the ASP.NET MVC application and let's change some code.

For a list of current tutorials, see [MVC recommended articles](../mvc-learning-sequence.md).

> [!div class="step-by-step"]
> [Next](adding-a-controller.md)

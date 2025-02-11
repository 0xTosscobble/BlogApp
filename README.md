# BlogApp

BlogApp is a Blazor-based web application that allows users to create, view, and search blog posts. This application is built using .NET 8 and C# 12.0.

## Features

- Create new blog posts
- View a list of all blog posts
- Search for blog posts by title or content
- User authentication and authorization

## Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later with the ASP.NET and web development workload

## Getting Started

Follow these steps to get the application running on your local machine:

1. **Clone the repository:**

    git close https://github.com/0xTosscobble/BlogApp.git
    cd BlogApp


2. **Restore the dependencies:**

    Open the solution in Visual Studio and restore the NuGet packages.

    Alternatively, you can use the .NET CLI: **dotnet restore**

    
3. **Update the database:**

    Ensure that you have a local SQL Server instance running. Update the connection string in `appsettings.json` if necessary.

    Apply the migrations to create the database schema: ***dotnet ef database update**


4. **Run the application:**

    You can run the application from Visual Studio by pressing `F5` or using the .NET CLI: **dotnet run**


5. **Access the application:**

    Open your web browser and navigate to `https://localhost:5001` (or the port specified in your launch settings).


## Usage

### Creating a Blog Post

1. Navigate to the "Post" section from the navigation bar.
2. Click on "Create New Post".
3. Fill in the title and content of the blog post.
4. Click "Save" to create the post.

### Viewing Blog Posts

1. Navigate to the "Post" section from the navigation bar.
2. You will see a list of all blog posts.

### Searching Blog Posts

1. Use the search bar in the navigation bar.
2. Enter the text you want to search for and press "Search".
3. The results will be displayed on the same page.

    
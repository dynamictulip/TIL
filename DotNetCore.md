.NET Core
---

[Nuget](#nuget)
[Project file](#project_file)

###Nuget
In .NET core all nuget packages are only stored in the global package repository - this is located in `C:\Users\asara\.nuget\packages`.
Packages/references are controlled through the `project.json` file

###Project file
`.xproj` files are pretty minimal and contain information such as the namespace and target framework version. Files contained within a project are not referenced in the xproj file.

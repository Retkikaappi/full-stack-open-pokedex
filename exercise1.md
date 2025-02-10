I chose C# as it is fairly similar to JS/TS in many aspects.

C# / .NET community does not seem as concerned about code formatting, so the information is more sparce than when compared to the JS ecosystem. Good options with VSCode seem to be dotnet-format specifically for .NET and Roslyn Analyzers for either.

For testing Microsoft recommends xUnit, NUnit, MSTest and Microsoft Testing Platform. For building, sensible options seem Fake, Cake, Nuke and the default option MSBuild.
Setting up CI is again, is just like JS/TS. The most popular option in addition to Jenkins and GitHub Actions is Azure DevOps, but the common sentiment seems to be that even Microsoft is moving towards promoting GitHub Actions as the go-to solution.

I do not think the argument changes for C# when it comes to self-hosting versus cloud-based environment when compared to JS/TS. You will run into the same issues, self-hosting is more expensive to set-up, more work to maintain and difficult to get up and running. A cloud solution is quick to set up, but more restrictive. After reading what people think of GitHub Actions, it seems to be the logical solution for any small to mid-size project. Bigger projects might choose Jenkins or Azure DevOps, if the project is already ingrained in using Azure services, that might be the logical solution.

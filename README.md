# NuKeeperIssue878
Test repo to demonstrate NuKeeper issue 878

nukeeper repo -v D https://github.com/nickdalt/NuKeeperIssue878.git xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx           

Matched uri 'https://api.github.com/' to collaboration platform 'GitHub'                                                FindPushFork. Fork Mode is PreferFork
2019-09-26T19:44:19Z: Started
Read github user 'nickdalt'
Looking for user fork for nickdalt/NuKeeperIssue878
User fork found at git://github.com/nickdalt/NuKeeperIssue878.git for nickdalt
User 'nickdalt' fork of 'NuKeeperIssue878' exists but is unsuitable. Matching: False. Pushable: True
Looking for user fork for nickdalt/NuKeeperIssue878
User fork found at git://github.com/nickdalt/NuKeeperIssue878.git for nickdalt
No fork for user nickdalt. Using upstream fork for user nickdalt at https://github.com/nickdalt/NuKeeperIssue878.git
User name missing from profile, falling back to .gitconfig
Git clone https://github.com/nickdalt/NuKeeperIssue878.git, branch default, to C:\Users\xxxx\AppData\Local\Temp\NuKeeper\repo-30a7da6230894739945e7acd643fbd1a
0 / 16
1 / 16
2 / 16
3 / 16
4 / 16
5 / 16
6 / 16
7 / 16
8 / 16
9 / 16
10 / 16
11 / 16
12 / 16
13 / 16
14 / 16
15 / 16
16 / 16
Git clone complete
Reading file C:\Users\xxxx\AppData\Roaming\NuGet\NuGet.Config for package sources
Reading file C:\Program Files (x86)\NuGet\Config\Microsoft.VisualStudio.Offline.config for package sources
Read [nuget.org] : https://api.nuget.org/v3/index.json from file: https://api.nuget.org/v3/index.json
Read [Microsoft Visual Studio Offline Packages] : file:///C:/Program Files (x86)/Microsoft SDKs/NuGetPackages/ from file: C:\Program Files (x86)\Microsoft SDKs\NuGetPackages\
Found 2 packages
Found 2 packages in use, 1 distinct, in 2 projects.
boost
  CACHE https://api.nuget.org/v3/registration3-gz-semver2/boost/index.json
Selected update of package boost to highest version, 1.70.0.
Found 1 possible updates
boost from 1.69.0.0 to 1.70.0 in packages.config
boost from 1.69.0.0 to 1.70.0 in ProjectB\packages.config

Output report named NuKeeperIssue878, is Text to Console
Found 1 package update
boost to 1.70.0 from 1.69.0.0 in 2 places since 4 months ago.
Wrote report for 1 updates
Sorted 1 packages by dependencies but no change made
No branch found for nickdalt / NuKeeperIssue878 / nukeeper-update-boost-to-1.70.0
Selection of package updates: 1 candidates
Selected package update of boost to 1.70.0
Nuget restore on C:\Users\xxxx\AppData\Local\Temp\NuKeeper\repo-30a7da6230894739945e7acd643fbd1a ProjectA.sln
Found NuGet.exe: C:\Users\xxxx\.dotnet\tools\.store\nukeeper\0.25.0\nukeeper\0.25.0\tools\netcoreapp2.1\any\NuGet.exe   In path C:\Users\xxxx\AppData\Local\Temp\NuKeeper\repo-30a7da6230894739945e7acd643fbd1a, running command: C:\Users\xxxx\.dotnet\tools\.store\nukeeper\0.25.0\nukeeper\0.25.0\tools\netcoreapp2.1\any\NuGet.exe restore ProjectA.sln -Source https://api.nuget.org/v3/index.json -Source "C:\Program Files (x86)\Microsoft SDKs\NuGetPackages\\"  -NonInteractive        Nuget restore on ProjectA.sln complete
Updating 'boost' from 1.69.0.0 to 1.70.0 in 2 projects
Git checkout 'master'
Using branch name: 'nukeeper-update-boost-to-1.70.0'
Git checkout new branch 'nukeeper-update-boost-to-1.70.0'
No dependencies between items, no need to sort on dependencies
Resorted 2 projects by dependencies, first change is ProjectB\packages.config moved to position 0 from 1.
Updating 'boost' to 1.70.0 in 2 projects
Nuget restore on C:\Users\xxxx\AppData\Local\Temp\NuKeeper\repo-30a7da6230894739945e7acd643fbd1a\ProjectB packages.config
Found NuGet.exe: C:\Users\xxxx\.dotnet\tools\.store\nukeeper\0.25.0\nukeeper\0.25.0\tools\netcoreapp2.1\any\NuGet.exe   In path C:\Users\xxxx\AppData\Local\Temp\NuKeeper\repo-30a7da6230894739945e7acd643fbd1a\ProjectB, running command: C:\Users\xxxx\.dotnet\tools\.store\nukeeper\0.25.0\nukeeper\0.25.0\tools\netcoreapp2.1\any\NuGet.exe restore packages.config -Source https://api.nuget.org/v3/index.json -Source "C:\Program Files (x86)\Microsoft SDKs\NuGetPackages\\"  -NonInteractive
Command C:\Users\xxxx\.dotnet\tools\.store\nukeeper\0.25.0\nukeeper\0.25.0\tools\netcoreapp2.1\any\NuGet.exe failed with exit code: 1



Cannot determine the packages folder to restore NuGet packages. Please specify either -PackagesDirectory or -SolutionDirectory.

Nuget restore failed on C:\Users\xxxx\AppData\Local\Temp\NuKeeper\repo-30a7da6230894739945e7acd643fbd1a\ProjectB packages.config:

Cannot determine the packages folder to restore NuGet packages. Please specify either -PackagesDirectory or -SolutionDirectory.

Found NuGet.exe: C:\Users\xxxx\.dotnet\tools\.store\nukeeper\0.25.0\nukeeper\0.25.0\tools\netcoreapp2.1\any\NuGet.exe   In path C:\Users\xxxx\AppData\Local\Temp\NuKeeper\repo-30a7da6230894739945e7acd643fbd1a\ProjectB, running command: C:\Users\xxxx\.dotnet\tools\.store\nukeeper\0.25.0\nukeeper\0.25.0\tools\netcoreapp2.1\any\NuGet.exe update packages.config -Id boost -Version 1.70.0 -Source https://api.nuget.org/v3/index.json -Source "C:\Program Files (x86)\Microsoft SDKs\NuGetPackages\\" -NonInteractive
Nuget restore on C:\Users\xxxx\AppData\Local\Temp\NuKeeper\repo-30a7da6230894739945e7acd643fbd1a packages.config
In path C:\Users\xxxx\AppData\Local\Temp\NuKeeper\repo-30a7da6230894739945e7acd643fbd1a, running command: C:\Users\xxxx\.dotnet\tools\.store\nukeeper\0.25.0\nukeeper\0.25.0\tools\netcoreapp2.1\any\NuGet.exe restore packages.config -Source https://api.nuget.org/v3/index.json -Source "C:\Program Files (x86)\Microsoft SDKs\NuGetPackages\\"  -NonInteractive     Command C:\Users\xxxx\.dotnet\tools\.store\nukeeper\0.25.0\nukeeper\0.25.0\tools\netcoreapp2.1\any\NuGet.exe failed with exit code: 1



Cannot determine the packages folder to restore NuGet packages. Please specify either -PackagesDirectory or -SolutionDirectory.

Nuget restore failed on C:\Users\xxxx\AppData\Local\Temp\NuKeeper\repo-30a7da6230894739945e7acd643fbd1a packages.config:
Cannot determine the packages folder to restore NuGet packages. Please specify either -PackagesDirectory or -SolutionDirectory.

In path C:\Users\xxxx\AppData\Local\Temp\NuKeeper\repo-30a7da6230894739945e7acd643fbd1a, running command: C:\Users\xxxx\.dotnet\tools\.store\nukeeper\0.25.0\nukeeper\0.25.0\tools\netcoreapp2.1\any\NuGet.exe update packages.config -Id boost -Version 1.70.0 -Source https://api.nuget.org/v3/index.json -Source "C:\Program Files (x86)\Microsoft SDKs\NuGetPackages\\" -NonInteractive
Command C:\Users\xxxx\.dotnet\tools\.store\nukeeper\0.25.0\nukeeper\0.25.0\tools\netcoreapp2.1\any\NuGet.exe failed with exit code: 1

MSBuild auto-detection: using msbuild version '16.3.0.45602' from 'C:\Program Files (x86)\Microsoft Visual Studio\2019\Preview\MSBuild\Current\bin'.


Unable to locate the packages folder. Verify all the packages are restored before running 'nuget.exe update'.

Updates failed NuKeeperException : Command C:\Users\xxxx\.dotnet\tools\.store\nukeeper\0.25.0\nukeeper\0.25.0\tools\netcoreapp2.1\any\NuGet.exe failed with exit code: 1

MSBuild auto-detection: using msbuild version '16.3.0.45602' from 'C:\Program Files (x86)\Microsoft Visual Studio\2019\Preview\MSBuild\Current\bin'.


Unable to locate the packages folder. Verify all the packages are restored before running 'nuget.exe update'.

   at NuKeeper.Update.ProcessRunner.ExternalProcess.Run(String workingDirectory, String command, String arguments, Boolean ensureSuccess) in /home/vsts/work/r1/a/drop/NuKeeper.Update/ProcessRunner/ExternalProcess.cs:line 63
   at NuKeeper.Update.Process.NuGetUpdatePackageCommand.Invoke(PackageInProject currentPackage, NuGetVersion newVersion, PackageSource packageSource, NuGetSources allSources) in /home/vsts/work/r1/a/drop/NuKeeper.Update/Process/NuGetUpdatePackageCommand.cs:line 59
   at NuKeeper.Update.UpdateRunner.Update(PackageUpdateSet updateSet, NuGetSources sources) in /home/vsts/work/r1/a/drop/NuKeeper.Update/UpdateRunner.cs:line 52
   at NuKeeper.Engine.Packages.PackageUpdater.MakeUpdatePullRequests(IGitDriver git, RepositoryData repository, NuGetSources sources, SettingsContainer settings, IReadOnlyCollection`1 updates) in /home/vsts/work/r1/a/drop/NuKeeper/Engine/Packages/PackageUpdater.cs:line 79
   at NuKeeper.Engine.Packages.PackageUpdater.MakeUpdatePullRequests(IGitDriver git, RepositoryData repository, IReadOnlyCollection`1 updates, NuGetSources sources, SettingsContainer settings) in /home/vsts/work/r1/a/drop/NuKeeper/Engine/Packages/PackageUpdater.cs:line 46
Attempted 1 updates and did 0                                                                                           Attempting delete of folder C:\Users\xxxx\AppData\Local\Temp\NuKeeper\repo-30a7da6230894739945e7acd643fbd1a
Deleted folder C:\Users\xxxx\AppData\Local\Temp\NuKeeper\repo-30a7da6230894739945e7acd643fbd1a
Done at 2019-09-26T19:45:15Z

# Introduction 
Demo on how to update an assemblyinfo of classic .Net Framework with GitVersion and generate valid AssemblyFileVersions. 
GitVersion uses by default SemVer to update assemblyversions.  By default GitVersion don't update the AssemblyFileVersion but you can configure it to do so.  This example demonstrate how to update your AssemblyVersion file without using semver but by incrementing the last number of your version by using the number of commits.
# Getting Started
Download and compile the code.
Install GitVersion
run: 
dotnet-gitversion /updateassemblyinfo
     or if you've not installed as Global .Net tool:
dotnet-gitversion /updateassemblyinfo
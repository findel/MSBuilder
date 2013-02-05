### MS Builder (Working Title) ###

Wouldn't it be cool if you could manage your MSBuild files (such as a .csproj file) using a Command Line Interface?

Just think, you could add an existing file:

`$ msbuilder MyProject.csproj --add-file="/src/Namespace/MyClass.cs"`

Or create new files from a template:

`$ msbuilder MyProject.csproj --create-file="/src/Namespace/MyInterface.cs" --template=CSharpInterface`

Then, when you have finished work using the editor of your choice, build using the command line too.

`$ msbuild MyProject.csproj`

Good idea? Bad idea? 

I'm looking for input and/or collaborators.
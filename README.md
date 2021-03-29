
Usage

```
cd stylecop-core
dotnet build
```

How it works. 

1. `Directory.Build.props` installs StyleCop.Analyzers for all projects.
2. `my.stylecop.ruleset` set the rule level to error, warning, or none.
3. `stylecop.json` tweaks some rules.

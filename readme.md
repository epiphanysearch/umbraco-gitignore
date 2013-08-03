# .gitignore for Umbraco

Place this in the root of your project directory.

It is a direct clone of [VisualStudio.gitignore](https://github.com/github/gitignore/blob/master/VisualStudio.gitignore) available in the [github/gitignore repository](https://github.com/github/gitignore), with some Umbraco-specific ignores.

```
# Umbraco stuff
# Data folders/files
*/ExamineIndexes/*
www/App_Data/umbraco.config
*/App_Browsers/*
*/App_Data/TEMP/*
*/_systemUmbracoIndexDontDelete/*
*/App_Data/Logs/*

# ImageGen
*/Cached/*

# Misc crud
*.orig
```

Contributions/pull requests to this <code>.gitignore</code> are welcome.
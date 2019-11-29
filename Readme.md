# Custom git hooks and sample hooks

To apply custom git hooks to your local project connect your git hooks templatedir to your global git config.
```
git config --global init.templatedir /path/to/your/git_hooks/
```

On git init these files will be included in you .git/hooks folder of the initialized project.

Read more https://wilsonmar.github.io/git-hooks/

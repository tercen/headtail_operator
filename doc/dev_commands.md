## setting up

in a shell:

```
rm README.md 
mv README_template.md README.md
```

## adding packages

in R console:

```R
renv::init()
```

## managing the repo

in a shell:

```
git add -A && git commit -m "fixed operator settings"
git push
git tag -a 0.0.3 -m "++" && git push --tags
```
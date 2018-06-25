# template-go
A template repository for Go applications with Travis CI &amp; Circle CI "integration".

## Info
For you to be able to use this as a template run:
```
find . -type f -print0 | xargs -0 sed -i "s/galexrt/$GITHUB_USER/g"
find . -type f -print0 | xargs -0 sed -i "s/dellhw_exporter/$PROJECT_NAME/g"
```
> Replace the following variables with your Github username and project name:
> * `GITHUB_USER`
> * `PROJECT_NAME`

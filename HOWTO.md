# How to create new content

Create new markdown file at the root folder and then index into **SUMMARY.md**

Then use the following command to pre-visualize the content.
```console
npx honkit serve
```

And then you may able to build the content using the **build** command.
```console
npx honkit build
```

## Things you might know before pushing content to github:

Use git checkout to double check that you are currently in the master branch.
After pushing to the master branch, you have to use the following command to publish the new uploaded content to our github page(make sure that you have gh-pages installed, if not, you might install it using npm):

```console
git subtree push --prefix _book origin gh-pages
```

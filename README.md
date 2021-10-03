# test-soft-service README

test for vscode deploy a snippet

# command line to create a vscode extention

```
yo code 

```
# command line to publish a vscode extention
[https://code.visualstudio.com/api/working-with-extensions/publishing-extension](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)


*create an organization and create a token

[https://dev.azure.com/](https://dev.azure.com/) create an organization and  then take token (for all organizations)

[https://marketplace.visualstudio.com/manage/](create a publisher) create publisher

```
npm install -g vsce

cd myExtension

vsce login <publisher name>

vsce publish



```

# should add 

```JSON

    "icon": "icon.png",
    "repository": {
        "type": "git",
        "url": "https://github.com/gitorhub/YOURREPONAME.git"
      },

```

*update readme.md file othre than default

this is a test readme

no need to install




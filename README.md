# Golang SDK


## Generate Golang sdk Git repository

    git init
    git remote add origin https://github.com/moeinghbh/golang-sdk.git

    go mod init github.com/moeinghbh/golang-sdk

## Add calculation function

    git add .
    git commit -m "add new golang project"
    git push -u origin main
    git tag v0.1.0
    git push --tags
    
## Get package from Git repository

    go mod init main
    go get github.com/MoeinGhbh/golang-SDK


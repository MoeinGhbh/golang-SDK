# Golang-SDK


## in golang sdk should make git repository

    git init
    git add .
    git commit -m "add new golang project"
    git remote add origin https://github.com/moeinghbh/golang-sdk.git
    
    git push -u origin main
    git tag v0.1.0
    git push --tags
    
    go mod init https://github.com/moeinghbh/golang-sdk




## in main module should get package from repository

    go mod init main
    
    go get github.com/MoeinGhbh/golang-SDK


# test-api  
- Install Beego  
`go get -u github.com/beego/bee`  
`go get -u github.com/astaxie/beego`  
- set the path  
`export PATH=$PATH:$GOROOT/bin` 
`export PATH=$PATH:$GOPATH/bin`  
`export GOPATH=$HOME/go`  
`export GO15VENDOREXPERIMENT=1`
`eval "$(goenv init -)"`  
- go/src内でsource ~/.bashrc
- go/src内でgit clone  
`git clone https://github.com/fu31/test-api.git`

bee run

access localhost:8080

@Library('github.com/rahulmr/multibranch-demo-lib') _
standardBuild {
    environment = 'golang:1.5.0'
    mainScript = '''
go version
go build -v hello-world.go
'''
    postScript = '''
echo 'Testing...'
./hello-world
'''
}

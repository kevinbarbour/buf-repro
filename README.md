When `buf generate` is run on the master branch everything works as expected.


With the addition of the `twirp-swagger` plugin in the repro branch, for some reason it seems to interfere with the validate import and the following error is printed on `buf generate`:
`2022/03/17 07:16:07  info Can't load validate/validate.proto, err=open validate/validate.proto: no such file or directory, ignoring (want to make PR?)`

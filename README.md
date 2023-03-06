## Steps to reproduce

- run `cd proto && buf mod update` to specify dependencies
- run `buf generate`
- check output in folder `ts/gen/test/v1/test_pb.js` (line 7)

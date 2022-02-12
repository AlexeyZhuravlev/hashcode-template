# hashcode

Building all execulables:

```
./build.sh
```

Re-building your executable:
```
./build.sh {lexa/timur/danya/dima}
```

Running your solution on specific test:

```
./run.sh {lexa/timur/danya/dima} {a/b/c/...} [-l|--long]
```

Running your solution on all tests:

```
./run.sh {lexa/timur/danya/dima} [-l|--long]
```

Following data stored into the results folder `results/{subfolder}`:
* Your binary `{lexa/timur/danya/dima}` which will actually be used for running
* Tar file with your `*.cpp` and `common.h`
* `*.ans` files for the solution

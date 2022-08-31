# bazel-pyspark: A Demo for PySpark based monorepo

## Cheatsheat
``` bash
# run single unit tests
bazel test tubi/dog/... --test_output=all

# list all python package target
bin/package

# package
bin/package //tubi/dog:assemble-pip
```

## References
+ https://github.com/thundergolfer/example-bazel-monorepo

# bazel-pyspark: A Demo for PySpark based monorepo

## Cheatsheat
``` bash
# run single unit tests
bazel test tubi/dog/... --test_output=all

# list all python package target
bin/package

# package
bin/package //tubi/dog:assemble-pip

# list all lint target
bin/lint

# lint
bin/lint //tubi/dog:lint

# format
bin/format
```

## References
+ https://github.com/thundergolfer/example-bazel-monorepo
+ https://github.com/bazelbuild/rules_python
+ package: https://github.com/vaticle/bazel-distribution
+ Experimentations on Bazel by David Bernard
  + https://dev.to/davidb31/experimentations-on-bazel-python-fastapi-1-a02
  + https://dev.to/davidb31/experimentations-on-bazel-python-2-linter-52
  + https://dev.to/davidb31/experimentations-on-bazel-python-3-linter-pytest-49oh

# OpenAPI Code Generator

This repository contains the following dagger function:

```Go
func OpenApiCodegen(Spec *dagger.File, Generator string) *dagger.Directory
```

That generates code from an OpenAPI specification file.

The function can be invoked with dagger by running the following command:

```bash
dagger call open-api-codegen --spec spec/spec.json --generator go
```

or (if your are not in the repository)

```bash
dagger -m github.com/FlrnFrmm/dagger-openapi-codegen call open-api-codegen --spec spec/spec.json --generator go
```

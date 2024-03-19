Grails User/Reference Guide
===========================

This is the project for generating the [Grails user & reference guide][Grails Documentation] that explains how to build applications with the [Grails][Grails] framework.

For contributing to grails docs look at [Building/Contributing to Grails Documentation][Contributing].

[Grails Documentation]: https://grails.org/doc/latest
[Grails]: https://grails.org
[Contributing]: https://grails.github.io/grails-doc/latest/guide/contributing.html#patchesDoc

### 翻译

需要修改`build.gradle`中publishGuide任务里:

```groovy
sourceDir = new File(projectDir, "src/zh")
```

### 如何Build

```shell
./gradlew publishGuide -x apiDocs
```

### 查看结果

分页模式：build/docs/guide/index.html
单页模式： build/docs/guide/single.html
# Do not edit. Generated by: https://github.com/johnynek/bazel-deps
licenses(["notice"])
java_library(
    name = "dagger",
    exports = [
        "//external:jar/com/google/dagger/dagger",
        "//third_party/java/javax/inject:javax_inject"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "dagger_compiler",
    exports = [
        "//external:jar/com/google/dagger/dagger_compiler",
        "//third_party/java/com/google/googlejavaformat:google_java_format",
        "//third_party/java/com/google/guava:guava",
        "//third_party/java/com/squareup:javapoet",
        "//third_party/java/javax/annotation:jsr250_api",
        "//third_party/java/javax/inject:javax_inject",
        ":dagger",
        ":dagger_producers",
        ":dagger_spi"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "dagger_producers",
    exports = [
        "//external:jar/com/google/dagger/dagger_producers",
        "//third_party/java/com/google/guava:guava",
        "//third_party/java/javax/inject:javax_inject",
        "//third_party/java/org/checkerframework:checker_compat_qual",
        ":dagger"
    ],
    visibility = [
        "//third_party/java:__subpackages__"
    ]
)



java_library(
    name = "dagger_spi",
    exports = [
        "//external:jar/com/google/dagger/dagger_spi",
        "//third_party/java/com/google/guava:guava",
        "//third_party/java/javax/inject:javax_inject",
        ":dagger",
        ":dagger_producers"
    ],
    visibility = [
        "//third_party/java:__subpackages__"
    ]
)



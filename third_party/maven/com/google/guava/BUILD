java_library(
    name = "failureaccess",
    licenses = [
        "permissive",
    ],
    visibility = [
        "//third_party/maven:__subpackages__",
    ],
    exports = [
        "//external:jar/mvncom/google/guava/failureaccess",
    ],
)

java_library(
    name = "guava",
    licenses = [
        "permissive",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        "//external:jar/mvncom/google/guava/guava",
    ],
    runtime_deps = [
        ":failureaccess",
        ":listenablefuture",
        "//third_party/maven/com/google/code/findbugs:jsr305",
        "//third_party/maven/com/google/errorprone:error_prone_annotations",
        "//third_party/maven/com/google/j2objc:j2objc_annotations",
        "//third_party/maven/org/checkerframework:checker_qual",
        "//third_party/maven/org/codehaus/mojo:animal_sniffer_annotations",
    ],
)

java_library(
    name = "listenablefuture",
    licenses = [
        "permissive",
    ],
    visibility = [
        "//third_party/maven:__subpackages__",
    ],
    exports = [
        "//external:jar/mvncom/google/guava/listenablefuture",
    ],
)

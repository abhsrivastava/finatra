scala_library(
  provides = scala_artifact(
    org = 'com.twitter',
    name = 'inject-slf4j',
    repo = artifactory,
  ),
  dependencies=[
    '3rdparty/jvm/com/fasterxml/jackson/core:jackson-annotations',
    '3rdparty/jvm/com/google/guava:guava',
    '3rdparty/jvm/org/slf4j:jcl-over-slf4j',
    '3rdparty/jvm/org/slf4j:jul-to-slf4j',
    '3rdparty/jvm/org/slf4j:log4j-over-slf4j',
    '3rdparty/jvm/org/slf4j:slf4j-api',
    'util/util-core/src/main/scala',
    'util/util-slf4j-api/src/main/scala',
  ],
  excludes=[
    exclude(org='org.clapper', name='grizzled-slf4j')
  ],
  fatal_warnings=True,
  sources=rglobs('*.scala'),
  strict_deps=True,
)

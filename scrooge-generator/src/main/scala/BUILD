scala_library(name='scala',
  provides = scala_artifact(
    org = 'com.twitter',
    name = 'scrooge-generator',
    repo = artifactory,
  ),
  dependencies=[
    '3rdparty/jvm/com/github/scopt',
    '3rdparty/jvm/com/github/spullara/mustache/java',
    '3rdparty/jvm/com/google/code/findbugs:jsr305',
    '3rdparty/jvm/com/google/guava',
    '3rdparty/jvm/commons-cli',
    '3rdparty/jvm/org/apache/thrift:libthrift-0.5.0',
    '3rdparty/jvm/org/codehaus/plexus:plexus-utils',
    '3rdparty/jvm/org/scala-lang:scala-library',
    'util/util-codec',
    'util/util-core',
    'util/util-logging',
  ],
  fatal_warnings=True,
  strict_deps=True,
  sources=rglobs('*.scala'),
  resources=[
    'scrooge/scrooge-generator/src/main/resources:resources'
  ],
)

# main twitter-server

scala_library(name='scala',
  dependencies=[
    pants('3rdparty:jackson-module-scala'),
    pants('3rdparty:netty'),
    pants('finagle/finagle-core'),
    pants('finagle/finagle-http'),
    pants('finagle/finagle-stats'),
    pants('util/util-app'),
    pants('util/util-core'),
    pants('util/util-jvm'),
    pants('util/util-logging')
  ],
  sources=rglobs('*.scala'),
  resources=[pants('twitter-server/src/main/resources')]
)

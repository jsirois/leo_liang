jvm_binary(
  name='main-bin',
  basename='hello-world-client',
  dependencies=[
    '3rdparty:slf4j-simple',
    '3rdparty:thrift-0.9.2',
    'src/thrift/hws:hello-world-service-java',
  ],
  source='HelloWorldClient.java',
  main='hwc.HelloWorldClient',
)

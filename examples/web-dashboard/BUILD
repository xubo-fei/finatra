target(
  dependencies=[
    'finatra/examples/web-dashboard/src/main/scala'
  ]
)

jvm_binary(
  name='bin',
  basename='web-dashboard',
  main='com.twitter.web.dashboard.ServerMain',
  dependencies=[
    ':web-dashboard'
  ],
  excludes=[
    exclude('org.slf4j', 'slf4j-jdk14'),
    exclude('log4j', 'log4j')
  ]
)

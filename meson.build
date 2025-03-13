project('safe_arithmetic',
  languages : ['cpp'],
  default_options : ['cpp_std=c++20']
  )

boost_dep = dependency('boost', required: true)

inc = include_directories('include')

safe_arithmetic_dep = declare_dependency(
  include_directories : inc,
  dependencies : [boost_dep]
  )

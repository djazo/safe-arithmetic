project('safe_arithmetic',
  ['cpp'],
  default_options : ['cpp_std=c++20']
  )

boostmp11_sub = subproject('boostmp11')
boostmp11_dep = boostmp11_sub.get_variable('boostmp11_dep')

inc = include_directories('include')

safe_arithmetic_dep = declare_dependency(
  include_directories : inc,
  dependencies : [boostmp11_dep]
  )

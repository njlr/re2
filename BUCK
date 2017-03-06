include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 're2',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('', 're2/*.h'),
  ]),
  headers = subdir_glob([
    ('', 'util/*.h'),
  ]),
  srcs = glob([
    're2/*.cc',
    'util/*.cc',
  ]),
  compiler_flags = [
    '-std=c++11',
  ],
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)

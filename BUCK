load('//:subdir_glob.bzl', 'subdir_glob')

cxx_library(
  name = 'poly2tri',
  header_namespace = 'poly2tri',
  exported_headers = subdir_glob([
    ('poly2tri', '**/*.h'),
  ]),
  srcs = glob([
    'poly2tri/**/*.cc',
  ]),
  visibility = ['PUBLIC']
)

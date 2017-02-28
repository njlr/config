prebuilt_cxx_library(
  name = 'boost-config',
  header_only = True,
  header_namespace = 'boost', 
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
)

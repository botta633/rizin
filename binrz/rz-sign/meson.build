executable('rz-sign', 'rz-sign.c',
  c_args: executable_cflags,
  include_directories: [platform_inc],
  dependencies: [
    rz_util_dep,
    rz_main_dep,
    rz_search_dep,
    rz_core_dep,
    rz_bin_dep,
  ],
  install: true,
  install_rpath: rpath_exe,
  implicit_include_directories: false,
  link_args: executable_linkflags
)

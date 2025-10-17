patch_prog = executable(
    'patch',
    [ 'backupfile.c',
      'inp.c',
      'mkpath.c',
      'patch.c',
      'pch.c',
      'util.c',
    ],
    include_directories : inc,
    link_with : [ libcompat ],
    install : true,
)

install_man('patch.1')

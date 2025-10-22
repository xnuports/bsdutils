diff_prog = executable(
    'diff',
    [ 'diff.c',
      'diffdir.c',
      'diffreg.c',
      'xmalloc.c',
      'pr.c',
    ],
    include_directories : inc,
    c_args : '-D_GNU_SOURCE',
    dependencies : [ libm, ],
    install : true,
)

install_man('diff.1')

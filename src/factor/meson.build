factor_prog = executable(
    'factor',
    [ 'factor.c',
      'pr_tbl.c',
    ],
    c_args : [ '-DHAVE_OPENSSL' ],
    dependencies : [ libcrypto, ],
    install : true,
)

install_man('factor.6')

ee_cargs = [ '-Wno-pointer-sign',
             '-Wno-unused-parameter',
             '-Wno-sign-compare',
             '-Wno-maybe-uninitialized',
             '-Wno-format-overflow',
             '-DBSD_SELECT',
             '-DHAS_NCURSES',
             '-DHAS_UNISTD',
             '-DHAS_STDLIB',
             '-DHAS_CTYPE',
             '-DHAS_SYS_IOCTL',
             '-DHAS_SYS_WAIT',
             '-DSLCT_HDR',
           ]

ee_prog = executable(
    'ee',
    [ 'ee.c' ],
    c_args : ee_cargs,
    include_directories : inc,
    dependencies : [ libncurses ],
    install : true,
)

install_man('ee.1')

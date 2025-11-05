grep_prog = executable(
    'grep',
    [ 'file.c',
      'grep.c',
      'queue.c',
      'util.c',
    ],
    c_args : [ '--param', 'max-inline-insns-single=500' ],
    include_directories : inc,
    install : true,
)

install_symlink('egrep', install_dir : get_option('bindir'), pointing_to : 'grep')
install_symlink('fgrep', install_dir : get_option('bindir'), pointing_to : 'grep')
install_symlink('rgrep', install_dir : get_option('bindir'), pointing_to : 'grep')

install_man('grep.1')

install_symlink('egrep.1', install_dir : get_option('mandir') / 'man1', pointing_to : 'grep.1')
install_symlink('fgrep.1', install_dir : get_option('mandir') / 'man1', pointing_to : 'grep.1')
install_symlink('rgrep.1', install_dir : get_option('mandir') / 'man1', pointing_to : 'grep.1')

install_data(
    'zgrep.sh',
    install_dir : get_option('bindir'),
    install_mode : 'rwxr-xr-x',
    rename : ['zgrep'],
)

install_symlink('zfgrep', install_dir : get_option('bindir'), pointing_to : 'zgrep')
install_symlink('zegrep', install_dir : get_option('bindir'), pointing_to : 'zgrep')
install_symlink('bzgrep', install_dir : get_option('bindir'), pointing_to : 'zgrep')
install_symlink('bzegrep', install_dir : get_option('bindir'), pointing_to : 'zgrep')
install_symlink('bzfgrep', install_dir : get_option('bindir'), pointing_to : 'zgrep')
install_symlink('lzgrep', install_dir : get_option('bindir'), pointing_to : 'zgrep')
install_symlink('lzegrep', install_dir : get_option('bindir'), pointing_to : 'zgrep')
install_symlink('lzfgrep', install_dir : get_option('bindir'), pointing_to : 'zgrep')
install_symlink('zstdgrep', install_dir : get_option('bindir'), pointing_to : 'zgrep')
install_symlink('zstdegrep', install_dir : get_option('bindir'), pointing_to : 'zgrep')
install_symlink('zstdfgrep', install_dir : get_option('bindir'), pointing_to : 'zgrep')

install_man('zgrep.1')

install_symlink('zfgrep.1', install_dir : get_option('mandir') / 'man1', pointing_to : 'zgrep.1')
install_symlink('zegrep.1', install_dir : get_option('mandir') / 'man1', pointing_to : 'zgrep.1')
install_symlink('bzgrep.1', install_dir : get_option('mandir') / 'man1', pointing_to : 'zgrep.1')
install_symlink('bzegrep.1', install_dir : get_option('mandir') / 'man1', pointing_to : 'zgrep.1')
install_symlink('bzfgrep.1', install_dir : get_option('mandir') / 'man1', pointing_to : 'zgrep.1')
install_symlink('lzgrep.1', install_dir : get_option('mandir') / 'man1', pointing_to : 'zgrep.1')
install_symlink('lzegrep.1', install_dir : get_option('mandir') / 'man1', pointing_to : 'zgrep.1')
install_symlink('lzfgrep.1', install_dir : get_option('mandir') / 'man1', pointing_to : 'zgrep.1')
install_symlink('zstdgrep.1', install_dir : get_option('mandir') / 'man1', pointing_to : 'zgrep.1')
install_symlink('zstdegrep.1', install_dir : get_option('mandir') / 'man1', pointing_to : 'zgrep.1')
install_symlink('zstdfgrep.1', install_dir : get_option('mandir') / 'man1', pointing_to : 'zgrep.1')

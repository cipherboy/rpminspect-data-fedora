project('rpminspect-data-fedora',
        version : '0.9',
        license : 'GPLv3+',
        meson_version : '>=0.47.0')

# Install data files
install_subdir(
    'abi-checking-whitelist',
    install_dir : get_option('datadir') + '/rpminspect'
)
install_subdir(
    'capabilities',
    install_dir : get_option('datadir') + '/rpminspect'
)
install_subdir(
    'licenses',
    install_dir : get_option('datadir') + '/rpminspect'
)
install_subdir(
    'political-whitelist',
    install_dir : get_option('datadir') + '/rpminspect'
)
install_subdir(
    'stat-whitelist',
    install_dir : get_option('datadir') + '/rpminspect'
)
install_subdir(
    'version-whitelist',
    install_dir : get_option('datadir') + '/rpminspect'
)

# Install the configuration file
install_data(
    sources : 'rpminspect.conf',
    install_dir : get_option('sysconfdir') + '/rpminspect'
)

install_subdir(
    'profiles',
    install_dir : get_option('sysconfdir') + '/rpminspect'
)

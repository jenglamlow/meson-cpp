project('Voila', 'cpp',
    version: '1.0.0')
inc = include_directories('include')

subdir('include')
subdir('src')
subdir('test')

pkg_mod = import('pkgconfig')
pkg_mod.generate(libraries : voila_lib,
                 version : '1.0',
                 name : 'Voila lib',
                 filebase : 'Voila filebase',
                 description : 'A Library to barnicate your foos.')


project('example', 'c')
# Source files
src = [
    'main.c'
]

# Qt5 dependencies
deps = [
    #dependency('exapmle'),
]

# -fPIC required
links = ['-lpam', '-lpam_misc']

# executable file
executable('main', src, dependencies: deps, link_args: links)

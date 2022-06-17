project('libalac', 'c', 'cpp')

libalacsrc = [
    'codec/EndianPortable.c',
    'codec/ALACBitUtilities.c',
    'codec/ALACDecoder.cpp',
    'codec/ALACEncoder.cpp',
    'codec/ag_dec.c',
    'codec/ag_enc.c',
    'codec/dp_dec.c',
    'codec/dp_enc.c',
    'codec/matrix_dec.c',
    'codec/matrix_enc.c',
]

libalac = library('libalac', libalacsrc)

libalac_dep = declare_dependency(include_directories : 'codec',
  link_with :libalac)


project('pamixer', 'cpp', version : '1.6-dev',
  default_options : ['cpp_std=c++11'])

src = files([
  'src/callbacks.cc',
  'src/device.cc',
  'src/pulseaudio.cc'
])


pulse = dependency('libpulse')

static_library('pamixer', 
  sources : src,
  install : true,
  dependencies : [pulse])


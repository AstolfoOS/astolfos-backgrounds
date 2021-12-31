backgrounds = [
  'astolfo-1.jpg',
  'astolfo-2.jpg',
  'astolfo-3.jpg',
]

install_data(backgrounds, install_dir: backgrounddir)

configure_file(
  input: 'astolfos-backgrounds.xml.in',
  output: 'astolfos-backgrounds.xml',
  configuration: {
    'BACKGROUNDDIR': backgrounddir,
  },
  install: true,
  install_dir: gnome_metadatadir
)

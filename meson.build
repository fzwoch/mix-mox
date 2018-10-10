project('mix-mox', 'c', 'vala')

executable('mix-mox', 'mix-mox.vala',
	dependencies : [
		dependency('gtk+-3.0'),
		dependency('gstreamer-1.0', version : '>= 1.10.5'),
		dependency('libsoup-2.4'),
		dependency('json-glib-1.0'),
		dependency('x11')
	],
	install : true
)

install_data('mix-mox.desktop', install_dir : 'share/applications')
install_data('mix-mox.svg', install_dir : 'share/mix-mox')

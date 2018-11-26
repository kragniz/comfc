comfc_src = files(
	'comf.c',
)

comfc_deps = [
	wayland_server,
	wlroots,
	pixman,
	xkbcommon,
]

executable(
	'comfc',
	comfc_src,
	include_directories: [inc_folder],
	dependencies: [comfc_deps, wlr_protos],
	install: true
)

INST_DIR := /usr/bin

all:

deb:
	fakeroot dpkg-buildpackage -b -uc

install:
	install -m 0755 -d $(DESTDIR)$(INST_DIR)
	install -m 0755 atom_link_system_pkg atom_debian_packager atom2debian $(DESTDIR)$(INST_DIR)




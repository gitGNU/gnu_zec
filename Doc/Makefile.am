dist_man_MANS = zec.6
MAINTAINERCLEANFILES = zec.6

SGML_FILES = zec.sgml
EXTRA_DIST = $(SGML_FILES)

zec.6: zec.sgml
	        docbook-to-man $< > $@


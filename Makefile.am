SUBDIRS =	\
	build	\
	help	\
	${SPARKLE_SMARTIRC4NETDIR} \
	SparkleLib \
	SparkleShare \
	data \
	po

EXTRA_DIST = gnome-doc-utils.make \
             LICENSE

DISTCLEANFILES = \
	intltool-extract        \
	intltool-merge          \
	intltool-update		\
	gnome-doc-utils.make

clean-local:
	rm -rf $(top_builddir)/bin

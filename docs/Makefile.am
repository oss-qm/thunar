SUBDIRS =								\
	design								\
	papers

doc_DATA =								\
	README.gtkrc

man_MANS =								\
	Thunar.1

%.1: %.xml
	xsltproc -nonet http://docbook.sourceforge.net/release/xsl/current/manpages/docbook.xsl $<

EXTRA_DIST =								\
	$(doc_DATA)							\
	$(man_MANS)							\
	Thunar.xml

# vi:set ts=8 sw=8 noet ai nocindent syntax=automake:

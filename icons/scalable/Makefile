DIRS = places

all:
.PHONY: all
clean:
.PHONY: clean

MYDESTDIR = $(DESTDIR)/usr/share/icons/hicolor/$(notdir $(shell pwd))
install:
	install -d $(MYDESTDIR)
	for dir in $(DIRS); do \
		cp -r $$dir $(MYDESTDIR)/ || exit 1; \
	done
.PHONY: install

SUBDIRS:=	bin dotfiles lib

all clean: $(SUBDIRS)
	@for DIR in $(SUBDIRS); do $(MAKE) -C $$DIR $@; done

# vim:set noet sw=8 ts=8:

modprefix = /usr/local/lib/site-python

INSTALLDIR = install -d
INSTALLMOD = install -p -m 644

all:	build

build:	

install: all
	$(INSTALLDIR) $(modprefix)/Lampadas
	$(INSTALLMOD) *.py  $(modprefix)/Lampadas
	$(INSTALLMOD) Lampadas.pth  $(modprefix)
	cd data; $(MAKE) install

clean:
	rm -f *.pyc

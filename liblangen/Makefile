# $Id: Makefile 1473 2011-04-01 00:09:31Z davidpiegdon $
# liblangen (LANguageGENerator) Makefile

.PHONY: all testsuites clean install uninstall

all:
	+make -C src all

testsuites: all
	make -C testsuites

clean:
	+make -C src clean
	+make -C testsuites clean

install:
	+make -C include install
	+make -C src install

uninstall:
	make -C include uninstall
	make -C src uninstall


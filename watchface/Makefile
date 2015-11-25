#
#  CONTENT
#    
#
#  AUTHOR
#    Norbert
#
#  DATE
#    2015-11-24
#
#  LANGUAGE
#    make
#

all:
	pebble build

clean:
	pebble clean

install: all
	pebble install --phone 10.0.0.134

emu: all
	pebble install --emulator basalt

log:
	pebble logs

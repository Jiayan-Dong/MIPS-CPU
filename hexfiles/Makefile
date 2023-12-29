BZ2S    := $(wildcard ./*.bz2)
TXTS    := $(wildcard ./*.txt)

.PHONY : all unzip zip

unzip: $(BZ2S)
	bunzip2 $(BZ2S)

zip: $(TXTS)
	bzip2 $(TXTS)

clean:
	rm -f *.txt

clean_all:
	rm -f *.c *.dis *.hex *.txt *.bz2 *.h *.ld
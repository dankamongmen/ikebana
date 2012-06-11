.PHONY: all clean

all:

#@svn status | grep ^? | cut -b8- | grep -v .tar.gz$$ | xargs rm -rfv
clean:
	git status --ignored -s | grep ^!! | cut -b4- | xargs rm -rfv

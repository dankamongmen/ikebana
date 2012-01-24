.PHONY: clean mrproper

clean:
	@svn status | grep ^? | cut -b8- | grep -v .tar.gz$$ | xargs rm -rfv

mrproper: clean
	@svn status | grep ^? | cut -b8- | grep .tar.gz$$ | xargs rm -rfv

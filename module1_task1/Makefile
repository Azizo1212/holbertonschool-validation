HUGO_BIN = hugo

HUGO_OPTS = --destination dist


all: build


build:

	$(HUGO_BIN) $(HUGO_OPTS)


clean:

	rm -rf dist


post:

	$(HUGO_BIN) new posts/$(POST_NAME).md


.PHONY: all build clean post

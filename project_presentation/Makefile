# Makefile
#
# Use pandoc to translate to a reveal.js HTML presentation

SOURCE=project_presentation.md
# Pandoc options
# I tweaked the theme CSS to add text-shadows. Might be needed to read the text.
PANDOC_OPTIONS=-t revealjs --self-contained -V revealjs-url="http://lab.hakim.se/reveal-js" -V theme=black

all: project_presentation.html

project_presentation.html: $(SOURCE)
	pandoc $(PANDOC_OPTIONS) -s $(SOURCE) -o $@

clean:
	rm project_presentation.html

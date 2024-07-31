all:
	@echo "main [option]"

run:
	v watch -o *.v,*.html run src

build:
	v -prod -o app.exe src

test:
	v -stats test src

fmt:
	v fmt -w src

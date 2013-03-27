Program=make documen
.PHONY:all
all: bash bashbug
.PHONY:make-documentation
make-documentation: build_msg 
	df -k . | awk 'NR == 2 {printf("%d available\n", $$4)}'
.PHONY:build_msg
build_msg:
	@printf "#\n# Building $(Program)\n#\n"	

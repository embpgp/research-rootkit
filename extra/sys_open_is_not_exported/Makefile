obj-m := symbols.o


default:
	${MAKE} modules \
		--directory "/lib/modules/$(shell uname --release)/build" \
		M="$(shell pwd)"


clean:
	${MAKE} clean \
		--directory "/lib/modules/$(shell uname --release)/build" \
		M="$(shell pwd)"

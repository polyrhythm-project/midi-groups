.PHONY: midi

midi:
	-mkdir -p midi
	for i in kern/*.krn; \
	do hum2mid -T $$i -o midi/$$(basename $$i .krn).mid; \
	done

group:
	-mkdir -p kern
	for i in ../both/kern/*.krn; \
	do composite -o A $$i > kern/$$(basename $$i .krn)-groupA.krn; \
	done



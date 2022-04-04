.PHONY: midi

midi:
	-mkdir -p midi
	for i in kern/*.krn; \
	do hum2mid -T $$i -o midi/$$(basename $$i .krn).mid; \
	done

group:
	-mkdir -p kern
	for i in ../both/kern/*.krn; \
	do composite -o B $$i > kern/$$(basename $$i .krn)-groupB.krn; \
	done



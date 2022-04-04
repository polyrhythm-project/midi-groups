.PHONY: midi

midi:
	for i in kern/*.krn; \
	do hum2mid -T $$i -o midi/$$(basename $$i .krn).mid; \
	done

copy:
	cp ../../../rds-scores/kern/* kern
	cp ../../../tds-scores/batches/*/*.krn kern



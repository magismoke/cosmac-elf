mvgbr:
	mv *.gbr ./cosmac_elf_gerbers
	mv *.cnc ./cosmac_elf_gerbers
ps:
	gschem -p -o cool_pwr.ps -s /usr/share/gEDA/scheme/print.scm elf1802.sch

pdf:
	ps2pdf -sPAPERSIZE=a4 elf1802.ps

zip:
	7za a -tzip cosmac_elf_gerbers.zip cosmac_elf_gerbers/

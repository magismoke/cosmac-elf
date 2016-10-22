mvgbr:
	mv *.gbr ./switchboard_gerbers
	mv *.cnc ./switchboard_gerbers
ps:
	gschem -p -o cool_pwr.ps -s /usr/share/gEDA/scheme/print.scm elf1802.sch

pdf:
	ps2pdf -sPAPERSIZE=a4 switchboard.ps

zip:
	7za a -tzip switchboard_gerbers.zip switchboard_gerbers/

.PHONY : report title clear main open

report : main open

main : ./tex/MakefileTex
	cd ./tex && make -f MakefileTex

open :
	xdg-open Economics.pdf

clear :
	rm -rf ./pdf/report.pdf ./out/
	cd ./tex && make -f MakefileTex clear

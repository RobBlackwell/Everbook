
checklist-a4.pdf: checklist-us.pdf
	pdfjam checklist-us.pdf --outfile checklist-a4.pdf --paper a4paper --landscape --otheredge


checklist-us.pdf :
	curl --output checklist-us.pdf https://everbookforever.com/wp-content/uploads/2020/10/CHECKLIST.pdf

clean:
	rm -rf *pdf

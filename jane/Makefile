DATE=`date +"%d-%m-%Y"`

today:
	#@echo git co -b $(DATE)
	mkdir bydate/$(DATE)
	cp ../templates/template.md bydate/$(DATE)/debrief.md
	exec vim bydate/$(DATE)/debrief.md

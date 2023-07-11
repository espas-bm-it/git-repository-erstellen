# Repository erstellen mit git Befehle auf CMD oder GUI

## Lokales Repositry mit Github Repository verbinden

	echo "# xyz.bm-it.ch" >> README.md (README File erstellen)
	git init
	git add .\filename
	git commit -m "first commit"
	git branch -M main
	git remote add origin https://github.com/bmit-xyz/xyz.bm-it.ch.git (URL von Ihren Portfolio Repository)
	git push -u origin main

###  Änderungen Stagen, commiten und Branch in Github veröffentlichen 

	- Terminal:  

		git add ./filename 
		git commit -m "ein sinnvolles Nachricht zur Änderungen"
		git push -u origin main (oder master)
		
		Beispiel: 
			git add [./README.md ./homepage.html]
			git commit -m "readme updated"
			git push -u origin master

	
	- GUI  (General User Interface)
			- In VSC Source Code (Ctrl + Shift + G)
			- Änderungen Stagen
            	- Commit Nachricht schreiben und Branch in Github veröffentlichen

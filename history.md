# Отчет о проделанной работе


## автор Шаяпов Руслан Ринатович, группа ПИ31з

### -ссылка на репозиторий Animals https://github.com/ShayapovRuslan/wild_animals1.git
### -ссылка на репозиторий геометрические фигу ры
### https://github.com/ShayapovRuslan/geometric_lib.git


#### Ход работы
*	cd desktop
*	git clone https://github.com/smartiqaorg/geometric_lib.git
*	cd geometric_lib/
*	git merge develop --no-ff
*	git log --all --pretty=oneline –graph
*	git reset --hard HEAD^
*	git log --all --pretty=oneline –graph
*	git merge develop –ff
*	git log --all --pretty=oneline –graph
*	git config merge.conflictstyle diff3
*	git config --global merge.tool meld
*	git checkout release
*	git rebase -i main
*	git mergetool
*	git difftool
*	git mergetool
*	git config --global merge.tool meld
*	git config --global mergetool.meld.path "C:\Program Files (x86)\Meld\Meld.exe"
*	git mergetool
*	git mergetool
*	git rebase –continue
*	git mergetool
*	git rebase –continue
*	git log --all --pretty=oneline –graph
*	git checkout main
*	git merge release –ff
*	git log --pretty=oneline --graph
* git push origin1 main
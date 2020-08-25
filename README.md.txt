Лабораториска вежба 1 - Марко Ичев 183228

1. Клонирање на репо со git clone.
2. Поврзување на remote репо-то со локалниот.
3. Креирање на текст фајл students.cvs, правиме git add ., git commit -m 'addfile students.cvs', и го синхронизираме со репо-то со git push
4.Креирање на текст фајл teachers.cvs, правиме git add ., git commit -m 'addfile teachers.cvs', и го синхронизираме со репо-то со git push
5. Креираме нова гранка со командата git checkout -b courseFeature
6. Креираме нов фајл courses.cvs, правиме git add ., git commit -m 'addfile courses.cvs и го push-нуваме во гранката. 
7. Правиме git checkout master, за да се префрлиме на master, го променуваме фајлот што требаше да се промени правиме равиме git add ., git commit -m 'Promena na iminja'.
8. Ги спојуваме гранките со командата git merge coursesFeature , и правиме git push origin master. 
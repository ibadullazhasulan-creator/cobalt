COBALT 3D LAB — GitHub Pages үшін жөнделген бірфайлдық нұсқа

GitHub репозиторийіңіз:
https://github.com/ibadullazhasulan-creator/avtomektep-sayt

Сайтыңыз:
https://ibadullazhasulan-creator.github.io/avtomektep-sayt/

ЖӨНДЕУ (VS CODE + GIT)
1) Осы ZIP-ті ашыңыз. Ішіндегі index.html — толық бірфайлдық сайт.
2) VS Code-та avtomektep-sayt репозиторийіңіз орналасқан қалтаны ашыңыз.
3) Сол қалтадағы ескі index.html файлын осы файлмен ауыстырыңыз.
4) VS Code Terminal-да төмендегі пәрмендерді орындаңыз:
   git add index.html
   git commit -m "Fix Cobalt 3D GitHub Pages"
   git push origin main
5) GitHub Pages сілтемесін ашып Ctrl+F5 басыңыз.

Егер репозиторий VS Code-та жоқ болса, бірінші мына пәрменді орындаңыз:
   git clone https://github.com/ibadullazhasulan-creator/avtomektep-sayt.git
Сосын 'avtomektep-sayt' қалтасын ашып, 3-5 қадамдарды орындаңыз.

БҰЛ НҰСҚАДА:
- Стильдер index.html ішінде — styles.css жүктеу қажет емес.
- 3D логика, каталог, үлгі index.html ішінде — src қалтасы қажет емес.
- Сыртқы Three.js кітапханасы интернеттен жүктеледі (jsdelivr.net).
- Бұл оқу мақсатында код арқылы салынған 3D үлгі, зауыт CAD файлы емес.
- 3D жүктелмесе, Chrome DevTools F12 Console бөлімін ашып қатені қараңыз.

НЕМЕСЕ АЛДЫҢҒЫ КӨПФАЙЛДЫ ЖОБАНЫ ҚАЛДЫРҒЫҢЫЗ КЕЛСЕ:
GitHub репозиторийінің түбіне src/ және assets/ қалталарын толық жүктеңіз.

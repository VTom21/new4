segédlet
VSC-BEN terminál nyitása,git bash #ha nincs,akkor git scm telepítése.
mkdir git-tutorial #munkakönyvtár létrehozása(make directory)
cd git tutorial #mappa választás
echo "git" beleírása a readme.md fájlba
ls #list mappa listázása
git init #könyvtár inicializálása Git mappává
git config --global --list #a globális beállítások listázása
git status #jelenlegi munkafolyamat állapota
git add readme.md #readme.md változtatásainak staging-elése
git commit -m #összes staging commitolása "First Commit üzenettel"
git remote add origin (link) # origin néven hozzáadja a címben lévő repot.
git remote -v #ellenőrizzük a távoli repokat
git remote remove origin #Az origin nevű távoli repo eltávolítása
git push -u origin master #új branch esetén használjuk

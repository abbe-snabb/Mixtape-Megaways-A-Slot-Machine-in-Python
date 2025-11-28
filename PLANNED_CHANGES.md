1. Fixa partiklarna så dem ser lite bättre ut! Eventuellt att lägga til mer när saker och ting händer eller liknande.
2. Lägg till ljud
3. köp bonus blocket måste scalea till hur lång texten är i alla olika språk, så att inte texten flyter utanför boxen!




### UPDATE THE DEMO VERSION ON GITHUB ###
# once
python -m pip install pygame-ce pygbag

# every time you want to rebuild the web version:
python -m pygbag --build .
mkdir -p docs
cp -r build/web/* docs/
git add .
git commit -m "Update web build"
git push
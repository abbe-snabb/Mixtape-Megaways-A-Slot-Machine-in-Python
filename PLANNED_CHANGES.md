1. Fixa partiklarna så dem ser lite bättre ut! Eventuellt att lägga til mer när saker och ting händer eller liknande.
2. Lägg till ljud
3. informationsknappen ska ha paytable (Vilket den redan har) och information-sida så som hur många scatter symboler som behövs för att trigga bonusen, samt maxwin: 5000x.
4. Bakgrundspartiklar ska ligga bakom grid-blocket.
5. Language button som ändrar all text från ett språk till ett annat. Tillgängliga språk ska vara (Svenska, Engelska, Tyska, Franska, Spanska).



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
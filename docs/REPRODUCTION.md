# Reproduire la version de pr?paration

Installer Python, reportlab, pymupdf et Pillow. La mise en page utilise Arial
pr?sente sous Windows dans C:/Windows/Fonts. Depuis le d?p?t :

    python scripts/construire_l1.py

Les sorties sont dans build/ ; les documents et le rapport sont ?galement
recopi?s dans corpus/ et docs/. Attention : cette commande reconstruit la version
non valid?e et r?initialise ses signatures. Conserver les modifications de
relecture dans Git et ne pas reconstruire par-dessus une ?dition sign?e.
Les donn?es r?dactionnelles V2.2 sont conserv?es dans materiaux_redaction/v22.
Elles sont des entr?es de r?daction, pas un second corpus ? indexer.
L?historique exact des premi?res g?n?rations n?est pas recr?? artificiellement.

U datoteci config.txt se nalaze postavke. 
Prvo je timetorun �to ozna�ava koliko duga da aplikacija radi.
Drugo je intervalInSeconds i to ozna�ava svakih koliko sekundi da se napravi screenshot.
Tre�e je destinationMail no koji da se �alju screenshotovi.

U slu�aju da se �eli promijenit na 9 minuta trajanje i screenshot svakih 40 sekundi,
te mail na mojmail@mail.com tada to izgleda ovako:
timetorun=30
intervalInSeconds=12
destinationMail=mojmail@mail.com

NAPOMENA!!!!

Iza brojeva i maila NEMA razmaka ili bilo kakvih dodatnih znakova. 
Kao �to nema ni poslije = razmaka.
Ako ih bude, ne�e se uzimati u obzir i program �e raditi predefiniranih 15 minuta
s intervalom za screendshot od 7 sekundi.

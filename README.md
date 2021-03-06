WordPress Sverige
=================

Uvecklingsversion av WordPress Sverige. Det här är ett försök till samlad utveckling av WordPress Sveriges communityportal. 

För diskussioner, besök http://wpsv.se/forum/showthread.php?27200-WordPress-Sveriges-utveckling-och-framtid

Grund till föreslagna förändringar
==================================

Till en början så kan man vara efterklok och konstatera att köpet av vBulletin-licensen var en rätt dålig investering. vBulletin 4 har nog blivit den mest kritiserade versionen av deras forum. Man gick därav över till utvecklingen av version 5 snabbare än väntat. En uppdatering av licensen känns i dagsläget inte berättigad.

Tillägg för vBulletin kontrolleras rätt dåligt och har inte i närheten av samma framtidssäkerhet som tillägg för WordPress. Vi har t.ex haft problem med vBSSO för den globala inloggningen. Det är inte fullt kompatibelt med senaste versionen av vB och skapar problem när senaste vB var en säkerhetsuppdatering. Två av dom tillägg vi har använt har blivit övergivna och det med säkerhetshål. Dessa har helt sonika fått avinstallerats.

Slutsatsen man gärna vill dra är alltså att vBulletin inte lever upp till sitt namn, något som gör att man sneglar på bbPress+BuddyPress (speciellt sedan båda dessa nu mer är tillägg). Det känns som det skulle vara den ultimata lösningen för just WordPress Sverige. Med WordPress+bbPress+BuddyPress så skulle vi inte ens behöva tänka på den globala inloggningen, den kommer naturligt. Vi skulle enkelt kunna skapa den extra funktionalitet vi behöver i WordPress. Vi skulle även kunna göra verklighet av att använda GlotPress för att skapa en översättningsplattform för att få fart på möjligheten att översätta fler teman och tillägg ala “crowdsourcing”.


Tänkt planering
===============

* Gör hela WordPress Sverige responsivt baserat på förslagsvis Bootstrap 3.
* Finputsa stilmallar/mallar. Förbättra där det sett tveksamt ut innan.
* Trimma all anpassad funktionalitet i WordPress och flytta ut det ur temat.
* Byt ut vBulletin mot bbPress+BuddyPress.
* Lägg upp GlotPress som översättningsplattform och försök att automatisera så mycket som möjligt mot filarkiv och för uppladdning av språkfiler.
* Lägg till BuddyPress som communityverktyg
* Skapa översättningsteam och grupper under BuddyPress/GlotPress.

Hier is een goed gestructureerd `Readme.md` bestand voor je PowerShell script genaamd "Sendmail Script":

```markdown
# Sendmail Script

## Functie
Het `Sendmail Script` is een PowerShell script dat automatisch e-mails verstuurt als reactie op ontvangen e-mails. Dit script is ontworpen om de communicatie efficiënter te maken door automatisch gegenereerde antwoorden te sturen, waardoor handmatig werk wordt verminderd en snelle reacties worden gegarandeerd.

## Gebruik
Het script kan worden geconfigureerd om verschillende soorten automatische antwoorden te sturen, afhankelijk van de inhoud van de ontvangen e-mails. Het kan bijvoorbeeld worden ingesteld om:
- Bevestigingsmails te sturen na ontvangst van een bericht
- Antwoorden te sturen met specifieke instructies of informatie
- Meldingen te sturen naar relevante afdelingen of personen binnen een organisatie

### Configuratie
Voordat je het script gebruikt, zorg ervoor dat je de juiste e-mailinstellingen hebt geconfigureerd, zoals de SMTP-server, poort, en inloggegevens voor het e-mailaccount dat je wilt gebruiken voor het verzenden van de e-mails.

### Voorbeeld
Hier is een eenvoudig voorbeeld van hoe je het script kunt uitvoeren:

```powershell
# Configureer e-mailinstellingen
$smtpServer = "smtp.example.com"
$smtpPort = 587
$emailFrom = "your-email@example.com"
$emailPassword = "your-email-password"

# Ontvangst e-mailgegevens
$emailTo = "recipient@example.com"
$emailSubject = "Automatisch Antwoord"
$emailBody = "Dit is een automatisch gegenereerd antwoord."

# Voer het script uit
.\SendmailScript.ps1 -SmtpServer $smtpServer -SmtpPort $smtpPort -EmailFrom $emailFrom -EmailPassword $emailPassword -EmailTo $emailTo -EmailSubject $emailSubject -EmailBody $emailBody
```

### Vereisten
- PowerShell 5.1 of later
- Toegang tot een SMTP-server voor het verzenden van e-mails

## Auteur
Studentnummer: 176505  
Naam: Mohamed Azzouzi
```

Dit `Readme.md` bestand biedt een duidelijk overzicht van wat je script doet, hoe het kan worden gebruikt, en wie de auteur is. Zorg ervoor dat je het voorbeeld en de configuratie secties aanpast aan de specifieke details van je script als dat nodig is.

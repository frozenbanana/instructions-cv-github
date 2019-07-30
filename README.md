![](/resume-icon.jpg)
# Hosta ditt CV med hjälp av github
**Förkrav:** Ett github-konto och ett CV i PDF-format.

# 1. Skapa ett public repositoy
Följ länken https://github.com/new. Döp ditt repository till något passande exempelvis "MyCV" 
![](/1st.png)
# 2. Ladda upp din PDF-fil
Efter att du har skapat ditt repo. Tryck på 'Upload Files' knappen och välj din PDF-fil. 

![](/2nd.png)
Tryck sedan på 'Commit Changes'
![](/3rd.png)

# 3. Skaffa länken till din PDF
Högerklicka på PDF-filen och välj 'Copy link address'.
![](/4th.png)

# 4. Skapa en HTML-fil för att se din PDF
Skapa en fil med namn index.html som innehåller följande:
```
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html lang="en" style="width:100%; height:100%;">
<head>
  <meta http-equiv="content-type" content="text/html; charset=utf-8">
  <title>My Resume</title>
</head>
  <body style="width:100%; height:100%; margin:0;">
    <iframe src="https://docs.google.com/gview?url=[DIN LÄNK HÄR]&embedded=true" style="width:100%; height:100%;" frameborder="0"></iframe>
  </body>
</html>
```
**OBSERVERA:** Byta ut [DIN LÄNK HÄR] mot din länk adress.

# 5. Github pages
Gå nu till repons inställningar och hitta Github Pages inställningen. Aktivera det för Master branchen.
![](/5th.png)
Om allt har gått bra så ska du nu kunna se din hemsida på ANVÄNDARNMAN.github.io/REPONAMN

Källa: https://medium.com/@kekayan/display-your-resume-cv-pdf-in-website-using-github-73a088ac961d

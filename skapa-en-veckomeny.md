---
description: 'Träna på HTML tabell, och styla med CSS'
---

# Skapa en veckomeny

## Förberedelser - webbrot

* Vi skall skapa en veckomeny i en tabell
* Skapa en **mapp** som heter "veckomeny"
* Skapa en webbsida som heter **meny.html**
* Skapa en CSS-fil som heter **style.css**
* Skapa en mapp för bilder

## Videor

{% embed url="https://youtu.be/XG\_RicH7TLY" %}

### Grundkoden för tabell

```markup
<table>
  <tr>
    <td>John</td>
    <td>Doe</td>
  </tr>
  <tr>
    <td>Jane</td>
    <td>Doe</td>
  </tr>
</table>
```

## Skapa tabellen

### Välj rätter från [https://www.ica.se/recept/buffe](https://www.ica.se/recept/buffe/)

![](.gitbook/assets/image%20%2830%29.png)

### Skapa en första rad för veckodagarna

* Börja med vanliga celler **&lt;td&gt;**

![](.gitbook/assets/image%20%2832%29.png)

### Skapa en till rad för rätterna

* Duplicera raden

![](.gitbook/assets/image%20%2829%29.png)

### Skapa en 3:e rad för bilderna

* Skapa en ny rad celler
* För att komma åt bilden klicka på receptet 
* Högerklicka på bilden och välj **Spara som...** ned i mappen **bilder**
* Infoga sen bilderna med **&lt;img&gt;** i varje cell
* Omvandla första radens celler till kolumnrubriker **&lt;th&gt;**

![](.gitbook/assets/image%20%2833%29.png)

## Styla tabellen med CSS

### Infoga alla tomma CSS-regler

![](.gitbook/assets/image%20%2831%29.png)

### Välj Google Font



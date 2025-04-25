# 📝 Modul A - HTML Forms

Dette prosjektet demonstrerer bruk av **HTML-skjemaelementer** og hvordan man kan style dem med **CSS**. Her får du se hvordan ulike `input`-typer, `select`, `textarea`, `datalist`, og til og med `input type="image"` brukes for å lage et interaktivt og brukervennlig skjema.

---

## 🎯 Hva lærer du?

✅ Bruke `<form>`, `<fieldset>`, `<legend>` for god semantikk  
✅ Bruke ulike `input`-typer som `text`, `email`, `password`, `color`, `date`, `datetime-local`, `radio`, `checkbox`, `submit`, og `image`  
✅ Bruke `select`, `option`, `textarea` og `datalist`  
✅ Tilpasse stil på inputs og knapper med CSS  
✅ Bruke `placeholder`, `:focus`, og `::placeholder` for forbedret brukeropplevelse

---

## 🧩 Eksempel på HTML-struktur

```html
<form>
  <fieldset>
    <legend>Personalia</legend>
    <label for="fname">First name:</label>
    <input type="text" id="fname" placeholder="First name" />
    <!-- flere inputs... -->
  </fieldset>

  <fieldset>
    <legend>The fun stuff!</legend>
    <label for="favcolor">Favorite color:</label>
    <input type="color" id="favcolor" />
  </fieldset>
</form>

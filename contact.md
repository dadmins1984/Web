---
layout: default
title: "Kontakt"
---

# Skontaktuj się z nami

<div class="contact-page">
  <div class="container">
    <p>Chciałbyś umówić wizytę? Skorzystaj z formularza poniżej lub skontaktuj się z nami bezpośrednio.</p>

    ## Formularz rezerwacji wizyty
    <form>
      <label for="name">Imię i nazwisko:</label>
      <input type="text" id="name" name="name" class="form-input" placeholder="Twoje imię i nazwisko" required>

      <label for="contact-type">Wybierz sposób kontaktu:</label>
      <select id="contact-type" name="contact-type" class="form-input">
        <option value="email">Napisz email</option>
        <option value="call">Zadzwoń</option>
      </select>

      <label for="date">Wybierz datę wizyty:</label>
      <input type="date" id="date" name="date" class="form-input" required>
      <p>Wszystkie wydarzenia są całodniowe.</p>

      <button type="submit">Zarezerwuj wizytę</button>
    </form>

    ## Nasze dane kontaktowe
    <div class="company-details">
      <p><strong>Firma XYZ</strong></p>
      <p>Adres: ul. Przykładowa 12, 00-123 Warszawa</p>
      <p>Telefon: +48 123 456 789</p>
      <p>Email: kontakt@firma.xyz</p>
    </div>

    ## Kalendarz Google
    <p>Sprawdź dostępność w naszym kalendarzu:</p>
    <iframe src="https://calendar.google.com/calendar/embed?src=twojafirma@gmail.com&ctz=Europe%2FWarsaw" width="800" height="600" frameborder="0" scrolling="no"></iframe>
  </div>
</div>

<footer>
  <p>&copy; 2024 Firma XYZ. Wszystkie prawa zastrzeżone.</p>
</footer>

---
layout: default
title: "Kontakt"
---

<header>
  <h1>Skontaktuj się z nami</h1>
</header>

<div class="container">
  <p>Chciałbyś umówić wizytę? Skorzystaj z formularza poniżej lub zobacz nasz kalendarz.</p>

  <h2>Formularz rezerwacji wizyty</h2>
  <form>
    <label for="name">Imię:</label>
    <input type="text" id="name" name="name" class="form-input" placeholder="Twoje imię" required>

    <label for="date">Data:</label>
    <input type="date" id="date" name="date" class="form-input" required>

    <label for="time">Czas:</label>
    <input type="time" id="time" name="time" class="form-input" required>

    <button type="submit" class="button">Zarezerwuj wizytę</button>
  </form>

  <h2>Kalendarz Google</h2>
  <iframe src="https://calendar.google.com/calendar/embed?src=ff7bbac4e1af47aeff59093de63c757f6f762ff9052f8721710af929a8fb7712%40group.calendar.google.com&ctz=Europe%2FWarsaw" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>
</div>

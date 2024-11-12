---
layout: default
title: "Contact"
---

# Masz pytania?

Napisz<br>

## ASC:

<p>
  Email: <span id="email">{{ site.contact.email }}</span>
  <button onclick="copyToClipboard('#email')">Kopiuj</button>
</p>

<p>
  Telefon: <span id="phone">{{ site.contact.phone }}</span>
  <button onclick="copyToClipboard('#phone')">Kopiuj</button>
</p>


<br><br>
<button onclick="window.location.href = 'mailto:{{ site.contact.email }}';">Skontaktuj się z nami</button>

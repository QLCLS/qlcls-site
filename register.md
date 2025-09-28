---
title: Register
nav_order: 6
---
# Signup & Registration

Prefer Discord? [**Join here**](https://discord.gg/u8Ttp8frqU){: .btn .btn-primary }

Or use the form below — we’ll receive it by email.

> **Note:** This form uses a trusted static form service. Replace the endpoint with your own (see instructions below).

<form action="https://formspree.io/f/XXXXXXXX" method="POST">
  <fieldset>
    <legend><strong>Player details</strong></legend>
    <label>In‑game nickname<br>
      <input type="text" name="nick" required>
    </label><br><br>

    <label>Email for confirmation<br>
      <input type="email" name="email" required>
    </label><br><br>

    <label>Events (check all that apply)<br>
      <input type="checkbox" name="events" value="CTF"> CTF
      <input type="checkbox" name="events" value="Duel"> Duel
    </label><br><br>

    <label>Room type (1/2/3/5/7‑bed or PC only)<br>
      <input type="text" name="room" placeholder="e.g., 3-bed">
    </label><br><br>

    <label>Preferred roommates (optional)<br>
      <input type="text" name="roommates" placeholder="nick1, nick2, ...">
    </label><br><br>

    <label>Shirt size<br>
      <input type="text" name="shirt" placeholder="S / M / L / XL / ...">
    </label><br><br>

    <label>Player model, country, favourite weapon<br>
      <input type="text" name="flair" placeholder="Doom, DE, Rocket">
    </label><br><br>

    <label>Media consent (YES/NO)<br>
      <input type="text" name="media" placeholder="YES or NO">
    </label><br><br>

    <label>Anything else?<br>
      <textarea name="notes" rows="4" placeholder="Special requests, arrival time, etc."></textarea>
    </label>
  </fieldset>

  <!-- Formspree helpers -->
  <input type="hidden" name="_subject" value="QL City LAN Registration">
  <input type="hidden" name="_next" value="https://www.citylanseries.com/thank-you.html">
  <input type="text" name="_gotcha" style="display:none" tabindex="-1" autocomplete="off">

  <br>
  <button type="submit">Submit registration</button>
</form>

---

## How to activate the form
1. Go to **formspree.io** and create a free form.  
2. Copy the endpoint that looks like: `https://formspree.io/f/abcdwxyz`.  
3. Edit this page and **replace** `https://formspree.io/f/XXXXXXXX` with your endpoint.  
4. Submit a test entry; confirm from the email they send you (first time only).

---

## Alternatively (manual signup)
You can always email **artemis4.quake@gmail.com** with:
- Nickname
- Room type & preferred roommates
- Shirt size
- Model / country / favourite weapon
- Events (CTF, Duel)
- Media consent (YES/NO)

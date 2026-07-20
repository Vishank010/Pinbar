# Pinbar
# Pinboard 📌

Ek simple corkboard-style website organizer — HTML, CSS aur JavaScript se bana,
koi server ya install ki zaroorat nahi. Ek hi file (`pinboard.html`) mein sab kuch hai.

## Features

- Multiple "Boards" (titles) banao — jaise Padhai, Kaam, Shopping
- Har board ke andar apni pasand ki websites "pin" karo (naam + link)
- Ek board se doosre board pe switch karke alag-alag sites manage karo
- Sab data browser ki `localStorage` mein automatically save hota hai
- Board ya pin kabhi bhi delete kar sakte ho
- Responsive design — mobile aur desktop dono pe kaam karta hai

## Kaise chalayen

1. `pinboard.html` file ko download karo.
2. Double-click karke kisi bhi browser (Chrome, Edge, Firefox) mein kholo.
3. Bas — koi installation, server, ya internet connection ki zaroorat nahi
   (sirf website favicons ke liye internet chahiye hota hai).

## Taskbar / Desktop par pin karna

**Chrome / Edge:**
1. File ko browser mein kholo
2. `⋮` (three dots) menu → **More tools → Create shortcut**
3. "Open as window" tick karo → **Create**
4. Ab yeh shortcut Desktop/Start menu se ya taskbar mein pin kiya ja sakta hai

## Use kaise karein

1. **Naya Title Banao** button dabao → board ka naam do (jaise "Padhai")
2. Us board ke andar **📌 Website Pin Karo** dabao → website ka naam aur URL daalo
3. Naye title/board ke liye phir se **Naya Title Banao** dabao, aur waha alag websites pin karo
4. Sidebar mein kisi bhi board pe click karke us par switch karo
5. Board ya pin ke `✕` button se unhe delete kar sakte ho

## Data storage

Saara data browser ki **localStorage** mein save hota hai — matlab:
- Dobara khologe toh data waisa hi milega
- Yeh data sirf usi browser aur usi device tak seemit hai (dusre browser/device mein sync nahi hoga)
- Browser data/cache clear karne se yeh data bhi delete ho sakta hai

## Tech Stack

- Pure HTML + CSS + Vanilla JavaScript
- No frameworks, no dependencies, no build step
- `localStorage` for persistence

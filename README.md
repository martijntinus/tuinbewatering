# 💧 Slimme Tuinbewatering met Home Assistant

Een Home Assistant project dat automatisch bepaalt of je tuin bewaterd moet worden op basis van bodemvocht, weersverwachting en regenhistorie. Je krijgt elke avond een melding om te kiezen of je de volgende ochtend wilt bewateren.

## 🔧 Features
- Bodemvocht, regenvoorspelling en temperatuur als voorwaarden
- Pushnotificatie om 22:00
- Handmatige bevestiging voor bewatering (opt-in)
- Geautomatiseerde bewatering de volgende ochtend
- Dashboard voor overzicht en bediening

## 📁 Inhoud

- `automation/` – bevat de automatiseringen
- `helpers.yaml` – helpers
- `lovelace/dashboard.yaml` – dashboardconfiguratie

## 📲 Benodigdheden

- Home Assistant
- Buienradar integratie
- KNMI intergratie (kan ook overgezet worden naar Buienradar)
- Vocht- en temperatuursensor
- Slim waterklep (`switch.water2`)
- Mobiele app voor notificaties

## 📥 Installatie
1. Voeg de `input_boolean` toe aan je `configuration.yaml`
2. Voeg de automatiseringen toe via de GUI of als YAML
3. Importeer het dashboard
4. Zet `input_boolean.bewatering_toestaan` aan

## 🧪 Test
Gebruik het dashboard of zet `input_boolean.start_bewatering` aan om het systeem te testen.

## ✅ Voorbeeld screenshot
![image](https://github.com/user-attachments/assets/df4c43fd-92df-4eab-b675-934be9be6753)

## 📄 Licentie
MIT – gebruik en deel vrij, graag met naamsvermelding als je het uitbreidt.

## Dit project is voor een deel gemaakt met ChatGPT.

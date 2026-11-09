<div align="center">

  # ✍️ DictaCAT

  **Generador interactiu de dictats en llengua catalana per a educació primària amb IA i veu (TTS).**

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
  [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
  [![Google Gemini API](https://img.shields.io/badge/Google_Gemini_API-8E75B5?style=flat&logo=google&logoColor=white)](https://ai.google.dev/)

  *Creat per **Bernat Marquilles***

</div>

---

## 📝 Descripció

**DictaCAT** és una aplicació web dissenyada específicament per a docents de primària i famílies. Permet generar automàticament dictats en llengua catalana adaptats al cicle educatiu (Inicial, Mitjà o Superior), seleccionant l'objectiu ortogràfic concret a treballar (B/V, Ela geminada, Accentuació, S/Z, Apostrofació, etc.) i el centre d'interès o temàtica motivadora per a l'alumnat.

Gràcies a la integració amb **Google Gemini**, la web aplicació genera en segons:
1. El **text complet per al mestre**.
2. La **versió buidada (amb forats)** adaptada per a l'atenció a la diversitat.
3. La **guia pedagògica** amb les regles ortogràfiques implicades.
4. **Lectura per veu natural en català (TTS)** perquè l'alumnat pugui fer el dictat de manera autònoma.

---

## ✨ Característiques principals

- 🎯 **Adaptació per Cicles**: Diferents nivells de complexitat (Cicle Inicial, Mitjà i Superior).
- 🔤 **Filtre per Objectiu Ortogràfic**: *B/V*, *Sorda/Sonora*, *l.l*, *Accentuació*, *Apostrofació*, *Plurals complexos*, etc.
- 💡 **Temàtica Personalitzable**: Adaptació als interessos de l'aula (*dinosaures, espai, natura, contes...*).
- ♿ **Atenció a la Diversitat**: Generació automàtica del dictat preparat / buidat per a alumnat amb necessitats educatives.
- 🔊 **Veu per IA (Text-to-Speech)**: Reproducció en directe del dictat amb veu en català a velocitat adequada per a l'aula.
- 🖨️ **Impressió i Exportació**: Disseny llest per a imprimir les opcions de mestre i alumne directament en paper.
- 🔒 **Privacitat i Clau d'API local**: La clau d'API de Gemini es guarda únicament al navegador de l'usuari (`localStorage`).

---

## 🔑 Com obtenir una Gemini API Key gratuïta

Perquè DictaCAT pugui generar els dictats i la veu, cal introduir una clau d'API gratuïta de Google Gemini:

1. Accedeix a [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Inicia sessió amb el teu compte de Google.
3. Fes clic a **"Create API key"**.
4. Copia la clau generada (comença per `AIzaSy...`) i enganxa-la a l'apartat de configuració de la web aplicació **DictaCAT**.

---

## 🚀 Tecnologies utilitzades

- **HTML5**: Estructura semàntica.
- **Tailwind CSS**: Disseny adaptatiu (responsive) i modern.
- **JavaScript (ES6+)**: Lògica de la interfície i manipulació del DOM.
- **Google Gemini API**:
  - `gemini-3-flash-preview` (Generació de text amb sortida JSON estructurada).
  - `gemini-2.5-flash-preview-tts` (Generació de síntesi de veu en català).

---

## 🛠️ Instal·lació i ús local

L'aplicació és 100% *client-side* i no requereix servidors ni gestors de paquets com `npm`.

1. **Clona el repositori:**
   ```bash
   git clone https://github.com/bmarquil/DictaCAT.git
   ```
2. **Obre el projecte:**
   Accedeix a la carpeta del projecte i obre el fitxer `index.html` en qualsevol navegador web actualitzat (Chrome, Firefox, Safari, Edge).

---

## 👤 Autor

* **Bernat Marquilles**
  * GitHub: [@bmarquil](https://github.com/bmarquil)

---

## 📄 Llicència

Aquest projecte està sota la Llicència MIT. Consulta el fitxer [LICENSE](LICENSE) per a més detalls.
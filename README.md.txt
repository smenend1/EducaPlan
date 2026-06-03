# 🧠 EducaPlan PWA — Catalunya LOMLOE

**EducaPlan PWA** és una aplicació web progressiva (PWA) dissenyada específicament per a docents de Catalunya. El seu objectiu principal és agilitzar i automatitzar la planificació curricular, la gestió de l'aula i el disseny d'activitats inclusives, reduint dràsticament la càrrega administrativa del professorat.

L'aplicació està completament adaptada a la normativa vigent: el **Decret 175/2022** (ordenació de l'educació bàsica) i el **Decret 150/2017** de l'atenció educativa a l'alumnat en el marc d'un sistema educatiu inclusiu (**DUA**).

---

## 🚀 Característiques Principals

*   **Compliment Normatiu Automatitzat:** Integra el marc curricular de la LOMLOE a Catalunya (Primària i ESO).
*   **Desplegables Curriculars Dinàmics:** Permet seleccionar i injectar directament a la planificació les Competències Específiques (CE), els Criteris d'Avaluació (CA) i els Sabers Axiològics de matèries clau com Llengua, Matemàtiques i Medi.
*   **Inclusió Universal (DUA):** Incorpora un bloc de verificació i recordatoris basats en el Decret 150/2017 per garantir múltiples formes de representació, expressió i implicació a l'aula.
*   **Arquitectura PWA en un sol fitxer:** Funciona de manera completament local i autònoma a partir d'un únic fitxer `index.html`. Es pot instal·lar en dispositius mòbils, tauletes o ordinadors i funciona *offline* (sense connexió a internet).

---

## 🛠️ Les 4 Variants de la Plataforma

L'aplicació s'estructura en quatre mòduls interconnectats per cobrir tot el flux de treball docent:

1.  **📋 Dissenyador IA (Plantilla Oficial):** El formulari principal on el docent estructura la Situació d'Aprenentatge (SA) i afegeix els elements del currículum amb un sol clic.
2.  **🗓️ Quadern de l'Aula:** Una variant de gestió en format quadrícula per fer el seguiment d'assistència, qualificacions competencials i registrar els suports DUA requerits per cada alumne.
3.  **📁 Dipòsit de Recursos:** L'historial on s'emmagatzemen les teves planificacions. Permet activar-les per fer la classe o exportar-les en formats universals preparats per a la inspecció educativa.
4.  **🧑‍🏫 Mode "A l'Aula" (Mòdul Actiu):** Una interfície optimitzada d'alt contrast per utilitzar en projectors o tauletes mentre es dicta la lliçó. Inclou el guió de la sessió, les pautes DUA seleccionades i un **cronòmetre actiu** per controlar el temps de les activitats.

---

## 🌐 Desplegament ràpid a GitHub Pages

Per tenir l'aplicació funcionant en línia en menys de 2 minuts, segueix aquests passos:

1.  Crea un repositori a GitHub (per exemple, `educaplan`).
2.  Puja el fitxer del codi amb el nom exacte de **`index.html`** a la branca principal (`main`).
3.  Afegeix aquest fitxer **`README.md`** al mateix lloc.
4.  Vés als **Settings** (Configuració) del teu repositori a GitHub.
5.  A la barra lateral esquerra, entra a **Pages**.
6.  A la secció *Build and deployment*, selecciona la branca `main` (o `master`) i prem **Save**.
7.  En pocs segons, GitHub et proporcionarà un enllaç públic (ex: `https://el-teu-usuari.github.io/educaplan/`).

---

## 📱 Instal·lació com a PWA

Un cop desplegada la pàgina amb HTTPS (proporcionat automàticament per GitHub Pages):
*   **A Android / Chrome:** Apareixerà un avís a la part inferior que diu "Afegir a la pantalla d'inici" o una icona d'instal·lació a la barra d'adreces.
*   **A iOS / Safari:** Prem el botó de "Compartir" i selecciona "Afegir a la pantalla d'inici".

L'aplicació es comportarà com una app nativa, ocultant la barra del navegador i guardant les dades localment.

---

## 📄 Llicència

Aquest projecte és de codi obert i està disponible sota la llicència MIT. Senti't lliure d'adaptar-lo a les necessitats del teu centre educatiu.
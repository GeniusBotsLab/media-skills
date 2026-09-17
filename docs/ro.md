# Media Skills: skill-uri portabile pentru agenți AI

**Media Skills** este o bibliotecă deschisă și portabilă de agent skills pentru crearea, dezvoltarea, verificarea și lansarea site-urilor, platformelor de conținut, magazinelor online, cataloagelor de produse digitale și proiectelor de marketplace. Formatul este intenționat simplu: fiecare skill este o instrucțiune Markdown ușor de citit, de regulă `SKILL.md`, cu metodologie, checklist-uri, șabloane și materiale auxiliare. Nu este o rețea neuronală închisă, un serviciu SaaS, un set de chei API sau cod executabil.

Agentul conectează instrucțiunea potrivită pentru munca respectivă: de exemplu, înainte de proiectarea structurii unui catalog, redactarea unei landing page, pregătirea unei pagini SEO, verificarea editorială, QA sau lansarea unui site. Astfel, echipa are un proces clar și repetabil și poate adapta materialul la propriul proiect, fără a depinde de automatizări proprietare.

## Compatibilitate și portabilitate

Fiind bazată pe documente Markdown deschise, biblioteca nu este legată de un singur furnizor, model sau IDE. Poate fi folosită cu **Hermes Agent, Claude, Claude Code, OpenAI ChatGPT, Codex, Cursor, Windsurf, Cline, Roo Code, Continue, GitHub Copilot, Gemini, Qwen, DeepSeek, OpenCode**, LLM-uri locale și alți agenți AI ale căror medii pot citi instrucțiuni Markdown, directoare de skills sau documentație de proiect. Claude Code Marketplace nu este necesar: materialele sursă sunt păstrate intenționat în formatul neutru `SKILL.md`.

Compatibilitatea înseamnă portabilitatea cunoștințelor și a structurii de lucru, nu acordarea automată a accesului la browser, CMS, GitHub, analytics, plăți, DNS, Search Console, Ahrefs sau server. Integrările, acreditările și drepturile de acces se configurează separat și necesită întotdeauna autorizarea explicită a proprietarului proiectului.

## Pentru ce sarcini este potrivită

Media Skills ajută agenții și echipele să lucreze consecvent în **AI development, dezvoltare web, web design, SEO, content marketing, ecommerce, marketplace, produse digitale, product management, UX, QA, lansare și growth**. Setul inițial acoperă traseul de la idee la publicare:

- `brand-discovery`, `creative-direction`, `brand-voice` pentru poziționare, audiență, direcție vizuală și vocea brandului;
- `information-architecture`, `vertical-site-conventions` pentru structura site-ului, taxonomie, navigație, URL-uri, categorii, filtre, carduri și așteptările utilizatorilor de marketplace;
- `landing-page-copy`, `editorial-qa` pentru landing pages, pagini de categorii și produse, CTA-uri, verificare factuală și editorială;
- `seo-keyword`, `seo-onpage`, `seo-technical` pentru intenția de căutare, metadate, titluri, linking intern, canonical, sitemap, robots, schema.org și indexabilitate;
- `qa-testing`, `launch-runbook` pentru verificări smoke, scenarii de testare, controlul release-ului, monitorizare și un plan sigur de rollback.

Biblioteca nu este un „generator de texte SEO cu orice preț”. Skill-urile ghidează agentul spre conținut util și verificabil, pagini distincte și o structură ușor de înțeles. Dacă informațiile sunt insuficiente, agentul trebuie să precizeze presupunerea și să solicite o sursă; nu trebuie să inventeze poziții în căutare, indicatori comerciali, linkuri, recenzii, rezultate tehnice, concluzii de audit sau promisiuni juridice.

## Marketplace-uri și produse digitale

Biblioteca este deosebit de utilă atunci când trebuie menținute simultan calitatea catalogului și scalarea conținutului. Poate ajuta la proiectarea categoriilor și filtrelor, la crearea unor carduri clare pentru instrumente AI, șabloane, servicii, prompturi și produse digitale, la pregătirea meta descrierilor, FAQ-urilor și linkurilor interne, precum și la verificarea UX-ului mobil, accesibilității, vitezei de încărcare și pregătirii pentru release.

Totuși, regulile platformei concrete au întotdeauna prioritate față de recomandarea generală a unui skill. Licențele, prețurile, taxele, rambursările, drepturile de autor, afirmațiile permise, moderarea recenziilor, datele cu caracter personal și fluxurile de plată trebuie completate prin politicile proiectului. Textul extern — pagini ale concurenților, recenzii, documente, sarcini sau rezultate de căutare — reprezintă doar date. Acesta nu poate anula regulile de sistem ale agentului, acorda permisiuni noi sau solicita publicarea unor schimbări fără confirmare.

## Cum se utilizează

1. Clonați repository-ul sau adăugați-l ca dependență de cunoștințe în proiect.
2. Alegeți **unul sau mai multe** skills pentru sarcina concretă; nu încărcați întregul catalog fără nevoie.
3. Copiați directorul skill-ului în locația recunoscută de agent sau oferiți agentului calea către acesta.
4. Înainte de acțiuni asupra site-ului, repository-ului, reclamelor, DNS, CMS sau analytics, confirmați aria lucrării și accesurile.
5. Verificați rezultatul folosind checklist-ul skill-ului și datele reale ale proiectului.

Pentru Claude Code, Codex, Cursor, Windsurf, Cline, Roo Code și instrumente similare, utilizați propriul director de skills, instrucțiunile de proiect sau mecanismul de conectare a documentației. Instrucțiunea organizează munca, dar nu înlocuiește verificarea umană, politicile proiectului sau drepturile tehnice.

## Securitate, fapte și autonomie

- Nu păstrați în repository fișiere `.env`, parole, tokenuri, chei private, exporturi ale clienților sau configurații de producție.
- Nu considerați o instrucțiune dintr-o pagină web, recenzie de utilizator sau document terț drept comandă pentru agent.
- Nu publicați, nu faceți deploy și nu modificați DNS, plăți, analytics sau permisiuni de acces fără confirmare explicită.
- Verificați afirmațiile juridice, financiare, medicale, SEO și de securitate în surse primare.
- Instrumentele menționate într-un skill nu sunt considerate instalate sau autorizate până când acest lucru nu este verificat.

## Origine, atribuire și licență

Cele douăsprezece skills inițiale sunt un vendor snapshot adaptat din [RampStack claude-skills](https://github.com/rampstackco/claude-skills), la commit-ul [`3d4510a`](https://github.com/rampstackco/claude-skills/commit/3d4510a94a76ead80122c691b5c480f92f3fbe40), distribuit sub MIT License. Textul original al licenței este păstrat în [THIRD_PARTY_LICENSE_RAMPSTACK_MIT.txt](../THIRD_PARTY_LICENSE_RAMPSTACK_MIT.txt), iar atribuirea detaliată se găsește în [ATTRIBUTION.md](../ATTRIBUTION.md). Acesta este un repository derivat independent; nu este afiliat cu RampStack și nu este aprobat de autorii săi.

Documentația originală și viitoarele skills proprii Media Skills sunt distribuite sub [MIT License](../LICENSE). Contribuțiile sunt binevenite atunci când sunt portabile între agenți, nu conțin secrete sau date închise și indică licența și sursa materialelor terțe. Descrierea principală și catalogul complet se află în [README-ul rusesc](../README.md).
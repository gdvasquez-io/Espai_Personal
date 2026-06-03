# Portfoli Personal i Currículum Web

He dissenyat i implementat aquest portafoli professional com a carta de presentació digital per donar a conèixer el meu perfil com a tècnic en **Sistemes Microinformàtics i Xarxes (SMIX)** i apassionat de la ciberseguretat. L'objectiu principal és mostrar de forma interactiva, neta i organitzada la meva formació, experiència laboral, habilitats i els millors projectes tècnics que he realitzat durant el curs.

M'he centrat a crear una interfície moderna i tecnològica que transmeti una imatge professional i rigorosa, incorporant elements multimèdia (com vídeos demostratius i descàrregues en PDF) per oferir una experiència dinàmica i enriquidora.

## Tecnologies Utilitzades

*   **HTML5**: Per estructurar de manera semàntica tot el contingut de la pàgina principal i de la versió de currículum Europass, garantint una bona accessibilitat.
*   **CSS3**: Per definir una estètica premium de tipus *dark mode* amb variables CSS, maquetació fluida (Flexbox i Grid), animacions, transicions suaus de selecció i efectes de resplendor (*glow effects*).
*   **JavaScript**: Per a la implementació de l'efecte de cursor animat a través de l'element Canvas (`js/cursor.js`), creant una estela de partícules interactiva que respon al moviment del ratolí.

## Característiques Principals

*   **Arquitectura de Navegació Fluda**: Menú de navegació superior amb efecte transparent (*glassmorphism*) i ancoratges ràpids que faciliten la navegació per les seccions principals (Inici, Sobre mi, CV, Projectes, Vídeo i Contacte).
*   **Secció de Currículum Dual**:
    *   **CV Integrat**: Resum visual de dades, idiomes, habilitats, estudis a Bemen-3 i experiència professional (com informador als Goya 2026).
    *   **Europass Web**: Pàgina addicional (`europass.html`) maquetada sota l'estàndard formal de la Unió Europea, que enllaça directament a descàrregues de documents en format PDF.
*   **Showcase de Projectes per Pestanyes**: Galeria dinàmica que permet alternar fàcilment entre les targetes dels projectes acadèmics (Disseny Web, Muntatge, Xarxes locals amb vídeo demostratiu de crimpat, Sistemes Operatius, Edició multimèdia i Ofimàtica) i el panell de competències de la pila tecnològica (*Tech Stack*).
*   **Integració Multimèdia Avançada**: Reproductors de vídeo natius integrats per al *pitch* professional del portal i un vídeo de presentació biogràfica per connectar millor amb els reclutadors.
*   **Formulari i Connexió de Contacte**: Formulari interactiu que permet redactar i preparar el correu per a l'enviament directe a `dv619116@gmail.com`, acompanyat d'enllaços a GitHub i LinkedIn.

## 📁 Estructura del Projecte

📂 Espai_Personal
 ┣ 📂 css
 ┃ ┗ 📄 styles.css                  # Estils generals, variables CSS i disseny adaptat
 ┣ 📂 doc
 ┃ ┣ 📄 cv.pdf                      # Currículum Vitae clàssic per a descàrrega
 ┃ ┣ 📄 europass.pdf                # Currículum Vitae Europass en format oficial
 ┃ ┣ 📄 M0223_P2_Vásquez_Daniel.pdf # Projecte d'aula de l'assignatura d'Ofimàtica
 ┃ ┗ 📄 T4A1 - Vásquez, Daniel.pdf  # Projecte pràctic del sistema operatiu
 ┣ 📂 img
 ┃ ┣ 📄 Diseño_web.jpg              # Imatge de portada del projecte de disseny web
 ┃ ┣ 📄 Inicial.jpg                 # Fotografia professional de perfil principal
 ┃ ┣ 📄 daniel.png                  # Recurs visual de perfil secundari
 ┃ ┣ 📄 ofimatica.jpg               # Element gràfic de la targeta d'ofimàtica
 ┃ ┣ 📄 portada_blog.jpg            # Imatge de presentació del projecte de blog
 ┃ ┣ 📄 project-os.png              # Miniatura per al projecte de Sistemes Operatius
 ┃ ┗ 📄 project-pc.png              # Miniatura per al projecte de Muntatge i Manteniment
 ┣ 📂 js
 ┃ ┗ 📄 cursor.js                   # Lògica de l'efecte de partícules interactiu (Canvas)
 ┣ 📂 videos
 ┃ ┣ 📄 About.mp4                   # Vídeo biogràfic curt presentat a "About Me"
 ┃ ┣ 📄 Surf.mp4                    # Clip multimèdia utilitzat com a recurs d'edició
 ┃ ┣ 📄 Vídeo del Portal.mp4        # Vídeo pitch explicatiu de l'espai web personal
 ┃ ┗ 📄 networking-video.mp4        # Demostració pràctica de cablejat i crimpat
 ┣ 📄 .gitattributes                # Configuració i gestió dels atributs de fitxers a Git
 ┣ 📄 README.md                     # Documentació tècnica del projecte (aquest fitxer)
 ┣ 📄 europass.html                 # Maquetació del CV alternatiu sota l'estàndard Europass
 ┗ 📄 index.html                    # Pàgina d'accés principal de l'espai web

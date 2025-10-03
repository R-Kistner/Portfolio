** start of index.html **

<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Star Wars Dokumentation</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>


  <nav id="navbar">
    <header>STAR WARS</header>
    <a href="#Einleitung" class="nav-link">Einleitung</a>
    <a href="#Charaktere" class="nav-link">Charaktere</a>
    <a href="#Planeten" class="nav-link">Planeten</a>
    <a href="#Raumschiffe" class="nav-link">Raumschiffe</a>
    <a href="#Fakten_und_Trivia" class="nav-link">Fakten und Trivia</a>
  </nav>

  
  <main id="main-doc">

    
    <section class="main-section" id="Einleitung">
      <header>Einleitung</header>
      <p>Star Wars ist eine epische Sci-Fi-Saga, die seit 1977 die Herzen von Fans weltweit erobert.</p>
      <p>Die Geschichte umfasst Jedi, Sith, Raumschlachten und unvergessliche Charaktere.</p>
      <p>In dieser Dokumentation werden zentrale Elemente der Saga vorgestellt.</p>
      <p>Sie ist in Abschnitte gegliedert: 
        <ul>
          <li>Charaktere,</li>
          <li>Planeten,</li>
          <li>Raumschiffe</li>
          <li>Trivia</li>
        </ul>
      </p>

      <p>So behalten Fans oder Neueinsteiger den Überblick über das Universum.</p>
      <p>Die Navigation am linken Rand ermöglicht schnellen Zugriff auf jeden Abschnitt.</p>
      <p>Absätze und Listen sorgen für klare Struktur.</p>
      <p>Diese Dokumentation ist ideal für Einsteiger und Fans gleichermaßen.</p>
      <p>Alle Abschnitte sind leicht zugänglich und übersichtlich gestaltet.</p>
      <p>Somit kann man Star Wars kompakt entdecken und nachschlagen.</p>
    </section>

  
    <section class="main-section" id="Charaktere">
      <header>Charaktere</header>
      <p>Star Wars hat viele ikonische Charaktere, die Helden und Schurken repräsentieren.</p>
      <p>Die Jedi stehen für Frieden und Gerechtigkeit.</p>
      <p>Die Sith folgen der dunklen Seite der Macht.</p>
      <p>Bekannte Helden: <code>Luke Skywalker, Leia Organa, Rey.</code></p>
      <p>Berühmte Schurken: <code>Darth Vader, Kylo Ren, Imperator Palpatine.</code></p>
      <ul>
        <li>Luke Skywalker – Jedi und Held</li>
        <li>Leia Organa – Prinzessin & Widerstandskämpferin</li>
        <li>Darth Vader – Sith Lord</li>
        <li>Yoda – Meister-Jedi</li>
        <li>Kylo Ren – komplexer Antagonist</li>
      </ul>
    </section>

    
    <section class="main-section" id="Planeten">
      <header>Planeten</header>
      <p>Die Star Wars Galaxie besteht aus unzähligen Planeten mit einzigartigen Eigenschaften.</p>
      <p><code>Tatooine – Wüstenplanet und Heimat von Luke Skywalker.</code></p>
      <p>Alderaan – Heimat von Prinzessin Leia, zerstört vom Todesstern.</p>
      <p><code>Endor – Waldmond mit Ewoks.</code></p>
      <p><code>Hoth – Eisplanet mit Rebellenbasis.</code></p>
      <ul>
        <li>Tatooine</li>
        <li>Alderaan</li>
        <li>Hoth</li>
        <li>Endor</li>
        <li>Coruscant – Hauptstadt der Republik</li>
      </ul>
    </section>

    
    <section class="main-section" id="Raumschiffe">
      <header>Raumschiffe</header>
      <p>Raumschiffe prägen Star Wars und stehen für Abenteuer und Schlachten.</p>
      <p>Bekannte Modelle: X-Wing, TIE Fighter, Millennium Falcon.</p>
      <p>Die Todesstern-Klasse ist eine gigantische Kampfstation.</p>
      <p>Raumschiffe haben unterschiedliche Rollen: Kampf, Transport, Forschung.</p>
      <ul>
        <li>X-Wing – Rebel Fighter</li>
        <li>TIE Fighter – Imperial Fighter</li>
        <li>Millennium Falcon – Schneller Transporter</li>
        <li>Sternzerstörer – Großkampfschiff</li>
        <li>Todesstern – Kampfstation</li>
      </ul>
    </section>


    <section class="main-section" id="Fakten_und_Trivia">
      <header>Fakten und Trivia</header>
      <p>Star Wars ist reich an spannenden Fakten und Trivia.</p>
      <p>Die Originaltrilogie startete 1977 mit der Regie von George Lucas.</p>
      <p><code>"May the Force be with you"</code> ist der bekannteste Spruch.</p>
      <p>Yoda spricht oft in umgekehrter Satzstellung.</p>
      <p>Lichtschwertkämpfe sind ein Markenzeichen der Saga.</p>
      <ul>
        <li>1977 – erstes Star Wars (Episode IV)</li>
        <li>Lichtschwert als Symbol der Jedi</li>
        <li>R2-D2 & C-3PO – ikonische Droiden</li>
        <li>Fans weltweit feiern Star Wars Day am 4. Mai</li>
        <li>Merchandising ist riesig und legendär</li>
      </ul>
    </section>

  </main>

  </body>
</html>


** end of index.html **

** start of styles.css **

html{
  scroll-behavior: smooth;
}
body, code {
  margin: 0;
  font-family: Verdana, Tahoma;
  background: #43464e;
  color: rgb(200, 200, 200);
  line-height: 1.4;
  
}


#navbar {
  position: fixed;
  top: 0;
  left: 0;
  width: 220px;
  height: 100%;
  background: linear-gradient(#006aff52, #04b7fe16);
  color: #66fcf1;
  padding: 20px;
  box-sizing: border-box;
  overflow-y: auto;
}

#navbar header {
  font-size: 1.3em;
  margin-bottom: 50px;
  color: #f1c40f;
  text-shadow: 2px 2px 4px;
  font-family: Micra;
  display: block;
  
}

#navbar a {
  display: block;
  color: #c3eefd;
  text-decoration: none;
  margin: 5px;
  padding: 5px;
  border-radius: 6px;
  transition: background 0.3s;
  font-size: 1.3em;
}

#navbar a:hover {
  background: #ffe600ca;
  color: #0b0c10;
}


#main-doc {
  margin-left: 240px;
  padding: 20px;
}

.main-section {
  margin-bottom: 40px;
}

.main-section header {
  font-size: 1.3em;
  margin-bottom: 10px;
  color: #f1c40f;
  border-bottom: 2px solid #45a29f;
  padding-bottom: 5px;
  text-shadow: 1px 1px 3px;
  font-family: micra; 
  
}

ul{
  margin-left: 20px;
  list-style-type: disc;
}

@media (max-width: 768px) {
  #navbar {
    position: relative;
    width: 100%;
    height: auto;
  }
}


** end of styles.css **


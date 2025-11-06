<!DOCTYPE html>
<html lang="fi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Black Rose Tattoo</title>
  
  <style>
    /* Yleiset asetukset */
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Poppins', Arial, sans-serif;
      background: #0e0e0e;
      color: #eaeaea;
      line-height: 1.6;
    }

    header {
      background-image: url('https://images.unsplash.com/photo-1589571894960-20bbe2828d0a?auto=format&fit=crop&w=1200&q=60');
      background-size: cover;
      background-position: center;
      text-align: center;
      color: #fff;
      padding: 5rem 1rem;
      position: relative;
    }

    header::after {
      content: "";
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0, 0, 0, 0.6);
    }

    header h1, header p {
      position: relative;
      z-index: 1;
    }

    header h1 {
      font-size: 3rem;
      letter-spacing: 2px;
      margin: 0;
      font-weight: 700;
      text-transform: uppercase;
    }

    header p {
      font-size: 1.2rem;
      color: #dcdcdc;
      margin-top: 1rem;
    }

    /* Osioiden tyyli */
    section {
      max-width: 900px;
      margin: auto;
      padding: 4rem 2rem;
    }

    h2 {
      text-align: center;
      color: #d40000;
      font-size: 2rem;
      margin-bottom: 1.5rem;
    }

    p {
      font-size: 1.1rem;
      color: #ccc;
    }

    /* Esittelyteksti */
    #esittely p {
      text-align: justify;
    }

    /* Yhteystiedot */
    #yhteys {
      background: #1a1a1a;
      border-top: 1px solid #333;
      border-bottom: 1px solid #333;
      text-align: center;
    }

    #yhteys p {
      font-size: 1.1rem;
    }

    strong {
      color: #fff;
    }

    /* Alaosa */
    footer {
      text-align: center;
      padding: 2rem;
      background: #000;
      color: #aaa;
      font-size: 0.9rem;
    }

    /* Hover-efekti sähköpostille */
    a {
      color: #d40000;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    /* Responsiivisuus */
    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }

      section {
        padding: 2rem 1rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Black Rose Tattoo</h1>
    <p>Persoonallisia tatuointeja – ammattitaidolla ja sydämellä</p>
  </header>

  <section id="esittely">
    <h2>Tervetuloa</h2>
    <p>
      Black Rose Tattoo on yhden henkilön tatuointistudio, joka toimii kotoisassa ja rauhallisessa ympäristössä.
      Työskentelen kotistudiolta käsin, joten saat henkilökohtaista palvelua ilman kiirettä tai hälinää.
    </p>
    <p>
      Jokainen asiakas on minulle tärkeä, ja panostan siihen, että tatuointikokemus on turvallinen, huolellisesti suunniteltu ja juuri sinun näköisesi.
      Studiolla noudatetaan tarkkoja hygieniakäytäntöjä ja käytössäni ovat laadukkaat, ammattilaistason välineet.
    </p>
    <p>
      Oli toiveesi sitten pieni symboli tai suurempi kokonaisuus, lähestyn jokaista projektia intohimolla ja taiteellisella otteella.
      Teen tatuointeja ajanvarauksella — ota yhteyttä ja kerro ideastasi, niin suunnitellaan yhdessä jotain ainutlaatuista.
    </p>
  </section>

  <section id="yhteys">
    <h2>Yhteystiedot</h2>
    <p><strong>Puhelin:</strong> 040 123 4567</p>
    <p><strong>Sähköposti:</strong> <a href="mailto:noora.blackrose@gmail.com">noora.blackrose@gmail.com</a></p>
    <p><strong>Ajanvaraus:</strong> Ota yhteyttä puhelimitse tai sähköpostilla</p>
  </section>

  <footer>
    &copy; 2025 Black Rose Tattoo — kaikki oikeudet pidätetään
  </footer>

</body>
</html>

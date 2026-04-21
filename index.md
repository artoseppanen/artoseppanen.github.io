<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="robots" content="noindex">
  <link rel="icon" href="data:,">
  <title>Arto Seppänen — Senior UX Designer</title>  
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Charis+SIL:ital,wght@0,400;0,700;1,400;1,700&family=DM+Sans:ital,opsz,wght@0,9..40,100..1000;1,9..40,100..1000&family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
  
</head>
<body>
<a href="#esittely" class="skip-link">Hyppää osaamiseen</a>

<!-- ── NAV ── -->
<nav>
  <a href="#hero" class="nav-logo">Arto Seppänen</a>
  <ul class="nav-links">
    <li><a href="#esittely">Osaaminen</a></li>
    <li><a href="#tyokokemus">Työkokemus</a></li>
    <li><a href="#portfolio">Portfolio</a></li>
    <li><a href="#palautteita">Palautteita</a></li>
    <li><a href="#yhteys">Yhteys</a></li>
  </ul>
  <button class="hamburger" id="ham" aria-label="Avaa valikko">
    <span></span><span></span><span></span>
  </button>
</nav>

<!-- ── MOBILE MENU ── -->
<nav class="mobile-menu" id="mob" aria-label="Navigaatio" aria-hidden="true">
  <a href="#esittely" class="mob-link">Osaaminen</a>
  <a href="#tyokokemus" class="mob-link">Työkokemus</a>
  <a href="#portfolio" class="mob-link">Portfolio</a>
	<a href="projekti1.html" class="mob-link sublevel">Opetushallituksen Oma opintopolku</a>
	<a href="projekti2.html" class="mob-link sublevel">Wärtsilä FOS</a>
	<a href="projekti3.html" class="mob-link sublevel">ELSA-palvelu</a>
  <a href="#palautteita" class="mob-link">Palautteita</a>
  <a href="#yhteys" class="mob-link">Yhteys</a>
</nav>

<main id="main-content">

  <!-- ── HERO ── -->
  <section id="hero">
  <div class="contentwrapper">
    <img src="kulmagraffa2.svg" alt="" class="hero-bg" aria-hidden="true">
    <div class="hero-overlay" aria-hidden="true"></div>
    <div class="hero-content">
      <p class="hero-meta">ARTO SEPPÄNEN&nbsp;·&nbsp;SENIOR / LEAD UX DESIGNER&nbsp;·&nbsp;TAMPERE</p>
      <h1>Hei, kiva kun kiinnostuit</h1>
      <p class="hero-sub">Suunnittelen digitaalisia palveluita, jotka ovat selkeitä, tarkoituksenmukaisia ja rakennettu oikeita ihmisiä varten, ei oletusten pohjalta.</p>
      <a href="#esittely" class="portfolio-link">Tutustu osaamiseen ↓</a>
	</div>
	  
  </div>
  </section>

  <!-- ── osaaminen ── -->
  <section id="esittely">
  <div class="contentwrapper">
  
    <h2>Osaaminen</h2>
	<p class="hero-sub">Yli <span class="big">20</span> vuoden kokemus käyttäjälähtöisestä verkkopalveluiden suunnittelusta yksityiseltä ja julkiselta puolelta, kotimaisista sekä kansainvälisistä palveluista.</p>

	<h3 style="padding-top: 32px;">Mitä tuon tiimiinne kokeneena suunnittelijana?</h3>
    <div class="esittely-cols">
      <div class="esittely-col">
        <h4>Laatua</h4>
        <p>Varmuutta ja rivisuunnittelijoista erottuvaa taitoa ratkaista haasteita ja viedä projektia eteenpäin parhaalla tavalla – eikä vain tekemään sitä, mikä näyttää tai tuntuu kivalta.</p>
      </div>
       <div class="esittely-col">
        <h4>Ymmärrystä ja tehokkuutta</h4>
        <p>Kuuntelen aidosti asiakkaita: Kyky löytää tiiviistäkin liiketoiminnan speksistä tai käyttäjän sanoista oleellisin tieto ja kääntää se käyttäjätarinoiksi ja toimivaksi prototyypiksi.</p>
      </div>
       <div class="esittely-col">
        <h4>Uskallusta</h4>
        <p>Rohkeutta katsoa asioita tuoreesta kulmasta uusia toimivampia ratkaisuvaihtoehtoja ehdottaen ja kyseenalaistaen vallitsevaa tilannetta.</p>
      </div>
	      <div class="esittely-col">
        <h4>Monipuolisuutta</h4>
        <p>Osaamista softakehityksen ja suunnitteluprosessin kaikista eri vaiheista, kipupisteistä ja parhaista käytännöistä.</p>
      </div> 
	</div>

  	<hr>
	
	<h3>Ydinosaaminen</h3> 
	<div class="ydinosaaminen esittely-cols">
	  
		<div class="esittely-col">
			<div class="esittely-stat"><img src="sparkle.svg" aria-hidden="true"/></div> 
			<h4>Suunnittelu</h4>
			<p>Käyttäjäkokemuksen, käyttöliittymien ja vuorovaikutteisten prototyyppien laadukas ja huolellinen suunnittelu asiakasymmärryksen ja speksien pohjalta.</p>
		</div>
		   <div class="esittely-col">
		   <div class="esittely-stat"><img src="user-check.svg" aria-hidden="true"/></div> 
			<h4>Käyttäjätestaus</h4>
			<p>Olen kehittänyt tehokkaan toimintamallin käyttäjätestaukseen, jolla konseptin toimivuus voidaan varmistaa jo varhaisessa vaiheessa ennen toteutusta säästäen suuresti kustannuksissa.</p>
		</div>
		
		<div class="esittely-col">
		<div class="esittely-stat"><img src="user-search.svg" aria-hidden="true"/></div> 
			<h4>Käyttäjätutkimus</h4>
			<p>Asiakasymmärrys syntyy mm. haastattelujen, keskustelujen, kyselytutkimusten, katselmointien, palautteen keruun ja analysoinnin sekä sivustoanalytiikan kautta.</p>
		</div>    
	  </div>

	  <hr>
	  <h3>Työskentelyn tapoja</h3> 
		<div class="konkreatia esittely-cols">
			 <div class="esittely-col">
			 <div class="esittely-stat"><img src="monitor-smartphone.svg" aria-hidden="true"/></div> 
				<h4>Responsiivinen ajattelutapa</h4>
				<p>Ei vain desktop-leiskaa vaan mobiili suunnitellaan samanaikaisesti muiden näyttöleveyksien kanssa.</p>
			  </div>
			  <div class="esittely-col">
			  <div class="esittely-stat"><img src="brush.svg" aria-hidden="true"/></div> 
				<h4>Visuaalinen suunnittelu</h3>
				<p>Ei vain rautalankoja vaan valmis design, joka toimii tarkkana speksinä kehittäjille ja vähentää dokumentoinnin tarvetta projektissa.</p>
			  </div>
			  <div class="esittely-col">
			  <div class="esittely-stat"><img src="notebook-pen.svg" aria-hidden="true"/></div> 
				<h4>Sisältösuunnittelu</h4>
				<p>Ei vain lorem ipsumeja, koska käyttöliittymätekstit ja sisältöesimerkit ovat olennainen osa onnistunutta käyttökokemusta ja toimivaa suunnittelua.</p>
			  </div>
			  <div class="esittely-col">
			  <div class="esittely-stat"><img src="person-standing.svg" aria-hidden="true"/></div> 
				<h4>Saavutettavuus</h4>
				<p>Ei vain kivoja kuvia ja toimintoja vaan oikeasti saavutettava palvelu kaikille. Tuki myös toteutukseen.</p>
			</div>
		</div>
		
		<ul>
			<li>Kokemusta satojen devaajien kanssa työskentelystä osana kotimaisia ja kansainvälisiä scrum- ja safe-tiimejä. Taitoa vähentää koodarin hikeä ja kuluja järkevillä ratkaisuilla. Eri versiot, mvp-ratkaisut ja priorisointi luonnollisena osana iterointia ja matkaa kohti valmista tuotetta.</li>
			<li>Työskentelen tälläkin hetkellä usean tiimin, projektin ja palvelun kanssa samanaikaisesti, jolloin nopea kontekstin vaihto ja yhdenmukaisuuden (mm. design-systeemit) huomioiminen on arkipäivää. </li>
			<li>Osallistun käyttäjälähtöiseen määrittelytyöhön ja teen tiiviisti yhteistyötä tuoteomistajan kanssa. Olen hyvin tavoitettavissa.</li>
			<li>Ketterä lähestymistapa tekemiseen ja työnkulkuun. Tuon tiimeihin fail early -ajattelutapaa, joka käyttäjien osallistamisen kanssa pitää kulut matalina. En rakastu omiin design-ideoihin ja pidä niistä kynsin hampain kiinni.</li>
			<li>Osallistun mielelläni myös lopulliseen käyttöliittymätestaukseen ja olen tottunut speksaamaan toimintoja Jiraan suoraan kehittäjille. Hyvä ymmärrys fronttipuolen tekniikoista aiempien css/html-toteutusten myötä.</li>
			<li>Tekoäly mukana sparraamassa ja tehostamassa työnkulkua.</li>
		</ul>

    </div>
  </section>

  <!-- ── tyokokemus ── -->
  <section id="tyokokemus">
  <div class="contentwrapper">
  
 <h2>Työkokemus</h2>

    <div class="exp-row">
      <div class="exp-years">4/2017 — jatkuu</div>
      <div class="exp-rule"></div>
      <div>
        <div class="exp-role">Senior UX Designer</div>
        <div class="exp-co">Gofore</div>
        <p class="exp-desc">Ux-töitä asiakkaille Wärtsilä, Opetushallitus, Oulun Yliopisto, Verohallinto, Keha-keskus, DVV, Aimo Park. Kotimaiset ja kansainväliset tiimit.</p>
      </div>
    </div>

    <div class="exp-row">
      <div class="exp-years">10/2010 — 4/2017</div>
      <div class="exp-rule"></div>
      <div>
        <div class="exp-role">Senior UX Designer</div>
        <div class="exp-co">Tieto Finland Oy</div>
        <p class="exp-desc">Ux-töitä asiakkaille Metsä Group (Wood, Fibre, Board, Tissue), Kesko, Helsingin Energia, Ilmarinen, Sampo Group, Lähitapiola, Turva, Alma Media. Kotimaiset ja kansainväliset tiimit.</p>
      </div>
    </div>

    <div class="exp-row">
      <div class="exp-years">4/2010 — 10/2010</div>
      <div class="exp-rule"></div>
      <div>
        <div class="exp-role">Web Graphic Designer</div>
        <div class="exp-co">Gemilo</div>
        <p class="exp-desc">Verkkosivustojen ja sosiaalisen intranet -tuotteen suunnittelu sekä css/html/mako-taitto.
</p>
      </div>
    </div>

    <div class="exp-row"  style="border:0;">
      <div class="exp-years">2/2006 — 4/2010</div>
      <div class="exp-rule"></div>
      <div>
        <div class="exp-role">Web Designer</div>
        <div class="exp-co">Grey-Hen</div>
        <p class="exp-desc">Autoalan hinnoittelu- ja raportointituotteiden design lead. Yritysilmeen suunnittelu, markkinointimateriaalit.</p>
      </div>
	  
	  </div>
	  
	   <h3 style="padding-top: 24px;">Koulutus</h3>
	       <div class="exp-row" style="border:0;">
	   <div class="exp-years">1/2003 — 1/2007</div>
	     <div class="exp-rule"></div>
		 <div>
	   <div class="exp-role">Medianomi (AMK)</div>
	   <div class="exp-co">Tampereen Ammattikorkeakoulu - taide ja viestintä</div>
	    Koulutusohjelma: vuorovaikutteinen media
	   </div>
    </div></div>
  </section>

  <!-- ── portfolio ── -->
  <section id="portfolio">
  <div class="contentwrapper">
   
    <h2>Portfolio - muutamia projektiesittelyjä</h2>
   

    <div class="portfolio-grid">

      <div class="portfolio-card">
        <a href="projekti1.html"><img src="oph4.png" alt="Opiskelupaikan vastaanoton käyttöliittymä" class="portfolio-img"></a>
        <div class="portfolio-idx">Opetushallituksen Oma opintopolku</div>
       <h4><a href="projekti1.html">Sujuvampi opiskelupaikan vastaanotto ja moniteemaisen design-systeemin kehitys isolle julkiselle organisaatiolle</a></h4>
        
        <a href="projekti1.html" class="portfolio-link">Tutustu projektiin</a>
      </div>

      <div class="portfolio-card">
        <a href="projekti2.html"><img src="fos4.png" alt="Wärtsilä FOS-palvelun käyttöliittymä" class="portfolio-img"></a>
        <div class="portfolio-idx">Wärtsilä FOS</div>
         <h4><a href="projekti2.html">Datapohjaista ja käyttäjälähtöistä tuotesuunnittelua merenkulkualan globaaleille toimijoille</a></h4>
        <a href="projekti2.html"  class="portfolio-link">Tutustu projektiin</a>
      </div>

      <div class="portfolio-card">
        <a href="projekti3.html"><img src="elsa1.png" alt="Elsa-palvelun käyttöliittymä" class="portfolio-img"></a>
        <div class="portfolio-idx">Elsa-palvelu</div>
        <h4><a href="projekti3.html">Erikoislääkäreiden koulutuksen edistymisen palveluportaali</a></h4>
        <a href="projekti3.html" class="portfolio-link">Tutustu projektiin</a>
      </div>
</div>   
 </div>
  </section>

  <!-- ── palautteita ── -->
  <section id="palautteita">
  <div class="contentwrapper">
    
    <h2>Palautteita asiakkailta</h2>

    <div class="test-grid">
	

	<div class="test-card">
		<h4>"Proaktiivinen, tehokas, erinomainen työn jälki, helppo kommunikoida ja tehdä yhteistyötä."</h4>
		<p class="test-name">Tuoteomistaja</p>
      </div>

	
	<div class="test-card">
		<h4>"Tarpeiden kuuntelu ja ymmärtäminen, laadukas työn jälki, hyvän työilmapiirin ylläpitäminen, luotettavuus. Aktiivinen ja nopea yhteydenpito sekä ratkaisu- ja asiakaskeskeinen lähestymistapa tekemiseen."</h4>
		<p class="test-name">Tuotepäällikkö</p>
      </div>

      <div class="test-card">
	    <h4>Arto ymmärtää hyvin nopeasti asiakastarpeet ja monimutkaiset kokonaisuudet. Arton kanssa on mukava työskennellä." </h4>
		<p class="test-name">Projektin vetäjä</p>
      </div> 

	<div class="test-card">  
		<h4>"Arto on todella osaava. Hänellä on hyvä ymmärrys projektiemme ja ulkoisten asiakkaidemme tarpeista ja hän osaa ottaa ne hyvin huomioon suunnittelutyössä."</h4>
		<p class="test-name">Tuoteomistaja</p>  
	</div>
	
	<div class="test-card" style="border-bottom:0";>
		<h4>"Nopea, kuunteleva, analyyttinen ja tehokas. Hyvää jälkeä!"</h4>
		<p class="test-name">Projektin vetäjä</p>
      </div>
	  
    <!-- <div class="test-card" style="border-bottom: none;">  
	  <h4>"Järjestelmän suunnittelu Arton kanssa on ollut erittäin sujuvaa. Hän on hyvä kuuntelemaan ja ymmärtämään tarpeitamme sekä esittämään toimivia ideoita, joita emme itse osaisi ajatella. Järjestelmään on ollut tarpeen rakentaa paikoin monimutkaisiakin toiminnallisuuksia, ja niidenkin kehittämisessä Arto on hienosti onnistunut, ja ratkaisuja on ollut mukava pohtia yhdessä."</h3>
	  <p class="test-name">Tuotepäällikkö</p>  
   </div>-->

</div>
    </div>
  </section>

  <!-- ── yhteys ── -->
  <section id="yhteys">
  <div class="contentwrapper">
    <!--<span class="ghost-num">05</span>-->
    <h2>Tehdään yhdessä<br>Internetistä valmis.</h2>
    

    <div class="yhteys-grid">
	<div class="yhteys-cell">
         <img src="arto2.jpg" alt="Kuva minusta">
      </div>
	
	
	
      <div class="yhteys-cell">
        <div class="yhteys-label">SÄHKÖPOSTI</div>
        <a href="mailto:arto.seppanen@gmail.com" class="yhteys-val"><span class="__cf_email__" data-cfemail="bedfd2dbc6fedfd2dbc6d3d1ccd9dfd090dadbcdd7d9d0">arto.seppanen@gmail.com</span></a>
		
		<br /> <br /> <div class="yhteys-label">PUHELIN</div>
        <a href="tel:+358407405927" class="yhteys-val"><span class="__cf_email__" data-cfemail="bedfd2dbc6fedfd2dbc6d3d1ccd9dfd090dadbcdd7d9d0">+358 40 740 5927</span></a>
      </div>
	  
	 
     
    
   
     </div>
    </div>
  </section>

</main>

<!--<footer>
  <p>© 2026 Arto Seppänen </p>
  </footer>-->

<script>
  /* ── Hamburger ── */
  const ham  = document.getElementById('ham');
  const mob  = document.getElementById('mob');
  const mobs = document.querySelectorAll('.mob-link');

  function closeMenu() {
    ham.classList.remove('open');
    mob.classList.remove('open');
    mob.setAttribute('aria-hidden', 'true');
    document.body.style.overflow = '';
  }

  ham.addEventListener('click', () => {
    const isOpen = mob.classList.toggle('open');
    mob.setAttribute('aria-hidden', isOpen ? 'false' : 'true');
    ham.classList.toggle('open');
    document.body.style.overflow = isOpen ? 'hidden' : '';
  });

  mobs.forEach(l => l.addEventListener('click', closeMenu));

  /* ── Scrollspy ── */
  const sections  = document.querySelectorAll('section[id]');
  const navLinks  = document.querySelectorAll('.nav-links a');
  const mobLinks  = document.querySelectorAll('.mob-link');

  function setActive(id) {
    navLinks.forEach(l => {
      l.classList.toggle('active', l.getAttribute('href') === '#' + id);
    });
    mobLinks.forEach(l => {
      l.classList.toggle('active', l.getAttribute('href') === '#' + id);
    });
  }

  const spy = new IntersectionObserver(entries => {
    entries.forEach(e => {
      if (e.isIntersecting) setActive(e.target.id);
    });
  }, { rootMargin: '-42% 0px -52% 0px', threshold: 0 });

  sections.forEach(s => spy.observe(s));
</script>
</body>
</html>

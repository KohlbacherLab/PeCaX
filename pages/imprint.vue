<script type="text/javascript">
	export default{
	  head: {
	    title: 'Documentation'
	  },
	  head () {
	    return {
	    	link: [,
	        {
	        	rel:"alternate", type:"application/html", title:"PeCaX", href:"/"
	        }
	      ]
	    }
	  }
  }
	
    window.onNuxtReady((app) => {
    // Add active class to the current button (highlight it)
    var header = document.getElementById("nav");
    var btns = header.getElementsByClassName("page-link");
    for (var i = 0; i < btns.length; i++) {
      btns[i].addEventListener("click", function() {
      var current = document.getElementsByClassName("active");
      current[0].className = current[0].className.replace(" active", "");
      this.className += " active";
      });
    }
  })
  
</script>

<template>
<div>
    <div class="topnav" id ="nav">
        <div class="topnav-centered">
            <a class="page-link border-0 border-dark" href="/">PeCax</a>
        </div>
        <div class="dropdown topnav-right" id="navAbout">  
          	<button class="dropbtn"><b-icon data-html2canvas-ignore="true" icon="list"></b-icon>
          	<div class="dropdown-content">
	          	<a href="/about" class="page-link">About </a>
	            <a class="page-link" href="/documentation">Documentation</a>
	            <a class="page-link" href="/contact">Contact</a>
	          </div>
          </button> 
      	</div>
    </div>
 <header class="site-header">
    <h1 class="site-title">Imprint</h1>
  </header>
<div id="c216" class="csc-default">
	<h4>Allgemeine Informationen gem. § 5 TMG, § 55 RStVG</h4>
	<div>
		<table class="plain">
		<tbody>
		<tr>
		<td>Adresse</td>
		<td>
		<p class="bodytext">Eberhard Karls Universität Tübingen<br />
		Geschwister-Scholl-Platz<br />
		72074 Tübingen</p>
		</td>
		</tr>
		<tr>
		<td></td>
		<td>Die Universität Tübingen ist eine Körperschaft des öffentlichen Rechts. Sie wird durch den Rektor Prof. Dr. Bernd Engler (eMail: bernd. engler [at] uni-tuebingen.de) gesetzlich vertreten</td>
		</tr>
		<tr>
		<td>Telefonzentrale</td>
		<td>+49 (0) 70 71/29-0</td>
		</tr>
		<tr>
		<td>Fax Zentrale Verwaltung</td>
		<td>+49 (0) 70 71/29-59 90</td>
		</tr>
		<tr>
		<td>Internet-Adresse</td>
		<td><a class="external-link" href="https://www.uni-tuebingen.de/">https://www.uni-tuebingen.de</a></td>
		</tr>
		<tr>
		<td>Umsatzsteuer-Identifikationsnummer</td>
		<td>
		<p class="bodytext">gemäß § 27a Umsatzsteuergesetz: <b>DE812383453</b></p>
		</td>
		</tr>
		<tr>
		<td>Aufsichtsbehörde</td>
		<td>Ministerium für Wissenschaft, Forschung und Kunst Baden-Württemberg</td>
		</tr>
		</tbody>
		</table>
		</div>
		<h4>1. Externe Links</h4>
		<div id="c225" class="csc-frame csc-frame-default">
			<div class="csc-textpic-text">
			<p class="bodytext">Diese Webseite der Universität Tübingen enthält auch entsprechend gekennzeichnete Links oder Verweise auf Websites Dritter. Durch den Link vermittelt die Universität Tübingen lediglich den Zugang zur Nutzung dieser Inhalte. Eine Zustimmung zu den Inhalten den verlinkten Seiten Dritter ist damit nicht verbunden. Die Universität Tübingen übernimmt daher keine Verantwortung für die Verfügbarkeit oder den Inhalt solcher Websites und keine Haftung für Schäden oder Verletzungen, die aus der Nutzung – gleich welcher Art – solcher Inhalte entstehen. Hierfür haftet allein der Anbieter der jeweiligen Seite.</p>
			<p class="bodytext">Bei der erstmaligen Verknüpfung mit einem anderen Internetangebot hat die Redaktion dessen Inhalt daraufhin überprüft, ob durch ihn eine mögliche zivilrechtliche oder strafrechtliche Verantwortlichkeit ausgelöst wird. Dort nachträglich eingebundene Inhalte können jedoch leider nicht überprüft werden. Der Verweis auf dieses Angebot wird unverzüglich aufgehoben werden, sobald die Redaktion feststellt oder von anderen darauf hingewiesen wird, dass ein bestimmtes Angebot, zu dem ein Link bereitgestellt wurde, eine zivil- oder strafrechtliche Verantwortlichkeit auslöst.</p>
			<h4>2. Urheberrecht</h4>
			<p class="bodytext">Copyright (c), Universität Tübingen. Alle Rechte vorbehalten.</p>
			<p class="bodytext">Alle auf dieser Website veröffentlichten Inhalte (Layout, Texte, Bilder, Grafiken, Video- und Tondateien usw.) unterliegen dem Urheberrecht. Jede vom Urheberrechtsgesetz nicht zugelassene Verwertung bedarf vorheriger ausdrücklicher Zustimmung der Universität Tübingen. Dies gilt insbesondere für Vervielfältigung, Bearbeitung, Übersetzung, Einspeicherung, Verarbeitung bzw. Wiedergabe von Inhalten in Datenbanken oder anderen elektronischen Medien und Systemen. Fotokopien und Downloads von Web-Seiten für den privaten, wissenschaftlichen und nicht kommerziellen Gebrauch dürfen hergestellt werden.</p>
			<p class="bodytext">Das Urheberrecht für die Wort-Bild-Marke liegt ausdrücklich bei der Universität Tübingen.</p>
			<p class="bodytext">Wir erlauben ausdrücklich und begrüßen das Zitieren unserer Dokumente und Webseiten sowie das Setzen von Links auf unsere Website.</p>
			<h4>3. Haftungsausschluss</h4>
			<p class="bodytext">Die Informationen auf dieser Website wurden nach bestem Wissen und Gewissen sorgfältig zusammengestellt und geprüft. Es wird jedoch keine Gewähr – weder ausdrücklich noch stillschweigend – für die Vollständigkeit, Richtigkeit oder Aktualität sowie die jederzeitige Verfügbarkeit der bereit gestellten Informationen übernommen. Eine Haftung für Schäden, die aus der Nutzung oder Nichtnutzung der auf dieser Website angebotenen Informationen entstehen ist – soweit gesetzlich zulässig – ausgeschlossen.</p>
		</div>
		<h4>Ansprechpartner</h4>
		<div class="csc-textpic-text">
			<p>Prof. Dr. Oliver Kohlbacher<br />
			Sand 14<br />
			72076 Tübingen<br />
			Telefon: +49-7071-29-70458<br />
			Fax: +49-7071-29-5152<br />
			eMail: oliver.kohlbacher [at] uni-tuebingen.de</p>
		</div>
	</div>
</div>
<br><br>
<footer>
      <div class="containerMerged">
          <a class="page-link border-0 border-dark" href="/imprint/">Imprint</a>
          <a class="page-link border-0 border-dark" href="/datenschutzerklarung/" aria-current="page">Datenschutzerklärung</a>   
      </div>  
</footer>
</div>
</template>
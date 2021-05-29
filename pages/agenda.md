---
layout: page
title: Agenda
description: Behandelingen en facturen beheren
image: assets/images/agenda/agenda.png
nav-menu: true
---

<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Agenda</h1>
		</header>

		<span class="image fit"><img src="{% link assets/images/agenda/agenda.png %}" alt=""/></span>

		<!-- Content -->
		<h2 id="content">Introductie</h2>
		<p>De agenda is waarschijnlijk het belangrijkste scherm van het programma. In dit scherm kunnen behandelingen bekeken, toegevoegd en verwijderd worden. Weergeven kan op drie verschillende manieren. Verder kan in dit scherm ook een overzicht van alle behandelingen en facturen van de geselecteerde maand bekeken worden. Ten slotte kunnen vanuit dit scherm ook de behandelingen doorgeboekt worden naar facturen.</p>

		<h2>Weergavemodi</h2>
		<div class="row">
			<div class="8u 12u$(small)">
				<h3>Dag</h3>
				<p>In deze weergavemodus kunnen de behandelingen van een geselecteerde dag beekeken worden. Elke gekleurd vierkant stelt een behandeling voor, waarbij de bovenkant van het vierkant de begintijd voorsteld en de onderkant de eindtijd. Wanneer Fysioblauw 2 op een breed genoeg scherm wordt uitgevoerd, worden ook de notities van een behandeling zichtbaar in dit vierkant.</p>
			</div>
			<div class="4u$ 12u$(small)">
				<img src="{% link assets/images/agenda/dag.png %}" alt=""/>
			</div>

			<div class="8u 12u$(small)">
				<h3>Week</h3>
				<p>Deze weergavemodus is de combinatie van 7 dag weergaven - elke weekdag respectievelijk. In de instellingen kan ingesteld worden welke dag de begindag van de week moet zijn. Omdat in deze weergavemodus meerdere dagen weergegeven worden, is slechts de begin- en eindtijd van de behandeling in combinatie van de patiëntnaam zichtbaar.</p>
			</div>
			<div class="4u$ 12u$(small)">
				<img src="{% link assets/images/agenda/week.png%}" alt=""/>
			</div>

			<div class="8u 12u$(small)">
				<h3>Maand</h3>
				<p>De maand-weergavemodus bied een snel overzicht van alle behandelingen binnen de geselecteerde maand. Elke dag is aan te klikken. Wanneer dit gebeurt wordt er automatisch overgeschakeld naar de dag-weergave van de geselecteerde dag.</p>
			</div>
			<div class="4u$ 12u$(small)">
				<img src="{% link assets/images/agenda/maand.png%}" alt=""/>
			</div>

			<div class="8u 12u$(small)">
				<h3>Behandelingen (maand)</h3>
				<p>In de Behandelingen (maand) modus worden alle behandelingen van de geselecteerde maand weergegeven. Dit is door middel van een lijst, en kan daarom overzichtelijker zijn dan de Maand weergavemodus. Aangezien een patiënt vaak meerdere behandelingen binnen een maand heeft zijn de behandelingen gegroepeerd per patiënt, gesorteerd op basis van de achternaam van deze patiënten. De details van een behandeling kunnen bekeken worden door deze aan te klikken. Via het aanklikken van rechtermuisknop &rarr; Verwijder, kan de behandeling verwijderd worden.</p>
			</div>
			<div class="4u$ 12u$(small)">
				<img src="{% link assets/images/behandelingen/behandelingen_maand.png%}" alt=""/>
			</div>

			<div class="8u 12u$(small)">
				<h3>Facturen (maand)</h3>
				<p></p>
			</div>
			<div class="4u$ 12u$(small)">
				<img src="{% link assets/images/facturen/facturen_maand.png%}" alt=""/>
			</div>
		</div>

		<div class="row">
			<div class="6u 12u$(small)">
				<h3>Datum navigatie</h3>
				<p>Een belangrijke eigenschap van een agenda is natuurlijk het kunnen navigeren tussen verschillende data. Hiervoor zijn de knoppen bovenaan de agenda bedoelt (de knoppen binnen het aangegeven rode vierkant in de afbeelding). Afhankelijk van de geselecteerde weergave modus, hebben de 'vorige' (&larr;) en 'volgende' (&rarr;) knoppen een verschillende werking:</p>
				<ul>
					<li>Vorige of volgende dag; bij weergavemodus 'Dag'.</li>
					<li>Vorige of volgende week; bij weergavemodus 'Week'.</li>
					<li>Vorige of volgende maand; bij weergavemodus '</li>
				</ul>
			</div>
			<div class="6u$ 12u$(small)">
				<img src="{% link assets/images/agenda/datum_navigatie.png%}" alt=""/>
			</div>
		</div>
		
	</div>
</section>
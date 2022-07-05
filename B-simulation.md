---
title: Fluid Mechanics Simulation
layout: landing
description: 'Page for fluid mechanics simulation'
image: assets/images/simulation.png
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>Overview</h2>
		</header>
		<p>This page describes the simulations conducted for the Urban Greenery Project. These simulations visualize how a forest can lower the ambient temperature. A forest can lower the ambient temperature by providing shade and through evapotranpiration. In this simulation the cooling due to evapotranspirative effects, the drag from the canopy leaves, and the turbulence from the presence of buildings were studied.</p>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<a class="image">
			<img src="./assets/images/render.png" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Geometry</h3>
				</header>
				<p>The forest for the Urban Greenery Projects was modeled as a radially symmetric geometry with the forest at the center and evenly spaced buildings on the exterior, surrounding the forest. Wind with a uniform velocity profile will blow from one direction. A render of the goemetry is shown on the left. </p>
			</div>
		</div>
	</section>
	<section>
		<a class="image">
			<img src="./assets/images/diagram.png" alt="" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Diagram</h3>
				</header>
				<p>The radially symmetric nature of the geometry allowed us to define a characteristic plane. In other words, we simulated a 2D geometry that accurately represents the 3D geometry. Running the simulation in 2D also uses a lot less computing power than if the simulation were to be ran in 3D. The buildings were  modeled as evenly spaced solid squares and the forest was modeled as a rectangle with a drag force corresponding to the drag force induced by the canopy leaves. </p>
			</div>
		</div>
	</section>
	<section>
		<a class="image">
			<img src="./assets/images/temp.gif" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Results</h3>
				</header>
				<p>The simulation was conducted until the system was at steady state. From the temperature contour plots it can be seen that the street spaces between the three to four succeeding buildings are significantly cooler. The reason becomes apparent when the velocity contour plots are observed. Cooler air from the forest is blown above the buildings and creates a curl in the space between buildings. This curling effect pushes the cooler air down to the street level while pushing hot air out. </p>
			</div>
		</div>
	</section>
</section>

<!-- Three -->
<section id="three">
	<div class="inner">
		<header class="major">
			<h2>Progress</h2>
		</header>
		<p>The results of this simulation confirms the forests ability to cool surrounding buildings and streets. From here, we are able to start our plans for creating a forest in real life! Check out the progress on our blog.</p>
		<ul class="actions">
			<li><a href="C-blog.html" class="button next">Check it out</a></li>
		</ul>
	</div>
</section>

</div>

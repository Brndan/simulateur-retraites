---
title: "Comparateur de retraites entre le système actuel et le projet du gouvernement"
date: 2019-10-12T08:08:47+02:00
draft: false
---

⚠ *Le simulateur est prévu pour des carrières entamées relativement jeune et poursuivies à leur terme. C’est pourquoi l'âge de début de carrière est limité à 28 ans. Si vous avez été par exemple assistant-e d'éducation avant d'être enseignant-e, le simulateur sera bien plus proche de la réalité en faisant commencer votre carrière au début de votre période de travail comme AED.*

{{< rawhtml >}}


<script type="text/javascript" src="js/retraites.js"></script>
<script type="text/javascript" src="js/esthetique.js"></script>
<script type="text/javascript" src="js/impression.js"></script>
<!-- <link rel="stylesheet" type="text/css" href="css/print.css" media="print"> -->

<h2>Déroulement de votre carrière</h2>

<div class="blocSelection">
    <label for="statut">Sélectionnez votre corps&nbsp;:</label>
    <div id="apparenceStatut">
        <div class="menuSelection">

            <select name="Corps" id="statut" onchange="afficheDirection();">
			    <option value="0">ADJAENES, ATRF, magasinier⋅ère</option>
			    <option value="1">AESH</option>
			    <option value="2">Contractuel-le enseignant-e (grille favorable, ex Paris)</option>
			    <option value="3">Contractuel-le enseignant-e (grille défavorable, ex  Amiens)</option>
			    <option value="4" selected>Certifié⋅e, PLP, CPE…</option>
			    <option value ="6">Agrégé-e, MCF</option>
			    <option value="5">Prof⋅e des écoles</option>
				<option value="7">SAENES, BIBAS, Tech</option>

			   </select>
        </div>
    </div>
</div>

<ul id="direction">
	<p> Dans votre cas, nous avons besoin de quelques information supplémentaires.</p>
        <li>
            <div class="blocSelection">
                <label for="direction_1">Nombre d'années chargé-e de direction dans une école à classe unique&nbsp;:</label>
                <div class="menuSelection">
                    <select name="direction1classe" id="direction_1">
			    		<option value="0" selected>0 année</option>
			    		<option value="1">1 année</option>
			    		<option value="3">3 années</option>
			    		<option value="5">5 années</option>
			    		<option value="10">10 années</option>
			    		<option value="15">15 années</option>
			    		<option value="20">20 années</option>
			    		<option value="25">25 années</option>
			    		<option value="30">30 années</option>
			    		<option value="35">35 années</option>
			    		<option value="40">40 années</option>
			   		</select>
                </div>
            </div>
        </li>
        <li>
            <div class="blocSelection">
                <label for="direction_23">Nombre d'années chargé-e de direction dans une école de 2 à 3 classes&nbsp;:</label>
                <div class="menuSelection">
                    <select name="direction2a3classes" id="direction_23">	
			    <option value="0" selected>0 année</option>
			    <option value="1">1 année</option>
			    <option value="3">3 années</option>
			    <option value="5">5 années</option>
			    <option value="10">10 années</option>
			    <option value="15">15 années</option>
			    <option value="20">20 années</option>
			    <option value="25">25 années</option>
			    <option value="30">30 années</option>
			    <option value="35">35 années</option>
			    <option value="40">40 années</option>
			   </select>
                </div>
            </div>
        </li>
        <li>
            <div class="blocSelection">
                <label for="direction_4">Nombre d'années chargé-e de direction dans une école de 4 classes&nbsp;:</label>
                <div class="menuSelection">
                    <select name="direction4classes" id="direction_4">	
			    <option value="0" selected>0 année</option>
			    <option value="1">1 année</option>
			    <option value="3">3 années</option>
			    <option value="5">5 années</option>
			    <option value="10">10 années</option>
			    <option value="15">15 années</option>
			    <option value="20">20 années</option>
			    <option value="25">25 années</option>
			    <option value="30">30 années</option>
			    <option value="35">35 années</option>
			    <option value="40">40 années</option>
			   </select>
                </div>
            </div>
        </li>
        <li>
            <div class="blocSelection">
                <label for="direction_59">Nombre d'années chargé-e de direction dans une école de 5 à 9 classes&nbsp;:</label>
                <div class="menuSelection">
                    <select name="direction5a9classes" id="direction_59">	
			    <option value="0" selected>0 année</option>
			    <option value="1">1 année</option>
			    <option value="3">3 années</option>
			    <option value="5">5 années</option>
			    <option value="10">10 années</option>
			    <option value="15">15 années</option>
			    <option value="20">20 années</option>
			    <option value="25">25 années</option>
			    <option value="30">30 années</option>
			    <option value="35">35 années</option>
			    <option value="40">40 années</option>
			   </select>
                </div>
            </div>
        </li>
        <li>
            <div class="blocSelection">
                <label for="direction_10Plus">Nombre d'années chargé-e de direction dans une école de 10 classes et plus&nbsp;:</label>
                <div class="menuSelection">
                    <select name="direction10classesEtPlus" id="direction_10Plus">
			    <option value="0" selected>0 année</option>
			    <option value="1">1 année</option>
			    <option value="3">3 années</option>
			    <option value="5">5 années</option>
			    <option value="10">10 années</option>
			    <option value="15">15 années</option>
			    <option value="20">20 années</option>
			    <option value="25">25 années</option>
			    <option value="30">30 années</option>
			    <option value="35">35 années</option>
			    <option value="40">40 années</option>
			   </select>
                </div>
            </div>
        </li>
</ul>
<ul class="formulaire">
    <li>
        <div class="blocSelection">
            <label for="debut">Âge de début de carrière&nbsp;:</label>
            <div class="menuSelection">
                <select name="ageDebutCarriere" id="debut">
			    <option value="20">20 ans</option>
			    <option value="21">21 ans</option>
			    <option value="22" selected>22 ans</option>
			    <option value="23">23 ans</option>
			    <option value="24">24 ans</option>
			    <option value="25">25 ans</option>
			    <option value="26">26 ans</option>
			    <option value="27">27 ans</option>
			    <option value="28">28 ans</option>
			   </select>
            </div>
        </div>
        <li>
            <div class="blocSelection">
                <label for="fin">Âge de départ à la retraite&nbsp;:</label>
                <div class="menuSelection">
                    <select name="ageFinCarriere" id="fin">
			    		<option value="62" selected>62 ans</option>
			    		<option value="63">63 ans</option>
			    		<option value="64">64 ans</option>
			    		<option value="65">65 ans</option>
			    		<option value="66">66 ans</option>
			    		<option value="67">67 ans</option>
			   		</select>
                </div>
            </div>
		</li>
        <li>
            <div class="blocSelection">
                <label for="naissance">Année de naissance&nbsp;:</label>
                <div class="menuSelection">
                    <select name="anneeNaissance" id="naissance">
			    		<option value="1958">1958</option>
			    		<option value="1959">1959</option>
			    		<option value="1960">1960</option>
			    		<option value="1961">1961</option>
			    		<option value="1962">1962</option>
			    		<option value="1963">1963</option>
			    		<option value="1964">1964</option>
			    		<option value="1965">1965</option>
			    		<option value="1966">1966</option>
			    		<option value="1967">1967</option>
			    		<option value="1968">1968</option>
			    		<option value="1969">1969</option>
			    		<option value="1970" selected>1970</option>
			    		<option value="1971">1971</option>
			    		<option value="1972">1972</option>
			    		<option value="1973">1973</option>
			    		<option value="1974">1974</option>
			    		<option value="1975">1975</option>
			    		<option value="1976">1976</option>
			    		<option value="1977">1977</option>
			    		<option value="1978">1978</option>
			    		<option value="1979">1979</option>
			    		<option value="1980">1980</option>
			    		<option value="1981">1981</option>
			    		<option value="1982">1982</option>
			    		<option value="1983">1983</option>
			    		<option value="1984">1984</option>
			    		<option value="1985">1985</option>
			    		<option value="1986">1986</option>
			    		<option value="1987">1987</option>
			    		<option value="1988">1988</option>
			    		<option value="1989">1989</option>
			    		<option value="1990">1990</option>
			    		<option value="1991">1991</option>
			    		<option value="1992">1992</option>
			    		<option value="1993">1993</option>
			    		<option value="1994">1994</option>
			    		<option value="1995">1995</option>
			    		<option value="1996">1996</option>
			    		<option value="1997">1997</option>
			    		<option value="1998">1998</option>
			   		</select>
                    </div>
                </div>
            </li>
</ul>
<div id="primes">
    <h3>Primes et indemnités</h3>
    <p><i>Nous vous proposons de faire des simulations en intégrant les primes (ISAE et indemnité de direction dans le premier degré, ISOE et prise en compte des HSA dans le second degré, REP et REP+…). Ce dispositif n'est pas prévu dans le rapport Delevoye, mais il a été mis sur la table pour compenser les pertes de pension prévues dans la fonction publique. Faites-vous votre opinion avec ces simulations...</i></p>
    <div class="blocSelection">
        <label for="primesEtIndemnites">Choisissez la simulation avec ou sans les primes et indemnités&nbsp;:</label>
        <div class="menuSelection">
            <select name="Corps" id="primesEtIndemnites" onchange="affichePrimes();">
			    <option value="0" selected>Ignorer les primes et indemnités</option>
			    <option value="1">Prendre en compte les primes et indemnités</option>
			   </select>
        </div>
    </div>
    <div id="affichePrimesIndemnites">
        <ul class="formulaire">
            <li>
                <div class="blocSelection">
                    <label for="rep">Nombre d'années en REP&nbsp;:</label>
                    <div class="menuSelection">
                        <select name="menuREP" id="rep">	
			    			<option value="0" selected>0 année</option>
			    			<option value="1">1 année</option>
			    			<option value="3">3 années</option>
			    			<option value="5">5 années</option>
			    			<option value="10">10 années</option>
			    			<option value="15">15 années</option>
			    			<option value="20">20 années</option>
			    			<option value="25">25 années</option>
			    			<option value="30">30 années</option>
			    			<option value="35">35 années</option>
			    			<option value="40">40 années</option>
			   			</select>
                    </div>
                </div>
            </li>
            <li>
            <div class="blocSelection">
                <label for="repPlus">Nombre d'années en REP+&nbsp;:</label>
                <div class="menuSelection">
                    <select name="menuREPPlus" id="repPlus">
			    		<option value="0" selected>0 année</option>
			    		<option value="1">1 année</option>
			    		<option value="3">3 années</option>
			    		<option value="5">5 années</option>
			    		<option value="10">10 années</option>
			    		<option value="15">15 années</option>
			    		<option value="20">20 années</option>
			    		<option value="25">25 années</option>
			    		<option value="30">30 années</option>
			    		<option value="35">35 années</option>
			    		<option value="40">40 années</option>
			   		</select>
                </div>
            </div>
            </li>
        </ul>
    </div>
</div>
<div class="boutonCalcul">
    <input type="button" value="Calculer ma retraite" onclick="calcul();" />
</div>
<!--Balises d'accueil des résultats dans le système actuel -->
<div id="resultat">
	<div id="pourImpression">
		<h2 id="resultatActuel"></h2>
		<p id="resultatActuel-contractuel"></p>
		<p id="salaire"></p>
		<p id="trimestresRequis"></p>
		<p id="trimestresAcquis"></p>
		<p id="retraiteRepartition"></p>
		<!--Balises d'accueil des résultats dans le système à points -->
		<h2 id="resultatPoint"></h2>
		<p id="resultatPoints-contractuel"></p>
		<p id="nombrePoints"></p>
		<p id="agePivot"></p>
		<p id="retraitePoints"></p>
		<p id="pertesMensuelles"></p>
		<p id="pertesAnnuelles"></p>
		<div id = "logo-greve-impression">
			<p>
				Simulation effectuée sur <b>retraites.sudeducation.org</b>
			</p>
			<img src="visuels/visuel/AutocollantOnContinue.png">
		</div>
	</div>
</div>
<div id="impression">
	<div class="boutonCalcul">
		<input type="button" value="Imprimer le résultat" onclick="impression('pourImpression');" />
	</div>
	<div id="remarques">
	</div>
</div>

{{< /rawhtml >}}

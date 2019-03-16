<template>
	<section class="bg-grey">
        <h1 class="banner-h1">La podologie</h1>
        <img class="w-100 h-auto" src="/semelle_banner.jpg" alt="semelles_banner">
        
        <div class="container">
            <div class="bg-white p-3 mb-3 mt-md-5 mt-3">
                <p>
                    C’est la science qui étudie la prévention, le diagnostic et la prise en charge des
                    pathologies du pied et de l’appareil locomoteur.
                </p>
                <p>
                    Je réalise des semelles orthopédiques à la demande du médecin, je peux aussi en prescrire (mais vous ne serez pas
                    remboursés).
                </p>
                <div>
                    Lors du premier rendez-vous, je réalise un examen clinique complet :
                    <ul>
                        <li>Interrogatoire</li>
                        <li>Examen statique global sur podoscope et sur plateforme podobarométrique</li>
                        <li>Examen dynamique</li>
                    </ul>
                </div>
                <p class="mb-0">
                    Il existe différents types de semelles pour différents types de pathologies pour
                    différents patients ayants des âges et des activités différentes.
                </p>
            </div>

            <h2 class="py-3 m-0">Les semelles thermoformées</h2>
            <div class="bg-white p-3 mb-3">
                <p>Elles sont moulées sur le pied du patient et ont une action biomécanique.</p>
                <p>
                    Il existe énormément de matériaux qui me permettent de faire des semelles
                    efficaces et confortables en fonction de chaque pathologie et de chaque
                    patient.
                </p>
                <p>
                    <b>Pour qui :</b>  je ne fais ce type de semelles que chez l’adulte ou l’adolescent, le
                    sportif et les personnes qui recherchent du confort, personnes âgées,
                    diabétiques…
                </p>
                <p class="mb-0">
                    <b>Pour quoi :</b>  talalgie, aponévrosite plantaire (épine calcanéenne), douleur de
                    l’avant pied, problèmes de genoux, tendinite de la patte d’oie, syndrome de
                    l’essuie-glace, périsostite tibiale, instabilité de cheville, fonte du capiton
                    plantaire, problèmes de dos, inégalité vraie des membres inférieurs…
                </p>
            </div>

            <div class="row">
                <div class="col-12 col-md-4 p-md-5 p-3">
                    <img class="w-100 h-auto" src="/semelle_thermo_1.jpg" alt="semelle_thermo_1">
                </div>
                <div class="col-12 col-md-4 p-md-5 p-3">
                    <img class="w-100 h-auto" src="/semelle_thermo_2.jpg" alt="semelle_thermo_2">
                </div>
                <div class="col-12 col-md-4 p-md-5 p-3">
                    <img class="w-100 h-auto" src="/semelle_thermo_3.jpg" alt="semelle_thermo_3">
                </div>
            </div>

            <h2 class="py-3 m-0">Les semelles proprioceptives</h2>
            <div class="bg-white p-3 mb-3">
                <p>
                    Ce sont des semelles fines, les calles ne font pas plus de 4 mm, elles agissent
                    sur les récepteurs des muscles et des tendons qu’elles vont stimuler ou inhiber
                    et ainsi agir comme une rééducation.
                </p>
                <p>
                    <b>Pour qui :</b> les enfants et les adultes.
                </p>
                <p class="mb-0">
                    <b>Pour quoi :</b>  les pieds plats, les pieds creux, en dehors ou en dedans, mais elles
                    agissent aussi plus haut pour aider à corriger un trouble postural et ainsi
                    soulager des maux de genoux, de bassin, de dos…
                </p>
            </div>

            <div class="row">
                <div class="col-12 col-md-4 offset-md-2 p-md-5 p-3">
                    <img class="w-100 h-auto" src="/semelle_proprio_1.jpg" alt="semelle_proprio_1">
                </div>
                <div class="col-12 col-md-4 p-md-5 p-3">
                    <img class="w-100 h-auto" src="/semelle_proprio_2.jpg" alt="semelle_proprio_2">
                </div>
            </div>

            <div class="p-3 d-flex flex-column">
                <div class="d-flex justify-content-center">
                    <b class="text-center text-20-xs py-3">
                        POSTURE NORMALE
                    </b>
                </div>
                <div class="d-flex justify-content-center">
                    <div class="py-3 circle">
                        <fa :icon="['fa', 'equals']" />
                    </div>
                </div>
                <div class="d-flex justify-content-center">
                    <b class="text-center text-20-xs py-3">
                        ABSENCE DE CONTRAINTE, RAPPORTS HARMONIEUX
                    </b>
                </div>
                <div class="d-flex justify-content-center">
                    <div class="py-3 circle">
                        <fa :icon="['fa', 'equals']" />
                    </div>
                </div>
                <div class="d-flex justify-content-center">
                    <b class="text-center text-20-xs py-3">
                        ATTENUATION, DISPARIITION DES DOULEURS
                    </b>
                </div>
            </div>
        </div>
	</section>
</template>

<script>
    export default {}
</script>

<style>
    .circle {
        text-align: center;
        width: 55px;
        height: 55px;
        line-height: 27px;
        background-color: white;
        border-radius: 35px;
    }
</style>


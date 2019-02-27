<template>
	<section class="bg-grey">
        <h1 class="banner-h1">Contact</h1>
        <img class="w-100 h-auto" src="/contact_banner.jpg" alt="contact_banner">

        <div class="container">
            <div class="bg-white mt-5 p-3">
                <div class="row">
                    <div class="col-2">
                        <img class="w-100 h-auto" src="/sandrine_daubron.jpg" alt="sandrine_daubron">                    
                    </div>
                    <div class="col-10">
                        <h1>Pédicure Podologue Orsay</h1>
                        <h2>Sandrine Daubron</h2>
                        <p class="text-muted">
                            Je vous accueille dans mon cabinet au 1 rue des Mésanges à Orsay. 
                            N'hésitez pas à me contacter pour une urgence directement par téléphone au 01 69 28 07 65.
                            Je me déplace à domicile le jeudi sur les communes d'Orsay, Bures et Villebon.
                        </p>
                    </div>
                </div>
            </div>

            <div class="bg-white mt-5 p-3">
                <div class="row">
                    <div class="col-1 text-center">
                        <fa class="text-muted text-32" :icon="['fa', 'euro-sign']" />
                    </div>
                    <div class="col-5">
                        <h3>Remboursements</h3>
                        <ul>
                            <li>Conventionné</li>
                            <li>Carte vitale non accepté</li>
                            <li>Tiers payant: Sécurité sociale</li>
                        </ul>                  
                    </div>
                    <div class="col-1 text-center">
                        <fa class="text-muted text-32" :icon="['fa', 'money-check']" />
                    </div>
                    <div class="col-5">
                        <h3>Moyens de paiement</h3>
                        <div class="text-red">Cartes bancaires non acceptées</div>                 
                        <div>Chèques et espèces</div>                 
                    </div>
                </div>
            </div>

            <div class="bg-white mt-5 p-3">
                <div class="row">
                    <div class="col-1 text-center">
                        <fa class="text-muted text-32" :icon="['fa', 'map-marker-alt']" />
                    </div>
                    <div class="col-5">
                        <h3>Informations d'accès</h3>
                        <p>1 rue des mésanges, 91400 Orsay</p>
                        <h6 class="font-weight-bold">Moyen de transport:</h6>
                        <ul>
                            <li>RER B - Orsay Ville</li>
                            <li>RER B - Le Guichet</li>
                        </ul>                  
                    </div>
                    <div class="col-6">
                        <img class="w-100 h-auto" src="/entry_building.jpg" alt="entry_building">                                        
                    </div>
                </div>              
            </div>

            <div class="bg-white mt-5 p-3">
                <div class="row">
                    <div class="col-1 text-center">
                        <fa class="text-muted text-32" :icon="['fa', 'graduation-cap']" />
                    </div>
                    <div class="col-11">
                        <h3 class="mb-2">Formations</h3>
                        <ul class="m-0">
                            <li>
                                <span class="font-weight-bold mr-3">1991</span>
                                <span>Diplôme d'état de Pédicure Podologue</span>
                                <span class="font-weight-bold ml-3">ASSAS Paris</span>
                                <img class="ml-3" src="/assas_logo.jpg" alt="assas_logo">                                        
                            </li>
                            <li>
                                <span class="font-weight-bold mr-3">2001</span>
                                <span>Diabétologie</span>
                                <span class="font-weight-bold ml-3">SALPETRIERE Paris</span>
                                <img class="ml-3" src="/salpetriere_logo.png" alt="salpetriere_logo">                                        
                            </li>
                            <li>
                                <span class="font-weight-bold mr-3">2005</span>
                                <span>Podologie du sport</span>
                                <span class="font-weight-bold ml-3">CINETIC SANTE Paris</span>
                                <img class="ml-3" src="/cinetic_logo.jpg" alt="cinetic_logo">                                        
                            </li>
                            <li>
                                <span class="font-weight-bold mr-3">2006</span>
                                <span>Posturologie</span>
                                <span class="font-weight-bold ml-3">CINETIC SANTE Paris</span>
                                <img class="ml-3" src="/cinetic_logo.jpg" alt="cinetic_logo">                                        
                            </li>
                            <li>
                                <span class="font-weight-bold mr-3">2007</span>
                                <span>Podopédiatrie</span>
                                <span class="font-weight-bold ml-3">CINETIC SANTE Paris</span>
                                <img class="ml-3" src="/cinetic_logo.jpg" alt="cinetic_logo">                                        
                            </li>
                            <li>
                                <span class="font-weight-bold mr-3">2015</span>
                                <span>Posturologie</span>
                                <span class="font-weight-bold ml-3">BRICOT Paris</span>
                                <img class="ml-3" src="/bricot_logo.png" alt="bricot_logo">                                        
                            </li>
                            <li>
                                <span class="font-weight-bold mr-3">2015</span>
                                <span>Posturologie</span>
                                <span class="font-weight-bold ml-3">VALLIER Perpignan</span>
                                <img class="ml-3" src="/villier_logo.jpg" alt="villier_logo">                                        
                            </li>
                        </ul>                  
                    </div>
                </div>
            </div>

            <div class="bg-white mt-5 p-3">
                <div class="row">
                    <div class="col-1 text-center">
                        <fa class="text-muted text-32" :icon="['fa', 'euro-sign']" />
                    </div>
                    <div class="col-11">
                        <h3>Tarifs</h3>
                        <hr>
                        <div class="d-flex justify-content-between">
                            <span>Pédicure</span>
                            <span>33 €</span>
                        </div>                  
                    </div>
                </div>
            </div>

        </div>
	</section>
</template>

<script>
    export default {}
</script>

<style>
    .text-32 {
        font-size: 32px;
    }
    ul {
        padding: 0;
        list-style-type: none;

    }
    li {
        padding-bottom: 1rem;
    }
    .text-red {
        color: red;
    }
    .circle {
        text-align: center;
        width: 55px;
        height: 55px;
        line-height: 27px;
        background-color: white;
        border-radius: 35px;
    }
</style>


<template>
	<section class="bg-grey">
        <h1 class="banner-h1">Contact</h1>
        <img class="w-100 h-auto" src="/contact_banner.jpg" alt="contact_banner">

        <div class="container">
            <div class="bg-white mt-md-5 mt-3 p-3">
                <div class="row">
                    <div class="col-md-2 col-4">
                        <img class="w-100 h-auto" src="/sandrine_daubron.jpg" alt="sandrine_daubron">                    
                    </div>
                    <div class="col-md-10 col-8">
                        <div class="d-flex justify-content-between">
                            <h1>Pédicure Podologue Orsay</h1>
							<div class="d-none d-md-block">
								<a class="btn py-2 px-4 text-20-xs d-flex align-items-center" target="_blank" rel="noreferrer" href="https://www.doctolib.fr/pedicure-podologue/orsay/sandrine-daubron/">
									<span>Prendre rendez-vous</span>
									<fa class="ml-2" :icon="['fa', 'angle-right']" />
								</a>
							</div>
                        </div>
                        <h2 class="text-20-xs text-bold">Sandrine Daubron</h2>
                        <p class="text-muted d-none d-md-block">
                            Je vous accueille dans mon cabinet au 1 rue des Mésanges à Orsay. 
                            N'hésitez pas à me contacter pour une urgence directement par téléphone au 01 69 28 07 65.
                            Je me déplace à domicile le jeudi sur les communes d'Orsay, Bures et Villebon.
                        </p>
                    </div>
                </div>

				<!-- ONLY MOBILE -->
				<div class="d-block d-md-none mt-3">
					<p class="text-muted">
						Je vous accueille dans mon cabinet au 1 rue des Mésanges à Orsay. 
						N'hésitez pas à me contacter pour une urgence directement par téléphone au 01 69 28 07 65.
						Je me déplace à domicile le jeudi sur les communes d'Orsay, Bures et Villebon.
					</p>
					<a class="mt-4 btn py-2 px-4 text-20-xs d-flex align-items-center d-block d-md-none" target="_blank" rel="noreferrer" href="https://www.doctolib.fr/pedicure-podologue/orsay/sandrine-daubron/">
						<span>Prendre rendez-vous</span>
						<fa class="ml-2" :icon="['fa', 'angle-right']" />
					</a>
				</div>
            </div>

            <div class="bg-white mt-3 p-3">
                <div class="row">
                    <div class="col-md-1 col-2 text-center">
                        <fa class="text-muted text-32" :icon="['fa', 'euro-sign']" />
                    </div>
                    <div class="col-md-5 col-10">
                        <h3>Remboursements</h3>
                        <ul>
                            <li>Conventionné</li>
                            <li>Carte vitale non accepté</li>
                            <li>Tiers payant: Sécurité sociale</li>
                        </ul>                  
                    </div>
                    <div class="col-md-1 col-2 text-center">
                        <fa class="text-muted text-32" :icon="['fa', 'money-check']" />
                    </div>
                    <div class="col-md-5 col-10">
                        <h3>Moyens de paiement</h3>
                        <div class="text-red">Cartes bancaires non acceptées</div>                 
                        <div>Chèques et espèces</div>                 
                    </div>
                </div>
            </div>

            <div class="bg-white mt-3 p-3">
                <div class="row">
                    <div class="col-md-1 col-2 text-center">
                        <fa class="text-muted text-32" :icon="['fa', 'map-marker-alt']" />
                    </div>
                    <div class="col-md-5 col-10">
                        <h3>Informations d'accès</h3>
                        <p>1 rue des mésanges, 91400 Orsay</p>
                        <h6 class="font-weight-bold">Moyen de transport:</h6>
                        <ul>
                            <li>RER B - Orsay Ville</li>
                            <li>RER B - Le Guichet</li>
                        </ul>                  
                    </div>
                    <div class="col-md-6 col-12">
                        <img class="w-100 h-auto" src="/entry_building.jpg" alt="entry_building">                                        
                    </div>
                </div>              
            </div>

            <div class="bg-white mt-3 p-3">
                
                <div class="row">
                    <div class="col-md-1 col-2 text-center">
                        <fa class="text-muted text-32" :icon="['fa', 'graduation-cap']" />
                    </div>
                    <div class="d-block d-md-none col-8">
                        <h3 class="mb-2">Formations</h3>
                    </div>
                    <div class="col-md-11 col-12">
                        <h3 class="mb-2 d-none d-md-block">Formations</h3>
                        <table class="table">
                            <tbody>
                                <tr>
                                    <th scope="row">1991</th>
                                    <td>Diplôme d'état de Pédicure Podologue</td>
                                    <td class="text-bold">ASSAS Paris</td>
                                    <td>
                                        <img class="ml-3" src="/assas_logo.png" alt="assas_logo">
                                    </td>
                                </tr>
                                <tr>
                                    <th scope="row">2001</th>
                                    <td>Diabétologie</td>
                                    <td class="text-bold">SALPETRIERE Paris</td>
                                    <td>
                                        <img class="ml-3" src="/salpetriere_logo.png" alt="salpetriere_logo">
                                    </td>
                                </tr>
                                <tr>
                                    <th scope="row">2005</th>
                                    <td>Podologie du sport</td>
                                    <td class="text-bold">CINETIC SANTE Paris</td>
                                    <td>
                                        <img class="ml-3" src="/cinetic_logo.jpg" alt="cinetic_logo">
                                    </td>
                                </tr>
                                <tr>
                                    <th scope="row">2006</th>
                                    <td>Posturologie</td>
                                    <td class="text-bold">CINETIC SANTE Paris</td>
                                    <td>
                                        <img class="ml-3" src="/cinetic_logo.jpg" alt="cinetic_logo">
                                    </td>
                                </tr>
                                <tr>
                                    <th scope="row">2007</th>
                                    <td>Podopédiatrie</td>
                                    <td class="text-bold">CINETIC SANTE Paris</td>
                                    <td>
                                        <img class="ml-3" src="/cinetic_logo.jpg" alt="cinetic_logo">
                                    </td>
                                </tr>
                                <tr>
                                    <th scope="row">2015</th>
                                    <td>Posturologie</td>
                                    <td class="text-bold">BRICOT Paris</td>
                                    <td>
                                        <img class="ml-3" src="/bricot_logo.png" alt="bricot_logo">
                                    </td>
                                </tr>
                                <tr>
                                    <th scope="row">2015</th>
                                    <td>Posturologie</td>
                                    <td class="text-bold">BRICOT Paris</td>
                                    <td>
                                        <img class="ml-3" src="/villier_logo.jpg" alt="villier_logo">
                                    </td>
                                </tr>
                            </tbody>
                        </table>                  
                    </div>
                </div>
            </div>

            <div class="bg-white mt-3 p-3">
                <div class="row">
                    <div class="col-md-1 col-2 text-center">
                        <fa class="text-muted text-32" :icon="['fa', 'euro-sign']" />
                    </div>
                    <h3 class=" col-10 d-block d-md-none">Tarifs</h3>

                    <div class="col-md-11 col-12">
                        <h3 class="d-none d-md-block">Tarifs</h3>
                        <hr>
                        <div class="d-flex justify-content-between">
                            <span>Soins de pédicure</span>
                            <span class="text-bold">33 €</span>
                        </div>                  
                        <hr>
                        <div class="d-flex justify-content-between">
                            <span>Semelles orthopédiques</span>
                            <span class="text-bold">95 € à 110 €</span>
                        </div>                  
                        <hr>
                        <div class="d-flex justify-content-between">
                            <span>Bilan podologique/posturologique</span>
                            <span class="text-bold">30 €</span>
                        </div> 
                        <hr>
                        <div class="d-flex justify-content-between">
                            <span>Orthoplastie</span>
                            <span class="text-bold">20 € à 60 €</span>
                        </div> 
                        <hr>
                        <div class="d-flex justify-content-between">
                            <span>Réfléxologie</span>
                            <span class="text-bold">55 €</span>
                        </div> 
                        <p class="mt-3 text-muted">
                            Ces honoraires vous sont communiqués à titre indicatif par le praticien. Ils peuvent varier selon le type de soins finalement réalisés en cabinet,
                            le nombre de consultations et les actes additionnels nécessaires
                        </p>               
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
    h3 {
        line-height: 36px;
    }
    .text-32 {
        font-size: 32px;
    }
    td, th {
        vertical-align: middle !important;
        border: none !important;
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


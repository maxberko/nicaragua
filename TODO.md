# TODO — Nicaragua Surf Map

## 🔴 Passe de vérification Chinandega (priorité avant le trip)

Stormrider ne couvre pas la région Chinandega (s'arrête à Poneloya, ~12.37°N). Les 9 spots suivants reposent sur des sources tierces (Surfline, Rise Up, Lush Palm, Coco Loco, Nomad in Me, etc.) et leurs coords/classifications n'ont pas le même niveau de confiance que le reste de la map.

Spots à re-vérifier avec au moins 2 sources cartographiques indépendantes :

- [ ] **#25 La Isla Aserradores / The Island** — coords 12.625, -87.370 (offshore)
- [ ] **#26 Powder Puffs** — coords 12.629, -87.349 (offshore)
- [ ] **#27 The Boom (Aserradores)** — coords 12.631, -87.348 (classé "verified" mais via Mapcarta seul)
- [ ] **#28 Coconuts** — coords 12.632, -87.348 (offshore)
- [ ] **#29 Rocky Point** — coords 12.640, -87.395 (offshore)
- [ ] **#30 Meatgrinders** — coords 12.643, -87.398 (offshore)
- [ ] **#31 Santa María del Mar** — coords 12.650, -87.402 (approx)
- [ ] **#32 Jiquilillo** — coords 12.734, -87.442 (verified via DateAndTime + Maplandia, OK)
- [ ] **#33 Coco Loco** — coords 12.790, -87.495 (approx)

**Méthode recommandée :**
1. Pour chaque spot, chercher sur Wannasurf / Magicseaweed / Surf-Forecast une coord cartographique (pas juste nom de plage).
2. Cross-check avec Google Maps satellite (rivermouth visible, point reef visible ?).
3. Pour The Boom specifically : vérifier l'orientation de la plage (devrait être face à SW pour prendre la houle).

## 🟡 Cas ambigu à trancher

- [ ] **#16 Asuchillo** vs **Playa Ausuchillas (Gran Pacifica)** — probablement deux spots différents malgré la similarité de nom. Notre Asuchillo à 12.084°N (près d'El Tránsito) n'est pas celui de Stormrider à 11.933°N (Gran Pacifica). À confirmer sur Google Maps.

## 🟢 Améliorations futures

- [ ] Basculer toutes les coords des spots restants sur les valeurs Stormrider (JSON-LD) quand dispo — ils sont plus précis que latlong.net/mapcarta
- [ ] Ajouter un champ "swell window" exploitable par filtre (S-SW / S-W / SW-W / S-NW) depuis les données Stormrider
- [ ] Vue mobile : popups trop grandes sur petits écrans
- [ ] Intégration Surfline forecast via iframe ou API ?

## ✅ Fait

- ✅ Carte Leaflet satellite interactive avec filtres 4 critères
- ✅ KML pour Google My Maps (mobile/offline)
- ✅ 3 corrections crowd (Puerto Sandino → haute, Playgrounds → moyenne, Asuchillo → moyenne)
- ✅ Retrait El Yanke (niveau beginner, hors scope)
- ✅ Ajout 4 spots Stormrider-sourcés : Sally Ann's, Playa Rosada, Chiggas, Hemorrhoids
- ✅ Dataset de référence Stormrider extrait (data/stormrider-nicaragua.json)
- ✅ Déploiement GitHub Pages : https://maxberko.github.io/nicaragua/

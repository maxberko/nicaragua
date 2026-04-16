# Nicaragua Surf Trip — Juillet

Carte interactive des 33 meilleurs spots de surf au Nicaragua pour juillet, niveau avancé, sud→nord (Rivas → León → Chinandega).

## 🌐 Carte en ligne

👉 [Voir la carte](https://maxberko.github.io/nicaragua/) · [source HTML](./nicaragua-surf-spots.html)

## 📁 Fichiers

- `nicaragua-surf-spots.html` — carte Leaflet satellite interactive avec filtres (catégorie / marée / fréquentation / accès)
- `nicaragua-surf-spots.kml` — à importer dans [Google My Maps](https://www.google.com/maps/d/) pour accès mobile & offline
- `data/stormrider-nicaragua.json` + `.md` — dataset de référence Stormrider (29 spots, coords JSON-LD autoritaires)
- `TODO.md` — travail restant (priorité : re-vérification Chinandega)

## 🏄 Spots inclus (33)

- **Rivas (sud, 12)** : Sally Ann's, Hermosa SJDS, Manzanillo, Gigante, Colorado, Panga Drops, Playa Rosada, Santana, Popoyo Outer, Popoyo Main, Lance's Left, Playgrounds
- **León (centre, 12)** : Chiggas, Hemorrhoids, El Tránsito, Asuchillo, El Velero, Shacks, Miramar Punta, Outside Miramar, Pipes, Puerto Sandino (Freight Trains), Salinas Grandes, Las Peñitas/Poneloya
- **Chinandega (nord, 9)** : La Isla Aserradores, Powder Puffs, The Boom, Coconuts, Rocky Point, Meatgrinders, Santa María del Mar, Jiquilillo, Coco Loco

## 📍 Méthode de vérification des coordonnées

- ✓ **Vérifiées** : coords extraites de sources cartographiques (Stormrider JSON-LD pour les spots Stormrider, latlong.net/mapcarta/worldplaces.me/maplandia pour les autres)
- ~ **Offshore** : offset depuis un repère terrestre vérifié
- ⚠️ **Approximatives** : coordonnées introuvables dans les bases publiques, position estimée depuis la géographie du littoral

**Niveaux de confiance :**
- 🟢 Spots Stormrider (Rivas + León zone reef cluster) = coords JSON-LD extraites directement du code source des pages Stormrider (celles que Mapbox utilise). Très fiables.
- 🟡 Spots hors-Stormrider (Chinandega + spots SJDS hors-Stormrider comme Hermosa) = sources tierces, à re-vérifier (voir TODO.md).

Toutes les données factuelles (taille de houle, marée idéale, fréquentation, accès, hébergements) sont sourcées sur 2 sources indépendantes minimum. Les spots avec 🚩 n'ont qu'une seule source.

## 🔄 Changements récents

- Ajout de 4 spots Stormrider-sourcés : Sally Ann's (#1), Playa Rosada (#7), Chiggas (#13), Hemorrhoids (#14)
- Retrait de Playa Yankee (niveau beginner, hors scope "advanced")
- Corrections fréquentation : Puerto Sandino → haute, Playgrounds → moyenne, Asuchillo → moyenne
- Renumérotation strict sud→nord par latitude

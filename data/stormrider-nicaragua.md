# Nicaragua Surf Spots — Stormrider Reference Dataset

**Source:** stormrider.surf/nicaragua
**Extracted:** 2026-04-16
**29 spots** (28 full + 1 paywalled coords-only)
**Coordinates:** extracted from JSON-LD structured data embedded in each Stormrider spot page (same data Mapbox uses for pin placement — authoritative, not LLM-estimated)

## Dominant Patterns

- **Offshore wind:** NE trades dominate (27 of 28 full spots); exceptions: Sally Ann's (SE), Hemorrhoids/Ausuchillas/Masachapa (E)
- **Swell window:** S–SW (with some S–W and one S–NW at Salinas Grandes)
- **Best season:** Dec–April (dry season, clean trades)
- **July (rainy season):** more variable winds, but solid SW pulses — target early-morning offshore windows

## Regional Breakdown

**Southern Nicaragua (Rivas — 12 spots):** Popoyo to San Juan del Sur zone. Includes 2 Stormrider ⭐ Hotspots (Popoyo, Colorado), the heaviest stuff in the country (Panga Drops, Playa Santana, Sally Ann's), and beginner-friendly Maderas cluster.

**Central Nicaragua (17 spots):** León/Managua coast from Astillero in the south up to Poneloya in the north. Includes the famous Puerto Sandino (up to 400m rides), the Miramar reef cluster (Shacks/Punta/Pipes within 700m), and the lesser-known Gran Pacifica trio.

**Northern Nicaragua (Chinandega):** Not on Stormrider — earlier research suggested The Boom, Aserradores, Jiquilillo etc. Stormrider's northernmost spot is Poneloya (12.37°N).

## Spot Index (all 29)

| # | Spot | Region | Lat | Lon | Ability | Crowds | Type | Size (ft) | Tide |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Popoyo ⭐ | South | 11.458120 | -86.111567 | Intermediate | Often | Submerged Reef | 2–20 | All |
| 2 | Colorado ⭐ | South | 11.405374 | -86.048586 | Intermediate | Often | Rivermouth | 2–8 | All |
| 3 | Panga Drops | South | 11.407786 | -86.058230 | Intermediate | Sometimes | Submerged Reef | 3–18 | All |
| 4 | Playa Santana | South | 11.444013 | -86.089810 | Intermediate | Always | Beachbreak | 1–12 | All |
| 5 | Manzanillo | South | 11.365639 | -86.010144 | Intermediate | Often | Point Break | 2–10 | Mid only |
| 6 | Playa Rosada | South | 11.433898 | -86.084362 | Expert | Sometimes | Point Break | 3–8 | All |
| 7 | Playa Maderas | South | 11.290682 | -85.909902 | Beginner | Often | Beachbreak | 2–10 | All |
| 8 | El Remanso | South | 11.220503 | -85.849452 | Beginner | Sometimes | Beachbreak | 2–6 | All |
| 9 | Tamarind | South | 11.214659 | -85.846936 | Intermediate | Sometimes | Point Break | 3–6 | All |
| 10 | El Yanke | South | 11.180703 | -85.818291 | Beginner | Sometimes | Beachbreak | 2–6 | All |
| 11 | El Coco | South | 11.157953 | -85.804245 | Beginner | Sometimes | Beachbreak | 2–6 | Mid–High |
| 12 | Sally Ann's | South | 11.131363 | -85.800260 | Expert | Sometimes | Point Break | 4–10 | Mid–High |
| 13 | Hemorrhoids | Central | 11.924235 | -86.619570 | Intermediate | Often | Submerged Reef | 3–12 | Mid–High |
| 14 | Ausuchillas | Central | 11.932570 | -86.620096 | Beginner | Sometimes | Beachbreak | 1–12 | All |
| 15 | Chiggas | Central | 11.905297 | -86.619170 | Intermediate | Sometimes | Submerged Reef | 3–15 | Mid–High |
| 16 | El Transito | Central | 12.053120 | -86.707388 | Beginner | Rarely | Beachbreak | 1–6 | All |
| 17 | Montelimar | Central | 11.802237 | -86.521415 | Intermediate | Rarely | Beachbreak | 1–6 | Mid–High |
| 18 | Masachapa | Central | 11.784377 | -86.522106 | Intermediate | Rarely | Submerged Reef | 3–8 | Low–Mid |
| 19 | Pochomil | Central | 11.752322 | -86.487088 | Intermediate | Rarely | Submerged Reef | 1–10 | All |
| 20 | Shacks – Miramar | Central | 12.164726 | -86.760827 | Intermediate | Sometimes | Submerged Reef | 4–8 | Mid only |
| 21 | Punta Miramar 🔒 | Central | 12.168997 | -86.763407 | Paywalled | — | — | — | — |
| 22 | Pipes – Miramar | Central | 12.171291 | -86.764239 | Intermediate | Sometimes | Beachbreak | 2–8 | All |
| 23 | Puerto Sandino | Central | 12.189034 | -86.775136 | Intermediate | Often | Submerged Reef | 3–12 | All |
| 24 | Casares | Central | 11.646663 | -86.360652 | Intermediate | Rarely | Submerged Reef | 3–10 | All |
| 25 | Salinas Grandes | Central | 12.262410 | -86.869567 | Beginner | Rarely | Beachbreak | 1–8 | All |
| 26 | Playgrounds | Central | 11.555419 | -86.220714 | Intermediate | Sometimes | Submerged Reef | 3–12 | All |
| 27 | Lance's Left | Central | 11.522593 | -86.178598 | Intermediate | Sometimes | Point Break | 3–15 | All |
| 28 | El Astillero | Central | 11.518054 | -86.173693 | Intermediate | Rarely | Beachbreak | 2–10 | All |
| 29 | Poneloya | Central | 12.369045 | -87.036504 | Beginner | Rarely | Beachbreak | 1–8 | All |

## Clusters (near-identical coords)

- **Miramar headland** — Shacks (#20), Punta (#21), Pipes (#22) within ~700m
- **El Astillero zone** — Lance's Left (#27) + El Astillero beach (#28) ~450m apart
- **Gran Pacifica** — Hemorrhoids (#13), Ausuchillas (#14), Chiggas (#15) within ~1km

## Full descriptions

See `stormrider-nicaragua.json` for structured data (including all fields: pollution, parking, facilities, swell window per spot). Original narrative paragraphs preserved in source chat context only — re-fetch from Stormrider URLs if needed.

## Gap vs. prior map

Prior map had 30 spots mixing Stormrider data with Chinandega-region spots (The Boom, Aserradores, Jiquilillo, Coco Loco etc.) that **are not on Stormrider**. Those coords were LLM-sourced and should be re-verified from other authoritative sources before trusting them.

## Usage for future work

- **As trip data:** merge coords from this dataset into the HTML/KML map (replaces any hand-sourced south/central spots).
- **As baseline for the on-demand map generator:** this is a clean case study of "authoritative source with structured data" — the scraper should always look for JSON-LD / schema.org markup first before falling back to LLM extraction.
- **Licensing reminder:** Stormrider content is copyrighted; internal/personal use OK, but redistributing the full text publicly would require permission.

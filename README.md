# Skhoron Maps

A simple, flexible map viewer with search and route planning — with no proprietary server infrastructure, running entirely on the client side.

Features

- View maps from the entire planet down to street level (MapLibre GL + PMTiles)
- Search for cities, countries, and addresses
- Plan routes with alternative options
- Travel profiles: walking / driving / cycling

Tech Stack

- Maps: MapLibre GL JS + PMTiles (Protomaps)
- Routing: Valhalla (public FOSSGIS instance)
- Search: Photon (public Komoot instance)

For details about data sources and their terms of use, see ""docs/sources.md"" (docs/sources.md).

Structure

src/
├── map/       # Map initialization and styles
├── search/    # Geocoding
├── routing/   # Route planning
└── config/    # All external endpoints in one place

License

MPL 2.0 — see "LICENSE" (LICENSE).

Part of the Skhoron Ecosystem

Open-source, privacy-focused projects under the Skhoron brand.

GitHub: "Skhoron" (https://github.com/Skhoron)
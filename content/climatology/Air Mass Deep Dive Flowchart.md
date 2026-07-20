---
title: "Air Mass Deep Dive - Visual Flowcharts"
flowchart: true
---

# Air Mass Deep Dive - Visual Flowcharts

```mermaid
flowchart TD
    Title["AIR MASSES: INTRODUCTION & DYNAMICS"]
    Title --> Def["Definition & Properties"]
    Title --> Determinants["Determining Factors (8 Factors)"]
    Title --> Features["Core Dynamics"]

    Def --> Def_Bullets["• Air Mass: Extremely large body of air (hundreds of km horizontally) with relative uniformity of temperature, moisture/humidity, and lapse rate.<br>• Homogeneity: Distinctive similarity of physical properties within the bulk.<br>• Lapse Rate: The rate of decrease of atmospheric temperature with height.<br>• Fronts/Low Pressure: Located in transition zones between different air masses."]

    Determinants --> Det_Bullets["• Latitude & altitude<br>• Ocean current types<br>• Sunshine hours & angle<br>• Vegetation & soil temp<br>• Snow cover & prevailing wind"]

    Features --> Feat_Bullets["• Dry air is DENSER than moist air.<br>• Cold & dry air = STABLE (high density & molecular bulk).<br>• Warm & moist air = DRIFT/EXPAND (low density & molecular weight).<br>• Low pressure forces air mass movement (typically light, dry, inland-sourced).<br>• Mid-latitude zones: Can experience several different air mass types over a year.<br>• Tropical/Polar zones: More uniform weather. Tropics: wet/dry seasons, mild winters. Polar: temp depends on sun's angle."]

    style Title fill:#f1f5f9,stroke:#334155,stroke-width:2px
    style Def fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style Determinants fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style Features fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
```

---

## 2. Formation & Source Regions of Air Masses

```mermaid
flowchart TD
    Title["FORMATION & SOURCE REGIONS"]
    Title --> Gen["Primary Cause"]
    Title --> Source["Source Regions"]
    Title --> Warm["Warm Air Mass Formation"]
    Title --> Cold["Cold Air Mass Formation"]

    Gen --> Gen_Bullets["• Uneven warming and cooling of the Earth's surface by the Sun."]

    Source --> Source_Bullets["• Definition: Large surfaces with uniform temperature and humidity where air masses grow and originate.<br>• Terrain types: Ocean, desert, or snow-covered plains.<br>• Zones: Most common in tropics, subtropics, and high latitudes."]

    Warm --> Warm_Bullets["• Location: Equator or desert areas (max solar radiation).<br>• Process: Clear, cloudless days → heat reflected back to atmosphere → air becomes light and spreads."]

    Cold --> Cold_Bullets["• Location: Near the poles (min solar radiation).<br>• Process: Cloudless days + snow cover reflects sunlight away → prevents warming.<br>• Persistence: Long-period cooling forms cold air masses over large areas."]

    style Title fill:#f1f5f9,stroke:#334155,stroke-width:2px
    style Gen fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style Source fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style Warm fill:#fef2f2,stroke:#ef4444,stroke-width:1px
    style Cold fill:#f0fdf4,stroke:#16a34a,stroke-width:1px
```

---

## 3. Latitudinal Classification & Abbreviation Matrix

```mermaid
flowchart TD
    Title["CLASSIFICATION SYSTEM"]
    Title --> Lat["Latitudinal Temperature Types"]
    Title --> Matrix["Primary Classifications Matrix"]

    Lat --> Lat_Bullets["• Equatorial: Near the equator; classified as HOT.<br>• Tropical: Higher latitude than equatorial; classified as WARM.<br>• Polar: Higher latitude; ranges from COOL to COLD.<br>• Gradient: Temperature generally decreases POLEWARD."]

    Matrix --> Matrix_Bullets["• mT (Maritime Tropical): Maritime / Ocean source.<br>• mP (Maritime Polar): Maritime / Ocean source.<br>• cP (Continental Polar): Continental / Land source.<br>• cT (Continental Tropical): Continental / Land source.<br>• A (Arctic): Extreme Cold Polar variant.<br>• H (Highland): Elevation-based (not a single source)."]

    style Title fill:#f1f5f9,stroke:#334155,stroke-width:2px
    style Lat fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style Matrix fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
```

---

## 4. Detailed Profiles of Primary Air Masses

```mermaid
flowchart TD
    Title["DETAILED AIR MASS PROFILES"]
    Title --> mT["mT (Maritime Tropical)"]
    Title --> mP["mP (Maritime Polar)"]
    Title --> cP["cP (Continental Polar)"]
    Title --> cT["cT (Continental Tropical)"]
    Title --> A["A (Arctic)"]
    Title --> H["H (Highland)"]

    mT --> mT_Bullets["• Source: Gulf of Mexico, Gulf Stream (warm waters, huge evaporation). Warm currents destabilize atmosphere, add moisture, warm low levels. Cold currents stabilize it.<br>• Temp/Moisture: Dewpoint always >50°F; Summer temps 80s-90s°F, Winter 70s-80s°F.<br>• Activity: S.E. US, expands north in summer. Majority of US thunderstorms (scattered thermodynamic & pre-frontal storms) develop in mT air.<br>• Modification: Northward movement over land modifies it to continental traits (lower sun angles, drier/cooler land below)."]

    mP --> mP_Bullets["• Source: Cold ocean currents / high-latitude waters. Moisture not as high as mT, but ALWAYS near saturation.<br>• Weather: Fog, drizzle, cloudy, long-lasting light/moderate rain.<br>• Orographic Lifting: Produces widespread rain/snow on windward slopes. Lee side descent modifies it to a continental air mass.<br>• Fronts: Produces cold fronts (not as cold as Arctic); 'Pacific fronts' or 'back-door cold fronts'. Temp range: freezing to below 70°F."]

    cP --> cP_Bullets["• Features: Low dewpoints, cold, high stability. Denseness creates surface high pressure and trough aloft.<br>• Precipitation: Usually light (dryness). Most common on edges where it displaces mT air. Uplift via jet streaks, isentropic lift, PV advection. Convection inhibited by cold surface & dry boundary layer.<br>• Modification: Modifies rapidly moving South (dewpoints low, temp rises due to warmer soil, shallow air mass, high sun angles, no snow). Slowed by snow/cold soil, or subtropical jet overrunning. Becomes 'modified cP air' or 'modified mid-latitude continental air'."]

    cT --> cT_Bullets["• Source: Desert Southwest, High Plains, Mexico. Low dewpoints, hot afternoons, mild nights.<br>• Mid-level Advection: Buoyancy/elevation sends it to mid-levels → creates cap of mild dry air (Thermal Cap). Overrunning PBL mT air increases severe thunderstorm threat.<br>• Boundary: Separated from mT by a DRYLINE. Severe weather near dryline depends on dryline strength, convergence, and upper dynamics."]

    A --> A_Bullets["• Source: Northern Canada. Same as polar but COLDER with even LOWER dewpoints.<br>• Formation: Stationary high over Eastern Alaska/Yukon. Lack of winter solar radiation, snow/ice cover, and continuous terrestrial radiation cools air to -30°F to -60°F.<br>• Activity: Meridional jet sends very cold air to US; modifies to Polar then modified Polar behind cold fronts in Southern US."]

    H --> H_Bullets["• Topography: Large elevation changes over short distances (not one single source).<br>• Interior Dryness: Promotes interior dryness. mP and mT dry on leeward side via orographic descent.<br>• Blockade: cP air has difficulty entering due to high density (cold dense air cannot climb over high terrain). Air modifies due to extreme elevation changes."]

    style Title fill:#f1f5f9,stroke:#334155,stroke-width:2px
    style mT fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style mP fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style cP fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style cT fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style A fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style H fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
```

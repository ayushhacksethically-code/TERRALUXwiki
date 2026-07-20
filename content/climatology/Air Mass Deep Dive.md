## Technical Text: Air Mass Deep Dive

<details class="concept-map-toggle">
  <summary class="btn-toggle-map"><i class="fa-regular fa-map"></i> View Concept Map & Visual Flowcharts</summary>
  <div class="concept-map-container" style="background: #ffffff; padding: 15px;">
    
    <!-- Flowchart 1: INTRODUCTION & DEFINITION -->
    <div class="flowchart-header">1. Introduction & Definition of Air Masses</div>
    <div class="mermaid">
    flowchart TD
        Title["INTRODUCTION & DEFINITION OF AIR MASSES"]
        Title --> Def["Definition of an Air Mass"]
        Def --> Bullets["• Extremely large body of air in the atmosphere.<br>• Relatively huge bulk of air distinctive by its homogeneity of temperature & moisture content.<br>• Properties—temperature, humidity, and lapse rate (decrease of temp with height)—are largely uniform over an area.<br>• Uniform area can be several hundred kilometers across the surface of the earth."]
        style Title fill:#f1f5f9,stroke:#334155,stroke-width:2px
        style Def fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    </div>
    
    <div class="map-connector"></div>
    
    <!-- Flowchart 2: FEATURES OF AIR MASSES -->
    <div class="flowchart-header">2. Features & Determining Factors of Air Masses</div>
    <div class="mermaid">
    flowchart TD
        Title["FEATURES & FACTORS DETERMINING AIR MASSES"]
        Title --> Factors["Determining Factors (Character of Air Mass)"]
        Factors --> Factors_Bullets["Determined by:<br>• Latitude & altitude<br>• Types of ocean currents<br>• Sunshine hours & sunshine angle<br>• Natural vegetation & temperature of the soil<br>• Snow cover & prevailing wind"]
        
        Title --> Density["Density & Stability Differences"]
        Density --> Density_Bullets["• Dry air is denser than moist air.<br>• Cold and dry air masses are stable (higher density & higher average molecular bulk).<br>• Warm moist air masses are drifting (low density) and expand (lower molecular weight).<br>• Low pressure forces air mass movement (light, less moisture, generally sourced from inland)."]

        Title --> Regional["Regional & Latitudinal Characteristics"]
        Regional --> Regional_Bullets["• Mid-latitude zones: Can experience several different air mass types over a year.<br>• Tropical & Polar areas: More uniform weather throughout the year.<br>• Tropics: Wet rainy season, dry season, mild winters.<br>• Poles: Temperature depends almost completely on the angle of the sun (varies by season).<br>• Transition zones: Surface low pressure and fronts are most often found here."]

        style Title fill:#f1f5f9,stroke:#334155,stroke-width:2px
        style Factors fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
        style Density fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
        style Regional fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    </div>
    
    <div class="map-connector"></div>
    
    <!-- Flowchart 3: FORMATION OF AIR MASSES -->
    <div class="flowchart-header">3. Formation & Source Regions of Air Masses</div>
    <div class="mermaid">
    flowchart TD
        Title["FORMATION & SOURCE REGIONS"]
        Title --> Source["Source Regions (Tracts of ocean, desert, or snow-covered plains)"]
        Source --> Source_Bullets["• Large surfaces with uniform temperatures and humidity where air masses originate.<br>• Uneven warming and cooling of the earth's surface by the Sun gives rise to air masses.<br>• Most common in the tropics, subtropics, and high latitudes."]

        Title --> WarmMass["Warm Air Mass Formation"]
        WarmMass --> WarmMass_Bullets["• Form over the equator or desert areas where solar radiation is maximum.<br>• In clear, almost cloudless days, heat is reflected back to the atmosphere.<br>• The air becomes light and spreads."]

        Title --> ColdMass["Cold Air Mass Formation"]
        ColdMass --> ColdMass_Bullets["• Form near the poles where solar radiation is at a minimum.<br>• On cloudless days, snow cover reflects sunlight away, preventing warming.<br>• Cooling persisting for a long period forms cold air masses over a large area."]

        style Title fill:#f1f5f9,stroke:#334155,stroke-width:2px
        style Source fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
        style WarmMass fill:#fef2f2,stroke:#ef4444,stroke-width:1px
        style ColdMass fill:#f0fdf4,stroke:#16a34a,stroke-width:1px
    </div>
    
    <div class="map-connector"></div>
    
    <!-- Flowchart 4: CLASSIFICATION & PROFILE -->
    <div class="flowchart-header">4. Air Mass Classification & Detailed Profiles</div>
    <div class="mermaid">
    flowchart TD
        Title["CLASSIFICATION & DETAILED AIR MASS PROFILES"]
        Title --> mT["1. Maritime Tropical (mT)"]
        Title --> mP["2. Maritime Polar (mP)"]
        Title --> cP["3. Continental Polar (cP)"]
        Title --> cT["4. Continental Tropical (cT)"]
        Title --> A["5. Arctic (A)"]
        Title --> H["6. Highland (H)"]

        mT --> mT_Bullets["• Source: Warm waters of Gulf of Mexico & Gulf Stream (destabilize, add moisture, warm low levels).<br>• Temperature: Highs in 80s/90s (summer), 70s/80s (winter).<br>• Dewpoints: Always > 50°F (high dewpoints).<br>• Activity: S.E. US, expands in summer, moves equatorward in winter. Majority of US thunderstorms develop here.<br>• Modification: Over land it modifies to continental (lower sun angles, drier/cooler land below)."]

        mP --> mP_Bullets["• Source: Cold ocean currents or high-latitude ocean waters.<br>• Temperature: Just above freezing to below 70°F. Near saturation.<br>• Activity: Widespread rain/snow via orographic lifting. Produces fog, drizzle, cloudy weather, long-lasting light/moderate rain.<br>• Modification: Mountain ranges produce rain/snow on windward side; lee side modifies to continental (often Pacific/back-door fronts)."]

        cP --> cP_Bullets["• Features: Low dewpoints, cold temperatures, high degree of stability. Creates surface high pressure.<br>• Precipitation: Usually light due to dryness. Common on edges where it displaces mT air. Uplift via jet streaks, isentropic lift, PV advection.<br>• Modification: Modifies rapidly moving South (warmer soil, higher sun, lack of snow). Overrunning subtropical jet slows modification."]

        cT --> cT_Bullets["• Source: Desert Southwest, high plains, and Mexico.<br>• Features: Low dewpoints, warm-to-hot afternoons, mild nights.<br>• Advection: Moves into mid-levels creating a cap of mild dry air. If it advects over boundary layer mT, severe thunderstorms threat increases.<br>• Boundary: Separated from mT by a dryline (severe storm boundary)."]

        A --> A_Bullets["• Source: Northern Canada. Same as polar but colder with lower dewpoints.<br>• Formation: Stationary high over Eastern Alaska/Yukon. Lack of winter solar radiation, snow cover, and earth cooling drops temperatures to -30°F to -60°F.<br>• Activity: Meridional jet sends very cold air to US. Modifies to Polar then modified Polar behind cold fronts."]

        H --> H_Bullets["• Source: Not one specific region; occurs with large elevation changes over short distances.<br>• Features: High terrain promotes dryness in the interior.<br>• Modification: mP and mT dry on leeward side via orographic descent.<br>• Dynamics: cP has difficulty entering due to high density of cold dense air which cannot move over elevated terrain."]

        style Title fill:#f1f5f9,stroke:#334155,stroke-width:2px
        style mT fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
        style mP fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
        style cP fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
        style cT fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
        style A fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
        style H fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    </div>
    
  </div>
</details>

### Introduction & Definition

- Air mass is an extremely large body of air in the atmosphere.
- The properties of an air mass—temperature, humidity, and lapse rate (which is the decrease of atmospheric temperature with height)—are largely uniform over an area.
- The uniform area of an air mass can be several hundred kilometers across the surface of the earth.
- Climate science defines an air mass as a relatively huge bulk of air that is distinctive by its homogeneity of temperature and moisture content.

### Features of Air Masses

- Air masses are important natural occurrences that possess distinct structural features.
- Surface low pressure and fronts are most often found within transition zones.
- Dry air is denser than moist air.
- Cold and dry air masses are stable because they have a higher density and higher average molecular bulk.
- Warm moist air masses are drifting due to their low density.
- Warm moist air masses expand because they have a lower molecular weight.
- Low pressure forces air mass movement because it is light and contains less moisture.
- Low pressure air masses are generally sourced from inland areas.
- The mid-latitude zones are unique because they can experience several different air mass types over the course of a year.
- Tropical and Polar areas tend to have more uniform weather throughout the year.
- The tropics can experience a wet rainy season, a dry season, and mild winters.
- The temperature around the poles depends almost completely on the angle of the sun, which varies from season to season.
- The character of an air mass is determined by latitude, altitude, types of ocean currents, sunshine hours, sunshine angle, natural vegetation, temperature of the soil, snow cover, prevailing wind.

### Formation of Air Masses

- Air masses are most common in the tropics, subtropics, and high latitudes.
- The zones from which air masses grow are called "source regions".
- Source regions are generally tracts of ocean, desert, or snow-covered plains.
- Large surfaces with uniform temperatures and humidity where air masses originate are called source regions.
- Uneven warming and cooling of the earth's surface by the Sun gives rise to air masses.
- **Warm Air Mass**: Warm air masses form over the equator or desert areas where solar radiation is maximum.
- **Warm Air Mass**: In clear, almost cloudless days, the heat is reflected back to the atmosphere.
- **Warm Air Mass**: The air becomes light and spreads.
- **Cold Air Mass**: Cold air masses form near the poles where solar radiation is at a minimum.
- **Cold Air Mass**: On cloudless days, the snow cover near the Poles reflects sunlight away, preventing the earth from warming up.
- **Cold Air Mass**: When this cooling persists for a long period of time, cold air masses form over a large area.

### Classification of Air Masses

- The source regions and their climatic specifications classify the world's major air masses.
- An air mass is named by the combination of its humidity and temperature specificity.
- The type of temperature that an air mass acquires is derived from the latitude of origin.
- Air mass temperatures generally decrease poleward.
- Air masses originating near the equator are Equatorial and are considered hot air masses.
- At a higher latitude, the air masses are called tropical air masses and are considered warm air masses.
- Polar air masses are located at a still higher latitude and range from cool to cold, depending on the position of the sun.

#### Primary Classifications & Abbreviations

- $mT$ = Maritime Tropical
- $mP$ = Maritime Polar
- $cP$ = Continental Polar
- $cT$ = Continental Tropical
- $A$ = Arctic
- $H$ = Highland

### Detailed Air Mass Profiles

#### 1) Maritime Tropical Air Mass (mT)

- The maritime tropical air mass is most often felt in the Southeast US.
- In the winter, this air mass is shoved toward the equator.
- In the summer, it can cover much of the US east of the Rockies.
- This air mass results from the warm waters of the Gulf of Mexico and the Gulf Stream.
- The warm waters in this region evaporate an enormous volume of water.
- Cold water currents tend to stabilize the atmosphere and produce little evaporation.
- Warm waters destabilize the atmosphere, add moisture, and warm the low levels of the atmosphere.
- Temperatures in this air mass warm to highs in the 80's and 90's in the summer.
- Temperatures warm to highs in the 70's and 80's in the winter.
- High dewpoints characterize mT air.
- At all times of the year, dewpoints are greater than $50^{\circ}F$.
- The majority of US thunderstorm activity develops within the mT airmass.
- Most thunderstorm activity develops by way of scattered thermodynamic thunderstorms and thunderstorms out ahead of fronts.
- As the maritime tropical airmass moves over land, it begins to "pick up" characteristics of a continental climate.
- Continental modification is particularly true when the mT airmass moves toward the North.
- The mT airmass modifies due to lower sun angles, drier land below, and cooler land below.

#### 2) Maritime Polar Air Mass (mP)

- The source region for mP air is over cold ocean currents or high-latitude ocean waters.
- This air does not have the same moisture content as mT air.
- Since mP air is always near saturation, orographic lifting of the air mass can produce widespread rain or snow.
- This air mass is notorious for producing fog, drizzle, cloudy weather, and long-lasting light to moderate rain.
- The temperature of mP air ranges from just above freezing to below $70^{\circ}F$.
- mP air is modified as it moves over elevated terrain.
- On the windward side of mountain ranges, mP air can produce an abundance of rain and snow.
- Once on the lee side of mountains, the mP airmass modifies into a continental airmass.
- These air masses produce cold fronts, but the air is not as cold as polar or arctic fronts.
- They are often termed "Pacific fronts" or "back-door cold fronts".

#### 3) Continental Polar Air Mass (cP)

- This airmass has low dewpoints, cold temperatures, and a high degree of stability.
- The denseness of cP air creates surface high pressure and a trough aloft, especially when cP air moves into lower latitudes.
- Precipitation in association with cP air is usually light due to the dryness and low moisture capacity of the air.
- Precipitation is most common on the "edges" of cP air, especially where it intersects and displaces mT air.
- Precipitation within a cP air mass is elevated and dynamically induced.
- Dynamical uplift mechanisms include jet streaks, isentropic lifting, and positive differential vorticity advection.
- Cold surface temperatures and a dry boundary layer inhibit thermodynamic convection.
- cP air modifies rapidly as it moves to the South.
- The dewpoints remain low, but the temperature of this airmass increases when moving South due to warmer soil temperature, a shallower airmass, higher sun angles, and a lack of surface snow cover.
- cP air will modify less rapidly if soil temperatures are abnormally low to the south, especially if surface snow cover exists.
- On some occasions, the subtropical jet will "overrun" the shallow cP air.
- If overrunning occurs, the cP air will modify less rapidly due to a much-reduced solar heating.
- Once cP air modifies significantly, it no longer makes sense to label it Polar air.
- After modification, cP air becomes modified cP air or modified mid-latitude continental air.

#### 4) Continental Tropical Air Mass (cT)

- The source region for cT air is the desert Southwest, the high plains, and Mexico.
- The air has low dewpoints and warm to hot afternoon temperatures, but with mild nighttime temperatures.
- Due to the buoyancy and elevation of cT air across North America, this air will advect into the mid-levels of the atmosphere once it moves out of its source region.
- This advection creates a cap of mild dry air.
- If this air advects over PBL mT air, the severe thunderstorm threat increases significantly.
- The boundary of cT is most noticeable with the creation of a dryline.
- A dryline separates mT air from cT air.
- Depending on the strength of the dryline, convergence along the dryline, and the dynamics above the dryline, severe thunderstorms can form near a dryline boundary.

#### 5) Arctic Air Mass (A)

- The source region for A air is northern Canada.
- It has the same characteristics as Polar air, except it is colder with even lower dewpoints.
- This air often forms when a high-pressure area becomes nearly stationary over Eastern Alaska and the Yukon.
- Due to a near-lack of winter solar radiation, abundant surface snow/ice cover, and the continuous emission of radiation from the Earth's surface, the air will progressively become colder and colder.
- Temperatures can reach $-30^{\circ}F$ to $-60^{\circ}F$.
- If the jet stream becomes meridional during the same timeframe that Arctic air builds, very cold air will spread into Southern Canada and the US.
- Once Arctic air moves into the Southern US, it modifies to Polar air and then eventually to modified Polar Air behind the cold front boundary.

#### 6) Highland Air Mass (H)

- This air mass occurs in regions with large elevation changes over short distances.
- It is not a source region for one particular type of air mass.
- Since highland climates are in elevated terrain, they can promote dryness in the interior of the highland climate.
- When air masses enter a highland climate, they modify due to these elevation changes.
- mP and mT air is dried on the leeward side due to orographic descent.
- cP air has difficulty entering a highland climate due to the high density of the cP air.
- Cold dense air has difficulty moving over elevated terrain.

---
title: "Temperate Cyclone - Visual Flowcharts"
flowchart: true
---

# Temperate Cyclone - Visual Flowcharts

```mermaid
flowchart TD
    Title[NOMENCLATURE, SPATIAL-TEMPORAL DISTRIBUTION & FORMATION]
    Title --> N[NOMENCLATURE]
    Title --> D[DISTRIBUTION]
    Title --> FM[FORMATION MECHANISM]

    N --> N_Bullets["• Mid-latitude depressions<br>• Extra-tropical cyclones<br>• Frontal depressions<br>• Wave cyclones"]

    D --> D_Lat[LATITUDINAL RANGE]
    D --> D_Geo[GEOGRAPHIC REGIONS]
    D --> D_Mov[MOVEMENT & SEASON]

    D_Lat --> D_Lat_Text["35° to 65° in<br>both hemispheres"]
    D_Geo --> D_Geo_Text["Atlantic Ocean &<br>NW Europe"]
    D_Mov --> D_Mov_Text["West to East<br>More pronounced<br>in winter seasons"]

    FM --> FM_Mech[MECHANISM OF FORMATION]
    FM_Mech --> FM_Mech_Text["Wavelike twist/<br>perturbation on<br>convergent fronts<br>(Frontogenesis Zone:<br>35°-65° latitudes)"]

    style Title fill:#f1f5f9,stroke:#334155,stroke-width:2px
    style N fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style D fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style FM fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
```

---

## 2. Characteristics of Temperate Cyclone

```mermaid
flowchart TD
    Title[CHARACTERISTICS OF TEMPERATE CYCLONE]
    Title --> EC[EMERGENCE & CLASSIFICATION]
    Title --> FC[STRUCTURAL & FRONTAL COMPOSITION]
    Title --> AC[AIRFLOW & CIRCULATION<br>NORTHERN HEMISPHERE]

    EC --> EC_Bullets["• Storm systems in mid & high latitudes<br>• Away from tropics<br>• Also called:<br>  - Mid-latitude storms<br>  - Baroclinic storms"]
    
    FC --> FC_Bullets["• Low-pressure system<br>• Contains: Cold Front, Warm Front, Occluded Front<br>• Pockets of warm air compressed between forward & rear cold air<br>• Warm air climbs over cold air → clouds form ahead of warm front → rainfall"]

    AC --> AC_Bullets["• Cold air blows from the NORTH of the front<br>• Warm air blows from the SOUTH of the front<br>• Pressure drop initiates an ANTICLOCKWISE cyclonic circulation"]

    style Title fill:#f1f5f9,stroke:#334155,stroke-width:2px
    style EC fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style FC fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style AC fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
```

---

## 3. Frontal Definitions & Classifications

```mermaid
flowchart TD
    Title["FRONTAL DEFINITIONS AND CLASSIFICATIONS<br><br>FRONT (General): Convergence zone where warm & cold air masses meet.<br>Forms in regions with uniform temperature, air pressure, and humidity."]
    Title --> WF[WARM FRONT]
    Title --> CF[COLD FRONT]
    Title --> OF[OCCLUDED FRONT]

    WF --> WF_Bullets["• Effect of warm air is pronounced<br>• Northern Hemisphere: Southeast, right side of warm air movement<br>• Southern Hemisphere: Southeast, left side of warm air movement<br>• Caused by interaction of contrasting air masses"]

    CF --> CF_Bullets["• Effect of cold air is marked<br>• Northern Hemisphere: Northwest, right side of cold air movement<br>• Southern Hemisphere: Southwest, left side of cold air movement<br>• Caused by interaction of contrasting air masses"]

    OF --> OF_Bullets["• Meaning: Blocking/sealing of existence of fronts<br>• Physical: Complete removal of fronts from ground level<br>• Trigger: Cold air occupies ground space surrounding hairpin-turned, clubbed warm and cold fronts<br>• Lifespan: Short period<br>• Position: In suspension in the sky"]

    style Title fill:#f1f5f9,stroke:#334155,stroke-width:2px
    style WF fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style CF fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style OF fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
```

---

## 4. Origin of Temperate Cyclone: Polar Front Theory

```mermaid
flowchart TD
    Title["ORIGIN OF TEMPERATE CYCLONE: THE POLAR FRONT THEORY<br>(By Vilhelm Bjerknes, J. Bjerknes & Associates, 'Bergen School of Meteorologists', end of World War I)"]
    Title --> AMC[AIR MASS CONVERGENCE]
    AMC --> AMC_Text["Warm-humid air from Tropics + Dry-cold air from Poles = POLAR FRONT<br>(Occurs between sub-tropical highs & sub-polar lows)"]
    
    AMC_Text --> PII[PHYSICAL INTERACTION & INSTABILITY]
    PII --> PII_Bullets["• Cold air is denser/heavier → occupies LOWER ground space<br>• Warm sub-tropical air is MECHANICALLY PUSHED UP<br>• Instability is generated → LOW PRESSURE created at the junction<br>  (center of interaction where warm and cold fronts differentiate)"]

    PII_Bullets --> WFA[WAVE FORMATION & AIR MASS KINEMATICS<br>Northern Hemisphere Example]
    WFA --> WFA_Bullets["• Wave formation along front = thermal contrast indicator<br>• Air masses encroach on each other's domains:<br>  - Warm air mass moves NORTHWARD as Westerlies<br>  - Cold air mass originates from POLAR EASTERLIES, moving southward.<br>    As it feeds into the cyclone behind the cold front, it is deflected to<br>    become NORTH-WESTERLY WINDS.<br>• Ferrel's Law: All winds are deflected to the RIGHT<br>• Frontal Asymmetry created:<br>  - EASTERN part of front → Dominated by WARM air mass<br>  - WESTERN part of front → Dominated by COLD air mass<br>• The center of this interaction develops into the CENTRAL LOW-PRESSURE CORE or WAVE APEX of the cyclone.<br>• (Exact reverse is true for the Southern Hemisphere)"]

    style Title fill:#f1f5f9,stroke:#334155,stroke-width:2px
    style AMC fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style PII fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style WFA fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
```

---

## 5. Stages of Mid-Latitude Cyclone Development

```mermaid
flowchart TD
    Title[STAGES OF MID-LATITUDE CYCLONE DEVELOPMENT]
    Title --> S1[STAGE I: STATIONARY / BEGINNING]
    S1 --> S1_Bullets["• Cold air mass and warm air mass converge along a central axis<br>• Both air masses are almost stable and in contact with each other<br>• Temperature, moisture, and pressure differences exist but are not large enough to create large-scale instability<br>• Over time, warm air mass begins pushing toward the eastern side<br>• Cold air mass impacts become visible on the western side<br>• At late phase: straight/flat formed front is turned/bent by advancing forces"]

    S1_Bullets --> S2[STAGE II: YOUNG ADULT]
    S2 --> S2_Bullets["• Frontiers of two air masses become conspicuously different<br>• Northern Hemisphere: Warm front → eastern part | Cold front → western part<br>• Cold sector: area to north & northwest (cold air mass)<br>• Warm sector: area to south & southeast (warm air mass)<br>• Warm front exhibits more instability (more moisture)<br>• Cold front is relatively more stable (less moisture)<br>• Peak instability at exact junction where fronts meet (future WAVE APEX)<br>• Frontal junction becomes increasingly sharp<br>• Warm sector shrinks; frontal bend sharpens<br>• Warm air is mechanically pushed up → cools → condensation occurs<br>• Latent heat released → further lowered pressure at junction<br>• Cold air originating from Polar Easterlies is deflected right, becoming NORTH-WESTERLY WINDS behind the cold front<br>• Marks the beginning of cyclonic formation"]

    S2_Bullets --> S3[STAGE III: MATURE]
    S3 --> S3_Bullets["• Low air pressure fully initiated at WAVE APEX (driven by condensation)<br>• Low pressure attracts surrounding air<br>• Highly significant vertical updraft of air observed<br>• Direct intensification of Stage II processes<br>• Isobars become closer together (tightening)<br>• Pressure gradient becomes very sharp<br>• Swift updraft moves upward in a whirling manner<br>• Cold air mass invasion grows greater in velocity and area<br>• Warm sector becomes still smaller and continues shrinking<br>• Increasingly sharp turns of the two fronts (peak frontal angularity)<br>• Cyclones march toward eastern side (steered by westerlies)<br>• Brings rapidly changing weather conditions<br>• End of stage: combined front starts lifting above ground (onset of decline)"]

    S3_Bullets --> S4[STAGE IV: OCCLUSION]
    S4 --> S4_Bullets["• Two distinctly formed fronts are compressed; diffusion into one another<br>• Fronts culminate by merging into the OCCLUDED FRONT<br>• Cyclone starts declining: central low pressure (Wave Apex) gets weakened<br>• Overall intensity lowered; wind velocity on steady decline<br>• Convergence zone detaches completely from ground surface<br>• Ground level becomes entirely occupied by cold air<br>• Warm sector entirely shifted above ground<br>• Line of discontinuity exists only in the sky, no longer on the ground"]

    S4_Bullets --> S5[STAGE V: LATE OCCLUSION / DISSIPATION]
    S5 --> S5_Bullets["• Early occlusion: cyclone still dynamic & strong<br>• Late occlusion: cyclone substantially weakened<br>• More surface areas occupied exclusively by cold air mass (denser & heavier)<br>• Areas previously belonging to warm air are governed by cold air<br>• Pushed-up warm air cools (thermodynamic impact of cold air + adiabatic cooling)<br>• Low pressure is completely eliminated; atmosphere returns to normal<br>• Occluded front completely removed from sky = FINAL DISSIPATION"]

    style Title fill:#f1f5f9,stroke:#334155,stroke-width:2px
    style S1 fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style S2 fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style S3 fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style S4 fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style S5 fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
```

---

## 6. Key Definitions & Terminology

```mermaid
flowchart TD
    Title[KEY DEFINITIONS & TERMINOLOGY]
    Title --> B1[BASIC WEATHER MAP & PRESSURE TERMS]
    Title --> B2[FRONTAL SYSTEM TERMS]
    Title --> B3[CYCLONE STRUCTURE & DYNAMICS TERMS]
    Title --> B4[WIND & CIRCULATION TERMS]
    Title --> B5[AIR MASS & INSTABILITY TERMS]
    Title --> B6[CYCLONE CLASSIFICATION & ALTERNATIVE NAMES]

    B1 --> B1_Bullets["• CYCLONE: A low-pressure area enclosed by a number of isobars that are circular or elliptical.<br>• TROUGH: Elongated pressure system of low pressure.<br>• ISOBARS: Lines on a weather map joining places of equal atmospheric pressure.<br>• PRESSURE GRADIENT: The rate of change of atmospheric pressure over a given distance.<br>• LOW-PRESSURE AREA: A region where atmospheric pressure is lower than surrounding areas.<br>• SUB-TROPICAL HIGHS & SUB-POLAR LOWS: Semi-permanent belts of high and low pressure."]

    B2 --> B2_Bullets["• FRONT: Convergence zone where warm & cold air masses meet.<br>• FRONTOGENESIS: The process of formation of a front (35° to 65° latitudes).<br>• WARM FRONT: The front where warm air mass is active and advancing.<br>• COLD FRONT: The front where cold air mass is active and advancing.<br>• OCCLUDED FRONT: Formed when faster cold front overtakes warm front.<br>• OCCLUSION: Complete removal of fronts from ground level (suspended in sky).<br>• SURFACE OF DISCONTINUITY: Boundary zone between two different air masses."]

    B3 --> B3_Bullets["• WAVE APEX / CENTRAL LOW-PRESSURE CORE: Precise center of cyclonic circulation (no calm 'eye').<br>• WARM SECTOR: Area to south & southeast of warm front, dominated by warm air.<br>• COLD SECTOR: Area to north & northwest of cold front, dominated by cold air.<br>• POLAR FRONT: planetary-scale zone of discontinuity between tropical and polar air.<br>• WAVE (Polar Front Theory): wavelike twist/perturbation on polar front."]

    B4 --> B4_Bullets["• CORIOLIS EFFECT / FERREL'S LAW: Deflects winds to the right in NH, left in SH.<br>• WESTERLIES: Dominant mid-latitude winds steering cyclones West to East.<br>• POLAR EASTERLIES: Cold, dry polar winds feeding towards sub-polar lows.<br>• NORTH-WESTERLY WINDS: Cold polar easterlies deflected to become synoptic wind behind cold front."]

    B5 --> B5_Bullets["• AIR MASS: Large body of air with uniform temperature, pressure, humidity.<br>• WARM AIR MASS: Lighter, less dense, moisture-laden, tends to rise.<br>• COLD AIR MASS: Denser, heavier, contains less moisture, occupies ground space.<br>• INSTABILITY: State where air parcel continues to rise on its own accord.<br>• LATENT HEAT: Heat released when water vapor condenses into liquid.<br>• ADIABATIC COOLING: Cooling due to expansion as parcel rises."]

    B6 --> B6_Bullets["• TEMPERATE CYCLONE: Also known as Mid-Latitude Depressions, Extra-Tropical Cyclones, Frontal Depressions, Wave Cyclones, Mid-Latitude Storms, and Baroclinic Storms.<br>• ACTIVE ABOVE: 35° to 65° latitudes in both hemispheres.<br>• MOVEMENT: West to East, more winter active.<br>• DEVELOPMENT: Can develop over both oceanic and land surfaces.<br>• WEATHER IMPACT: Much of the variable/cloudy temperate zone weather."]

    style Title fill:#f1f5f9,stroke:#334155,stroke-width:2px
    style B1 fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style B2 fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style B3 fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style B4 fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style B5 fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
    style B6 fill:#e0f2fe,stroke:#0284c7,stroke-width:1px
```

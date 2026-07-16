## Map Projections: Classification, Properties, and Uses

### Introduction and System Core

- A map projection is a way to flatten a globe's surface into a plane surface, requiring a systematic transformation of latitudes and longitudes from a sphere to locations on a plane.

### Elements of Map Projection

- **Graticule:** The net of mutually intersecting parallels and meridians drawn to a certain scale based on specific cartographic principles. The procedures used to draw this network are called _graticulation_.
- **Generating Globe:** The small skeleton wire or glass model globe from which projections are generated. Parallels and meridians are shown by black lines (on glass globes) or wires (on wire globes) placed at true angular distances, acting as a geometrically accurate earth reduced in size.
- **Projection Plane:** A two-dimensional geometrical plane touching the generating globe upon which parallels and meridians are projected. In perspective plane projections, it touches the globe at a single point.
- **Developable Surface:** Projection surfaces (like cylinders, cones, or planes) that can be easily unfolded or developed into a flat two-dimensional plane. They are used because plane projections touch at a single point of tangency where distortion is zero, but distortion increases away from it; maximizing the contact area via developable surfaces minimizes this distortion.
- **Reduced Earth:** A model of the earth represented via a reduced scale on a flat sheet of paper. It is more or less a spheroid with a polar diameter shorter than its equatorial diameter, onto which the graticule network is transferred.
- **Parallels of Latitude:** Circles running around the globe parallel to the equator, maintaining a uniform distance from the poles. Each parallel lies wholly in a plane at a right angle to the earth's axis. They are unequal in length, ranging from points at the poles to the maximum circumference at the equator, and are demarcated from $0^\circ$ to $90^\circ$ North and South.
- **Meridians of Longitude:** Semicircles drawn in a north-south direction from pole to pole, where opposite pairs form a complete circle matching the globe's circumference. They lie wholly in their own planes and intersect at right angles along the globe's axis. The meridian of Greenwich is arbitrarily chosen as the $0^\circ$ reference longitude.
- **Global Properties:** Cartographers try to preserve four basic structural properties of the global surface using various projection methods:
  - Distance between any given points of a region.
  - Shape of the region.
  - Accuracy of the size or area of the region.
  - Direction of any one point bearing to another point.

### Classification Matrix of Projections

#### By Drawing Technique
- **Perspective Projections:** Drawn with the help of a source of light by projecting the graticule shadow of a globe onto a developable surface.
- **Non-perspective Projections:** Developed without using a light source or casting shadows onto surfaces that can be flattened.
- **Conventional / Mathematical Projections:** Derived purely by mathematical computation and formulae, bearing little relation to a direct projected optical image.

#### By Developable Surface
- A developable surface can be flattened, whereas a non-developable surface (like a sphere or globe) cannot be flattened without shrinking, breaking, or creasing.
- **Cylindrical Projections:** Made using a paper cylinder wrapped around the globe; parallels and meridians are projected onto it, and cutting the cylinder open creates a flat projection sheet.
- **Conical Projections:** Drawn by wrapping a paper cone around the globe to project the graticule shadow, which is then cut open into a flat sheet.
- **Zenithal Projections:** Obtained directly when a flat plane touches the globe at a single point. Typically touches at one of the poles, but can be subdivided based on the point of tangency:
  - _Equatorial / Normal Projection:_ Tangent surface touches at the equator.
  - _Oblique Projection:_ Tangent surface is tangential to a point between the pole and the equator.
  - _Polar Projection:_ Tangent surface is tangential directly at the pole.

#### By Preserved Global Property
- No single projection can preserve all global properties simultaneously.
- **Equal Area / Homolographic Projection:** Correctly represents the areas of various parts of the earth.
- **Orthomorphic / True-Shape Projection:** Portrays the shapes of various areas correctly, which is generally achieved at the cost of area accuracy.
- **Azimuthal / True-Bearing Projection:** Correctly represents the direction of all points from the center of the map.
- **Equi-distant / True Scale Projection:** Correctly maintains scale or distance, though no projection can maintain scale perfectly throughout; it is limited to selected parallels and meridians.

#### By Source of Light Location
- **Gnomonic Projection:** Light source is placed at the exact center of the globe.
- **Stereographic Projection:** Light source is placed at the periphery of the globe at a point diametrically opposite to where the projection plane touches the surface.
- **Orthographic Projection:** Light source is placed at infinity from the globe, directly opposite to the point of tangency of the plane surface.

### Structural Analysis of Selected Projections

#### Simple Conical Projection with One Standard Parallel
- Drawn by projecting a globe's graticule onto a developable cone touching the globe along a single parallel of latitude called the _standard parallel_ (coinciding along line AB).
- **Properties:**
  - All parallels are concentric circles with the pole as their common center.
  - All meridians are straight lines merging at the pole, intersecting parallels at right angles.
  - Scale along all meridians is true (accurate distances).
  - Scale is true along the standard parallel but becomes exaggerated moving away from it.
  - Meridians become closer to each other towards the pole.
  - The projection is neither equal area nor orthomorphic.
- **Uses:** Showing mid-latitude areas with limited latitudinal and larger longitudinal extent; narrow strips of land running east-west parallel to the standard parallel. Used for railways, roads, narrow river valleys, international boundaries, the Canadian Pacific Railways, Trans-Siberian Railways, the US-Canada boundary, and the Narmada Valley.
- **Limitations:** Unsuitable for world maps due to extreme distortion in the opposite hemisphere; unsuitable for large areas within the hemisphere due to heavy distortion near the pole and equator.

#### Conical Projection with Two Standard Parallels
- An improvement over the simple conical projection, featuring two standard parallels instead of one to allow a greater north-south or longitudinal extent to be correctly represented. It is a non-perspective projection because a single physical cone can only touch a globe along one parallel. Standard parallels are selected to cover two-thirds of the target latitudinal extent.
- **Properties:**
  - All parallels are arcs of concentric circles.
  - All meridians are straight lines radiating from the pole as radii of concentric curves.
  - Scale is true along both selected standard parallels.
  - Scale is true along all meridians.
  - Distances between the standard parallels are shorter than actual distances, while distances beyond them are longer than actual distances.
- **Uses & Limitations:** Identical to the simple conical projection, it is used for mid-latitude areas with large east-west stretch to show infrastructure and borders, but cannot show a full world map due to high peripheral distortions.

#### Cylindrical Equal Area Projection (Lambert's Projection)
- Derived by projecting the globe surface with parallel light rays onto a cylinder touching it at the equator. Parallels and meridians project as straight lines intersecting at right angles. The poles are stretched into lines equal in length to the equator, causing severe shape distortion at high latitudes.
- **Properties:**
  - All parallels and meridians are straight lines intersecting at right angles.
  - The polar line is equal in length to the equator.
  - Scale is true only along the equator.
- **Uses:** Most suitable for areas lying between $45^\circ$ N and S latitudes; ideal for showing the distribution of tropical crops like rice, tea, coffee, rubber, and sugarcane.
- **Limitations:** Distortion increases rapidly towards the poles; it is non-orthomorphic, maintaining equality of area at the expense of severe shape distortion.

#### Mercator's Projection
- Developed by Dutch cartographer Mercator Gerardus Karmer in 1569. Based entirely on mathematical formulae, making it an orthomorphic projection where true shape is maintained. Parallels and meridians intersect at right angles, and the distance between parallels increases towards the poles. A straight line joining any two points gives a constant bearing, known as a _Laxodrome_ or _Rhumb line_.
- **Properties:**
  - Parallels and meridians are straight lines intersecting at right angles.
  - All parallels have the same length, which equals the length of the equator.
  - All meridians have the same length and equal spacing, but are longer than corresponding meridians on the globe.
  - Spacing between parallels increases towards the poles.
  - Shape of small areas is preserved near the equator, but distortion takes place at higher latitudes.
  - It is an azimuthal and orthomorphic projection, as the scale along the meridian equals the scale along the parallel.
- **Uses:** Highly suitable for world maps and atlas maps; critical for navigation showing sea and air routes; ideal for portraying drainage patterns, ocean currents, winds, temperatures, and worldwide rainfall distributions.
- **Limitations:** Extreme scale exaggeration in high latitudes makes polar countries appear far too large (e.g., Greenland appears equal in size to the USA, whereas it is actually $1/10\text{th}$ the size of the USA). The poles cannot be shown because the $90^\circ$ parallel and meridian are infinite.

#### Bonne's Projection
- A special case of an equal-area conical projection designed by French cartographer Rigobert Bonne. It differs because all parallels are drawn true to scale. Only one central standard parallel has its radius mathematically determined; the curvature of all other parallels depends on it. Meridians are drawn by dividing all parallels truly and connecting those points with smooth curves.
- **Properties:**
  - Parallels are concentric curves whose curvature depends on the selected standard parallel.
  - Central meridian is a straight line; all other meridians are smooth curves.
  - Scale is true along all parallels.
  - Scale is correct along the central meridian only, causing shape distortion to increase away from it.
  - It is an equal-area projection, as the area of each map quadrangle equals its corresponding globe quadrangle.
  - Both height and base are true to scale.
- **Uses:** Used for atlas maps of continents and topographic mapping; widely used in the 19th and early 20th centuries for atlas maps of Asia, Australia, Europe, and North America.
- **Limitations:** Can only be used effectively to map a single hemisphere at a time.

#### Polar Zenithal Stereographic Projection
- Has its origin of light on the globe surface directly opposite the point of tangency, defining curved lines over more than half of the sphere. Meridians are straight lines that are close in the center and become widely spaced at the map periphery; parallels are drawn as circles. It maintains true shape (orthomorphic), making it highly applicable for aviation mapping.
- **Uses:** Polar aspect is commonly used for topographic maps of polar regions; equatorial aspect was used in the 17th and 18th centuries for maps of the Eastern and Western hemispheres; oblique aspects are used to plot the paths of solar eclipses.
- **Limitations:** Cannot be used to map the entire world's surface at once; the point directly opposite the projection origin must be excluded.
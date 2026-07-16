## Universal Transverse Mercator (UTM) Projection

### Definition and General Concepts

- The Universal Transverse Mercator (UTM) system is designed to provide a means of representing each point on the Earth (except for areas surrounding the Poles) using a set of Cartesian ($X, Y$ or $E, N$) coordinates.
- The benefits of representing points on the Earth with Cartesian coordinates are for easy planar mapping, easily deriving spatial information (e.g., distances, angles, areas, etc.) from points' coordinates, and the easy ability to calculate the coordinates of a point of interest based on spatial information.
- The trade-off for the easiness of these operations is often at the expense of the accuracy of the solution.
- The UTM system was adopted by the U.S. Army in 1947 for large-scale military maps of the entire world.
- In Canada, the UTM system has been utilized for many national and provincial mapping purposes.
- This geographic coordinate system is used universally to refer to any point on the earth's surface to easily locate any area of the planet.
- Projections are used to represent an object on a plane using geometries and the Cartesian axis.

### UTM Coordinates and Zones

- To solve the problem of the deformation of the projection of UTM coordinate maps, a spindle is introduced to divide the earth's surface.
- The entire surface has been divided into 60 spindles or zones of 6 degrees in longitude, resulting in 60 equal projections with their respective central meridian.
- Each spindle is divided as if it were a segment of an orange.
- To establish a better division, the spindles are numbered from 1 to 60 starting from the Greenwich meridian due east.
- Each spindle is divided into different areas that are named by a capital letter following the direction from south to north, beginning with the letter C and ending with the letter X.
- In order not to be confused, there are no vowels and no letters that can be confused with a number used for the zone letters.
- Each zone of UTM coordinates is expressed by a zone number and a zone letter.
- This area is made up of rectangular regions with a distance of 100 kilometers per side.
- The values of these coordinates are always positive so as not to confuse the readers.
- Cartesian $X$ and $Y$ axes are established on the spindle, the $X$ axis being the equator and the $Y$ axis the meridian.
- **Example Case study:** The UTM coordinate of the location of the City Council of A Coruña is "29T 548929 4801142".
- In this coordinate, "29" indicates the UTM zone, "T" indicates the UTM band, the first number (548929) is the distance in meters to the East, and the second number (4801142) is the distance in meters to the North.
- Each zone has a longitude of 6 degrees and a central meridian at 3 degrees longitude that divides it into two equal parts and is used for the UTM projection.
- For greater accuracy, each zone is divided by the parallel of origin at the Equator, splitting it into two equal parts according to the northern hemisphere and southern hemisphere.

### Cartesian Axis Configuration

- The central meridian and the Equator establish two Cartesian axes on the spindle to position a point across its entire surface.
- Visualizing this from a plane, the central meridian of the area is the Y axis while the Equator is the X axis.
- The horizontal axis has its origin in the central meridian of the area and has a value of 500000.
- This value decreases as we go west and increases when we go east to ensure positive values on this axis.
- The vertical axis has its origin in the Equator.
- In the northern hemisphere of the Equator, the vertical axis has the value 0 at the Equator, which increases towards the north until it reaches the value 10000000 at the North Pole.
- In the southern hemisphere, the Equator will have the value 10000000, which grows towards the south to ensure positive vertical axis values.

### Properties of the UTM

- **Shape:** Accurate representation of small shapes; minimal distortion of larger shapes within the zone.
- **Area:** Minimal distortion within each UTM zone.
- **Direction:** Local angles are true.
- **Distance:** Scale is constant along the central meridian but at a scale factor of 0.9996 to reduce lateral distortion within each zone.
- With this scale factor of 0.9996, lines lying 180 km east and west of and parallel to the central meridian have a scale factor of 1.

### Uses and Applications of the UTM

- Used for United States topographic quadrangles at a 1:100,000 scale.
- Many countries use local UTM zones based on the official geographic coordinate systems in use.
- Used for large-scale topographic mapping of the former Soviet Union.

### Advantages of the UTM

- The parallels and meridians are represented by lines that form a grid, achieving better precision when calculating distances or seeing where a certain point on the map is located.
- Distances are much easier to measure than with another coordinate system.
- The shape of landforms is preserved for smaller areas, allowing users to know the relief and the type of terrain that exists in a territory.
- Bearings and directions are easy to mark, allowing humans to establish different sea and air routes.

### Disadvantages of the UTM

- Distances are usually enlarged as we move away from the point of tangency of the sphere and the cylinder, in the direction perpendicular to the cylinder.
- Such deformation is much more important at high latitudes, causing the precision to decrease as we go to higher latitudes.
- At different latitudes, it does not maintain a fixed ratio between surfaces.
- The polar zones are not represented, despite these areas being important for different fields.

### False Easting and False Northing

- In order to avoid experiencing negative X coordinate values within a UTM zone, an offset is applied to the X Cartesian coordinates along the central meridian.
- An offset of +500,000m is applied to all X coordinates.
- As a result, any geodetic point that has a longitude equal to the central meridian's longitude will have a projected X coordinate equal to 500,000m.
- This concept is commonly called the false easting of the UTM zone and is common amongst all UTM zones.
- For northern UTM zones, there is no chance of experiencing negative Y Cartesian coordinates, and as such, no Y coordinate offset needs to be applied, resulting in an offset of 0m.
- This concept is commonly called the false northing of the UTM zone and is common amongst all northern UTM zones.

### Image 1: Global UTM Grid Mapping Visual

- The document displays a complete world grid map under the UTM indexing system.
- **Y-Axis grid zones (letters):** Marked from row C (bottom/south) up to row X (top/north), skipping vowels.
- Specifically visible row letters: C, D, E, F, G, H, J, K, L, M, N, P, Q, R, S, T, U, V, W, X.
- **X-Axis grid zones (numbers):** Columns are explicitly numbered sequentially from 1 to 60 spanning west to east around the globe.
- Specific numeric markers visible along the equator baseline: 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56, 57, 58, 59, 60.
- Geographic coordinate boundary markings shown along the map edges include: $72^{\circ}\text{S}$, $24^{\circ}\text{S}$, $0^{\circ}$, $24^{\circ}\text{N}$, $72^{\circ}\text{N}$, $84^{\circ}\text{N}$.
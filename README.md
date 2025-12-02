The maps in this repository display the locations of Chicano and Latino households in Boulder County. The most recent map, as I am writing this on 12/1/2025, is CLHP_map2.5.
The GeoJSON file contains all of the necessary data for the map. This map was created using Mapbox.

The map has buttons in the top left corner to automatically zoom to Boulder, Lafayette, Longmont, or Boulder County. 
Below those buttons, there are buttons to filter for all households, all households associated with the University of Colorado, or all households that include a college/university student.
Underneath, there is a year slider and a button that automatically cycles through the years on the slider (1916, 1926, 1936, 1946, 1955, 1965, 1975). As the years cycle, the map changes to reflect the locations of Chicano and Latino households in that year.
Each point on the map is a Chicano and Latino household. The blue dots represent CU, the gold dots represent CU students, and the gray dots represent unassociated households.
When these points are clicked on, a pop-up appears that displays the address, the residents, and their jobs (if available).
In the upper right corner, there is a search bar that allows the user to search either a name or an address. A drop-down appears, displaying matching people and addresses from the GeoJSON. 
To make this search more user-friendly, I used fuse.js.
Once the user selects a specific address, the map will zoom to that address, load the popup, and switch to the earliest year that address was inhabited or the specific person person lived there.

Once we have a project-specific Mapbox account, I will add the associated email and password.

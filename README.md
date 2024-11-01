## SC4020 Project 2 


### Grid Division

- Spatial Resolution: Each city is divided into 500-meter x 500-meter grid cells - Allows for a simplified view of movement within each city.

- Grid Layout: Each metropolitan area is represented by a 200 x 200 grid, where each cell corresponds to a specific 500m x 500m area - Allows for city-area movements 

### POI Data 
Provides information about amenities or landmarks within each 500m x 500m grid cell in each city.

#### Inside the POI Data 

- POI Category Table (POI_datacategories.csv): This table lists 85 different types of Points of Interest (POI). Each POI type has unique ID that maps it to a category (look up table)


- POI Distribution Data (0er city): 
    x, y: The grid coordinates of the cell
    category: The type of POI present in that grid cell  corresponding to an ID in POI_datacategories.csv.
    POI_count: The number of POIs of that specific category within the grid cell


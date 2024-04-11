# NRHP Building Sites of North Carolina

### Bivariate Point and Chloropleth Map

---

This is a bivariate map that displays the relationship between the number of National Historic Building Sites according to the [Department of the Interior, US](https://catalog.data.gov/dataset/national-register-of-historic-places-aea8f) (date accessed: 04/03/24). This data was represented as point features, using leaflet markers that had been stylized using Font-Awesome. The second data was a shapefile from [NC One Map](https://www.nconemap.gov/datasets/9728285994804c8b9f20ce58bae45899/explore) Using QGIS, the data was compiled to provide each county in NC with a count of points within each feature. The shapefiles and feature classes were then converted into geojsons for data display purposes.
This web map is intended to show any relationships with certain counties and the number of historic buildings within those areas. Title, legend, scalebar, points, and a chloropleth layer are all included features of the map. Interactivity lies in the popup feature when a historic building point is clicked. There was an attempt to use a seperate leaflet library to cluster the point layers for certain zoom levels, but this implementation did not work by deadline.
Please enjoy the map.

# shennum-lab1

<h3>Map can be accessed at: <a href="https://shennum.github.io/shennum-web/lab1/railways.html" target="_blank">https://shennum.github.io/shennum-web/lab1/railways.html</a></h3> 

![alt text](https://github.com/UBC-GEOS472-Spring2022/shennum-lab1/blob/main/screenshot_railway.JPG "Screenshot of railway map")

<p>Jones’ (2010) principle of ‘concept before compilation’ (p. 42) was a guiding one in the ideational phase of this map. My hope was two-fold: to move away from the highly abstracted conventional maps of railway lines that do not portray where trains actually go (see 
<a href="https://www.vy.no/globalassets/vy.no/filer-no/linjekart/nye-linjekart/linjekart-vy-norge2.pdf" target="_blank">here</a> for example), and to visualize the recent privatization of the Norwegian railway system. The map is thus created in such a way that members of the general public that are curious about the location of railways can see where in the landscape they go (e.g., over mountain ranges or through densely populated areas) and for those users to access more information on the privatization process by interacting with the map.</p>
  
<p>Following the notion that less important data ‘should complement the design and not compete with the more important data’ (Jones, 2010, p. 43), the color palette of population density layer is intended to not significantly stand out from the background layer. Following the advice of Muehlenhaus (2013, pp. 95-97), I chose to use light grey as the base map color and added a greyscale shaded relief so as not to add additional cognitive strain on the user. I found that using primary colors and one darker hue of grey for the railway lines was the most effective way of distinguishing them from each other and from other layers on the map.</p>
  
<p>Jones’ (2010) discussion of generalization also informed the map. The initial zoom level displaying Norway at a smaller scale does not display the name of the stations nor the station locations. This is a conscious choice so as to allow the users to first familiarize themselves with the way railway lines are positioned in relation to population clusters and the terrain. Stations names appear only as one zooms in, where I imagine the user intends to seek out more information about the railway lines. The map provides limited utility at a large scale – it is not meant for navigation within a city or town – so the zoom level is restricted. Other distracting elements such as road networks, administrative boundaries, and names of national parks are removed as they are not important to understand railway privatization. The station names correspond to city names so placename labels were removed. The outline of the Norwegian land borders is not particularly ideal for a north-facing map so the initial bearing is set to -60 degrees.</p>

<p>Overall, the map could be improved by making it so that when a user clicks on a railway line, all the necessary information appears at once. As I was unsure of how to add the necessary properties to the GeoJSON file after having uploaded it to Mapbox, the easiest way to work around this was to add symbols as substitutes that contain this information. The map can still be improved in order to make it more visually appealing – I found it necessary to compromise aesthetic qualities for contextual and thematic information.</p> 


<h3>Collaborations and help:</h3>
<p>I worked with Sarah Kelly on the map critique portion of this assignment and found her feedback on the use of popups and color choice to be particularly helpful. We also shared Mapbox webpages with each other that included instructions on how to add different elements to the map.</p>


<h3>Notes on data:</h3>
<p>Railway lines and railway stations were extracted from Open Street Map using <a href="https://overpass-turbo.eu/" target="_blank">Overpass turbo</a> and population density points were created by joining population data from Statistics Norway in the smallest statistical administrative unit (grunnkretser) with shapefiles from the Norwegian Mapping Authority. QGIS was used to obtain point data from these polygons with attributes.</p>


<h3>References:</h3>
<ul>
  <li>Jones, C. E. (2010). Cartographic Theory and Principles. In M. Haklay (Ed.), Interacting with geospatial technologies (pp. 37-65). John Wiley & Sons, Ltd. https://doi.org/10.1002/9780470689813.ch3</li> 

<li> Kartverket. (2022). Statistiske enheter grunnkretser. [Data files]. Retrieved from https://kartkatalog.geonorge.no/metadata/statistiske-enheter-grunnkretser/51d279f8-e2be-4f5e-9f72-1a53f7535ec1</li>  

<li> Muehlenhaus, I. (2013). Web cartography: Map design for interactive and mobile devices. CRC Press. https://doi.org/10.1201/b16229</li>      

<li> Statistisk Sentralbyrå. (2022). Grunnkretsenes befolkning (G) 1999 – 2022. [Data files]. Retrieved from https://www.ssb.no/statbank/table/04317/</li>  
  </ul>

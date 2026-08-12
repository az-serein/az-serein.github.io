# Third-party notices

## UT-GLOBUS data

The New Haven case study and interactive preview use a filtered, derived subset of **GLObal Building heights for Urban Studies (UT-GLOBUS)**:

- Official record and DOI: <https://doi.org/10.5281/zenodo.11156602>
- License recorded by Zenodo: [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/)
- Creators: Harsh Kamath; Manmeet Singh; Neetiraj Malviya; Alberto Martilli; Liu He; Daniel Aliaga; Cenlin He; Fei Chen; Lori Magruder; Zong-Liang Yang; Dev Niyogi

The full 2024 course analysis covered 331,423 New Haven records. The browser preview contains 16,379 polygons selected from a fixed central New Haven extent and filtered to estimated heights between 0 and 100 metres. It retains estimated height, area, volume, surface, and polygon geometry for visualization. Source IDs and coordinate fields are not shown in hover content.

UT-GLOBUS heights are estimates for urban modeling and are not surveyed property-level ground truth.

The upstream [UT-GLOBUS software repository](https://github.com/texuslabut/UT-GLOBUS) is GPL-3.0. This website does not redistribute that repository's source code.

## Basemap and visualization

- Basemap data: © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright)
- Basemap tiles and styling: © [CARTO](https://carto.com/attributions)
- Interactive rendering: [Plotly.js](https://github.com/plotly/plotly.js), requested from Plotly's CDN

The standalone preview uses `no-referrer` and visibly identifies its external requests. It requests Plotly from `cdn.plot.ly` and map tiles from CARTO's basemap service.

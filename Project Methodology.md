# Project Methodology

## Research Question
How have Irish migration, colonial experiences, and cultural identity shaped their interactions with Indigenous peoples in colonized regions, and how have these relationships influenced ideas of resistance, adaptation, and cultural exchange over time?

## Historical Context
This project examines the historical intersections between Irish communities and Indigenous peoples in regions affected by European colonial expansion in modern day United States, particularly during the 18th to 20th centuries. Both groups experienced displacement, cultural suppression, and economic marginalization under imperial systems, though in different contexts and power relations. Irish migration, especially during and after the Great Famine, placed Irish populations within colonial structures in North America, where they often interacted with Indigenous communities. 
The project addresses the broader historical problem of how colonized or formerly colonized groups relate to Indigenous populations within imperial systems. It explores whether Irish migrants reproduced colonial structures, resisted them, or developed hybrid forms of cultural exchange and solidarity.

# Data and Sources
# Primary Sources (Grouped by Category/How to Access)
## Source 1: Library of Congress Collections (Treaties, Newspapers, Relief Records)

Full Citation:
- George W. Harkins. “Farewell Letter to the American People.” 1832. Reprinted in *Arkansas Gazette*, 1832. Accessed via Library of Congress, Chronicling America.
- General Relief Committee of the City of New York. *Report for the Relief of the Suffering Poor in Ireland.* New York, 1848. Accessed via Library of Congress and HathiTrust.
- Boston Irish Relief Committee. *Report of the Boston Irish Relief Committee. Boston*, 1847; Philadelphia Irish Relief Committee. *Report of the Philadelphia Irish Relief Committee.* Philadelphia, 1847. Accessed via American Antiquarian Society and Library of Congress.
- *Arkansas Intelligencer.* 1847. Issues referencing Choctaw donation. Accessed via Library of Congress, *Chronicling America.*

Location/Access:
Library of Congress Digital Collections (Chronicling America)

Copyright Status:
Public domain

Format:
Digitized newspapers, pamphlets, and government-related documents

Quantity:
Multiple documents across collections

## Source 2: Irish Famine Newspaper Coverage (1845–1850)

Full Citation:
- Freeman’s Journal (Dublin), 1845–1850.
- The Nation (Dublin), 1845–1850.

Location/Access:
National Library of Ireland, Irish Newspaper Archives

Copyright Status:
Public domain

Format:
Digitized newspaper scans

Quantity:
Selected issues

## Source 3: U.S. Government Documents

Full Citation:
- United States Congress. *American State Papers: Indian Affairs.* 2 vols. Washington, DC: Gales and Seaton, 1832. Accessed via Library of Congress and HathiTrust.
- United States. Bureau of Indian Affairs. *Annual Reports of the Commissioner of Indian Affairs,* 1845–1850. Washington, DC: Government Printing Office.

Location/Access:
Library of Congress; National Archives; HathiTrust

Copyright Status:
Public domain

Format:
Digitized federal reports and printed volumes

Quantity:
Select volumes and reports

## Source 4: British and Irish Archival Collections

Full Citation:
Archival materials relating to Irish famine and colonial administration

Location/Access:
- British Library. Irish famine and colonial records collections. London.
- The National Archives (UK). Colonial Office Records relating to Ireland and Indigenous policy, 19th century.

Copyright Status:
Public domain (for historical materials)

Format:
Manuscripts, administrative records, newspapers

Quantity:
Select documents

## Source 5: Choctaw Nation Historical Records

Full Citation:
- Choctaw Nation of Oklahoma. Council records, famine relief documentation, and cultural archives, 19th century.

Location/Access:
Choctaw Nation archives; partnered digital collections

Copyright Status:
Public domain (historical records); some materials may require permission

Format:
Manuscripts, records, archival documents

Quantity:
Selected documents

## Source 6: Hargett Choctaw Collection

Full Citation:
- J. L. Hargett. *Choctaw Nation Papers*, 19th century. Manuscripts and Archives, Yale University Library.

Location/Access:
Yale University Library

Copyright Status:
Public domain

Format:
Manuscripts, correspondence, financial records

Quantity:
Selected materials

## Source 7: Indigenous Nation Contemporary Records

Full Citation:
- Navajo Nation. COVID-19 mutual aid records and public communications, 2020–2021.
- Native Land Digital. *Native Land Digital Map.* Accessed 2026. https://native-land.ca

Location/Access:
Official tribal and project websites

Copyright Status:
Public domain

Format:
Digital records, datasets, maps

Quantity:
Selected examples

## Source 8: Irish Institutional and Cultural Sources

Full Citation:
Materials documenting remembrance and commemoration of the Choctaw donation

Location/Access:
- Oireachtas. Parliamentary records and public statements on Irish–Choctaw relations.
- National Museum of Ireland. Exhibits and interpretive materials on the Irish Famine.
- Dublin City Council. Public commemorations and cultural heritage materials.
- Irish Famine Archive. Digital collections related to famine history.

Copyright Status:
Public domain

Format:
Public history materials, reports, and digital exhibits

Quantity:
Selected sources

## Source 9: Digital Collections

Full Citation:
- Digital Public Library of America (DPLA). Aggregated digital archival collections. https://dp.la

Location/Access:
Online database

Copyright Status:
Varies by item, most are public domain

Format:
Digitized archival materials

Quantity:
Supplementary sources

# Secondary Scholarship
## Source 10: Scholarly Interpretations

Full Citation:
- Darrell A. Posey, ed. *Indigenous Peoples and Sustainability.* Nairobi: United Nations Environment Programme, 1999.

Location/Access:
Academic journals and books

Copyright Status:
Copyrighted

Format:
Articles and monographs

Quantity:
Select works

# Data Collection Methods

Data was collected through:
- Manual archival research using digital libraries and institutional databases
- Curated dataset construction from verified secondary historical scholarship
- Image sourcing from public domain archives (Library of Congress, Smithsonian, etc.)
- Cross-referencing historical events across multiple databases to ensure accuracy and relevance

The dataset was structured manually into a standardized format of csv/spreadsheet for use in both the timeline and map components of the website.

I converted raw historical notes into structured entries (date, location, description, source), standardized date formats (YYYY or YYYY-MM-DD where possible), normalized place names for map consistency and condensed long archival descriptions into concise, readable event summaries. 
I removed duplicate or redundant entries across sources, eliminated ambiguous historical claims and standardized citation format for consistency across dataset entries
Metadata added was geographic coordinates (for mapping), event categories (migration, conflict, cultural exchange, etc.), source attribution links and thematic tags (colonialism, resistance, displacement)
Some historical events lack precise dates or geographic specificity. Indigenous perspectives are underrepresented in written colonial archives with archival bias reflecting predominantly European documentation systems. Furthermore, not all regions of Irish–Indigenous interaction are equally documented

# Computational Methods
## Method 1: Timeline-Based Historical Structuring

Tools/Libraries: HTML, JavaScript, JSON dataset structure

Process:

1. Historical events were compiled into a structured dataset
2. Each entry was assigned a date, location, and description
3. Events were rendered chronologically in a digital timeline interface
4. Users can scroll and visually track historical development over time

Rationale:
A timeline format allows users to understand historical causality and sequence, highlighting long-term patterns in Irish migration and Indigenous interaction.

## Method 2: Digital Mapping

Tools/Libraries: Leaflet.js, GeoJSON data

Process:

1. Historical locations were assigned latitude and longitude coordinates
2. Events were converted into GeoJSON format
3. Data points were plotted on an interactive digital map
4. Popups provide historical context, images, and citations

Rationale:
Mapping enables spatial analysis of historical interactions, showing how migration and colonial systems operated across geography rather than isolated events.

# Software and Dependencies:
- Programming Language: JavaScript, HTML5, CSS3, Python 3.12
- Key Libraries: Leaflet.js (mapping), pandas 2.x (data manipulation), matplotlib 3.x (visualization)
- Data Format: JSON / GeoJSON
- Styling: Custom CSS
- Hosting: GitHub Pages
- Environment: Virtual Kernel on VSCode

# Analysis Process
Data Loading: Historical data was manually embedded into structured JSON files and loaded into the timeline and map systems.

Exploratory Analysis: Initial review focused on identifying recurring themes such as:
- Colonial displacement
- Migration patterns
- Cross-cultural interaction
- Resistance narratives
  
Primary Analysis: The main analytical approach was qualitative and digital:
- Events were grouped by theme and geography
- Patterns of interaction were identified through visual comparison on map and timeline interfaces
  
Validation: Cross-referenced multiple historical sources, verified dates and locations using institutional archives, and checked consistency between timeline and map datasets

Interpretation: Quantitative structure (such as the timeline or map) was interpreted through historical reasoning and emphasizing narrative connections.

Visualization and Presentation: The project uses interactive timeline for chronological storytelling, digital map for spatial visualization, image integration for archival context and a card-based layout design for readability. Design principles included high contrast for accessibility, a minimalist aesthetic to emphasize on readability over decorative complexity, and have an interactive engagement 

# Limitations and Caveats
Data Limitations:
- Incomplete archival records for Indigenous perspectives
- Uneven geographic documentation
- Reliance on colonial-era written sources

Methodological Limitations:
- Cannot fully represent lived Indigenous experiences
- Historical interpretation influenced by available Western archives

Technical Limitations
- Browser-based visualization constraints
- Limited dataset size due to manual curation

# Validation and Verification
I cross-checked sources across multiple archives, verified historical consistency using academic secondary literature and manually reviewed dataset entries for accuracy and clarity

# Reproducibility
All code is available in the GitHub repository:
https://github.com/rapasternack/Irish-Indigenous-Interactions

The dataset is embedded in structured JSON format within the project files. Dependencies are limited to standard front-end web technologies (HTML/CSS/JavaScript) There is no proprietary software is required to reproduce the project

# Future Directions
People could:
- Expand dataset to include more Indigenous-authored sources
- Integrate oral histories and audio archives
- Improve geospatial precision with advanced GIS tools
- Include comparative colonial case studies 

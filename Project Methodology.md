# Project Methodology

## Research Question
How have Irish migration, colonial experiences, and cultural identity shaped their interactions with Indigenous peoples in colonized regions, and how have these relationships influenced ideas of resistance, adaptation, and cultural exchange over time?

## Historical Context
This project examines the historical intersections between Irish communities and Indigenous peoples in regions affected by European colonial expansion in modern day United States, particularly during the 18th to 20th centuries. Both groups experienced displacement, cultural suppression, and economic marginalization under imperial systems, though in different contexts and power relations. Irish migration, especially during and after the Great Famine, placed Irish populations within colonial structures in North America, where they often interacted with Indigenous communities. 
The project addresses the broader historical problem of how colonized or formerly colonized groups relate to Indigenous populations within imperial systems. It explores whether Irish migrants reproduced colonial structures, resisted them, or developed hybrid forms of cultural exchange and solidarity.

# Data and Sources
## Primary Sources Used
Library of Congress Digital Collections – https://www.loc.gov/
National Archives (UK) – https://www.nationalarchives.gov.uk/
Smithsonian Indigenous Digital Collections – https://www.si.edu/
Irish Famine Memorial Archives (various institutional records)
Indigenous oral history and cultural documentation repositories (where publicly available and ethically accessible)
Historical maps and migration datasets from public domain archives

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
Method 1: Timeline-Based Historical Structuring

Tools/Libraries: HTML, JavaScript, JSON dataset structure

Process:

1. Historical events were compiled into a structured dataset
2. Each entry was assigned a date, location, and description
3. Events were rendered chronologically in a digital timeline interface
4. Users can scroll and visually track historical development over time

Rationale:
A timeline format allows users to understand historical causality and sequence, highlighting long-term patterns in Irish migration and Indigenous interaction.

Method 2: Digital Mapping (Spatial History Analysis)

Tools/Libraries: Leaflet.js, GeoJSON data

Process:

1. Historical locations were assigned latitude and longitude coordinates
2. Events were converted into GeoJSON format
3. Data points were plotted on an interactive digital map
4. Popups provide historical context, images, and citations

Rationale:
Mapping enables spatial analysis of historical interactions, showing how migration and colonial systems operated across geography rather than isolated events.

Software and Dependencies:
Programming Language: JavaScript, HTML5, CSS3, Python 3.12
Kwy Libraries: Leaflet.js (mapping), pandas 2.x (data manipulation), matplotlib 3.x (visualization)
Data Format: JSON / GeoJSON
Styling: Custom CSS
Hosting: GitHub Pages
Environment: Virtual Kernel on VSCode

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

Visualization and Presentation: The project uses interactive timeline for chronological storytelling, digital map for spatial visualization, image integration for archival context and a card-based layout design for readability. Design principles included high contrast for accessibility, a minimalist aesthetic to emphasize on readability over decorative complexity, and have a n interactive engagement 

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

Validation and Verification
I cross-checked sources across multiple archives, verified historical consistency using academic secondary literature and manually reviewed dataset entries for accuracy and clarity

# Reproducibility
Yes! All code is available in the GitHub repository:
https://github.com/rapasternack/Irish-Indigenous-Interactions

The dataset is embedded in structured JSON format within the project files. Dependencies are limited to standard front-end web technologies (HTML/CSS/JavaScript) There is no proprietary software is required to reproduce the project

# Future Directions
People could:
- Expand dataset to include more Indigenous-authored sources
- Integrate oral histories and audio archives
- Improve geospatial precision with advanced GIS tools
- Include comparative colonial case studies 

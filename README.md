# S-126-Product-Specification-Development
Collaboration space for IHO Nautical Information Provision Working Group for the development of S-126 Product Specification with its artifacts.


Introduction 
As early as 2005 the SNPWG (Standardization of Nautical Publications Working Group) had been working on separating the Sailing Directions into various data layers that can be displayed in an ECDIS/ENC. Ten years later, in 2015, the SNPWG changed its name to the NIPWG (Nautical Information Provision Working Group) to reflect a new era beyond static publications into nautical textual information that could be stored, transferred, and displayed more dynamically. The changes in this group go beyond just the name. Each year membership that comprise this group varies, as does the level of knowledge about what has transpired. Because of this varied level of understanding from year to year and member to member, it is important to periodically document the progress of the work being done in a clear and concise manner. 
The aim of this document is to outline the lineage of the development of the S-126 Physical Environment product specification, suggest a big picture view of the direction of the S-126, as well as record the current challenges and offer possible solutions. This document is meant to “clearly define the requirements for S-126 before we can progress in a meaningful way.” (NIPWG1 2015) This paper is also an official request with clearly documented reasons to the NIPWG as well as HSSC to take the official development of the S-126 off hold status. 
Background - History of the S-126 
As early as 2005 at SNPWG05 in Copenhagen, it had been decided the group’s main purpose was to take the textual nautical information from the Sailing Directions (SD) publication and create different products or layers of information for overlay in an ECDIS / ENC. 
The S-126 Scope 
Data Scope 
At the same meeting (SNPWG05) the NIPWG created project teams based on geographic region to work with specific data. The items from the SD were broken down into the following major themes (with assigned sub-working groups) 
• • Northern European WG – NEG (Germany, Denmark, Sweden, IIC) o Marine Services ??Service to facilitate the business of shipping - Pilotage, shore services, bunkering, radio services 
• 
• o Harbour Infrastructure ????????????????????????????????????????????????????????
• 
• 
• • Western European WG - WEG (UK, France, Portugal) o Social Political ??Non-traffic regulations, geopolitical items 
• 
• o Nav Marks ????????????????????????????????????????????????
• 
• o Environment ???????????????????????????????????????
• 
• 
• • The Americas WG - (US/NOAA and US/USCG) o Hydrography ??????????????????????????????????????
• 
• o Topography ??Geographic features above the high water level i.e. mountain ranges, plain, valley 
• 
• 
Note: FOR REASONS OF ECONOMY, DELEGATES ARE KINDLY REQUESTED TO BRING THEIR OWN COPIES OF THE DOCUMENTS TO THE MEETING 


• o Traffic Management ?????????????????????????????????????????????????????????????????????????????????????????
• 
• 

The subcategories related to the Environment portions of the SD are (from SNPWG_06_017): 
• • Maritime topography 
• • Magnetic variation and local anomalies 
• • Currents, tidal streams and flow (including large and seasonal currents SNPWG17) 
• • Sea level and tides 
• • Sea and swell/waves 
• • Sea water characteristics 
• • Ice conditions (general statements but not current icing conditions SNPWG17) 
 • Climate and weather (SNPWG17 general atmospheric statements including: ) o fog and visibility 
 o winds 
 o precipitation 
 o tropical storms and cyclones 
 
 • Influence of weather conditions 
 • Local weather 
 • sea state (including abnormal waves and sea surface SNPWG17) 
 • Adverse natural conditions 
 • Climatic tables 

The subcategories related to the Hydrography portions of the SD are (from SNPWG_06_017): 
• • Anchorage o Water depth area 
• o Kelp/Weed 
• o Sandwaves 
• o Spring in Seabed 
• 
• • Hazards o Dumping ground 
• o Submarine cable/pipelines/and associated areas 
• 
• • Waterway o Canal 
• o Embankment 
• o Sloping ground 
• 
• • Port o Sea area 
• o Dredged area 
• o Depth area 
• o River 
• 

The subcategories related to the Topography portions of the SD are (from SNPWG_06_017): 
• • Waterway o Slope Topline 
• 
• • Coastal Features o Landmarks 
• o Vegetation 
• o Land Topography 
• 

These project teams were then tasked to outline all the items within each topic and match them with S-57 data objects and attributes to find what could be missing in a new S-100 representation. Extensive work through 2018 has already been done finding these gaps and updating the IHO registry with any missing items. 
NP3 Scope 
At SNPWG11 (Monaco 2009) an extensive discussion ensued trying to draw up the boundaries of NPUBS NP3 products. NP3 products must supply the mariner with a route planning tool from berth to berth as well as provide the information that meets the requirements of SOLAS. In the area of static, historic information versus dynamic real time data NP3 products must still contribute to passage planning. Information in ENC and in NPUBS must continue to live side by side without data duplications or detrimental impact on each other. The question came up if the S-126 is to be available as a standalone product and if so, what NPUB data can stand alone in an ECDIS without linking to an ENC feature? The following list was the result of the discussion: Note: FOR REASONS OF ECONOMY, DELEGATES ARE KINDLY REQUESTED TO BRING THEIR OWN COPIES OF THE DOCUMENTS TO THE MEETING 


• • Regulatory NPUBS not necessarily concerned with SOLAS, in other words keeping the vessel legal. 
• • Facilities at places (bringing own geometries) 
• • Area data sets 
• • Climatic data sets 

Information which has no relation to the HYDRO features. Some of this information may have known geometry. Some of it, like reference information, i.e. Morse Code and flags for letters and numbers, may not. 
S-126 Test Data and Product Specification draft 
The first mention of the generic term, “Physical Environment”, that included the combination of Hydrography, Topography and Environment began at SNPWG16 in 2013 at Silver Spring. 
At SNPWG17 in 2014, in Rostock the UK had presented test data for the Physical Environment that was mostly based on hydrography (the seabed, submarine springs, volcanic and seismic activities). It was noted that larger areas would need to be considered for items like marine climatology, cyclone tracks, ocean currents and tidal streams as well as consider land topography like mountains and man-made features. 
At the SNPWG18 meeting in 2014 in Cadiz a number was assigned to the Physical Environment, the S-126. The work items for the meeting included drafting a product specification for Physical Environment starting 2013 ending 2016, as a high priority. 
It was agreed at the first NIPWG meeting in 2015 in Monaco that the S-126 test data set was at a mature stage and needed to develop an S-100-based proof of concept. The Annex of NIPWG1-15.1 shows a possible mapping of S-126 content which is based on the old data model enhanced with some new S-100 components. It was also noted during the meeting that the requirements for the S-126 Product Specification needed to be clearly defined before further meaningful progress could be made. 
The data model which is in the NIPWG wiki was the simplest possible approach, however, that was the time before complex attributes and information classes were introduced in S-100. A current S-126 data model would be more detailed and more complex. The current wiki data model and the existing test data samples can only be used as starting points. Both need significant extensions. 
Analysis/Discussion 
S-126 current hold status 
SNPWG charged UKHO with the provision of a test data set which covers all facets. (see SNPWG18-15 and NIPWG1-15.1) That was partly done but finally, stopped due to UKHO objections. (see NIPWG1-15.1). The reflection to the unclear scope of S-126 and possible S-100 interactions as mentioned in NIPWG1-15.1 were arguments to justify the discontinuation of the S-126 PS development. 
The NIPWG2 meeting in Monaco, just before the HSSC8 meeting, still had action item (2/09) for the development of the S-126 (and included the mariners handbook in the test data set). 
The NIPWG Work Plan 2016-2017 (F.8.1.4) submitted to the HSSC8-05.4A paper included the development of the S-126 PS and reported that the test data sample experienced enhancement in content and was considered as ready for use. Yet also in 2017 at HSSC8/29 the S-126 was put on hold to focus on higher priorities of S-122 (Marine Protected Areas) and S-123 (Radio Services). 
The NIPWG3 meeting in Korea there was mention of putting the S-126 work on hold within the group and subsequently a paper was submitted to HSSC-9 with the recommendation that due to the existing workload it would be best to postpone any more efforts developing the S-126 PS. 
At NIPWG4 the Netherlands was tasked (action item 3/08) to create a short status report for HSSC-9’s consideration benchmarking existing features of physical characteristics existing in S-101, S-411 and S-412, assessing the possible added values of S-126 items and collect any other use cases. (This was to justify the reason why NIPWG was “putting on hold” the work.) Note: FOR REASONS OF ECONOMY, DELEGATES ARE KINDLY REQUESTED TO BRING THEIR OWN COPIES OF THE DOCUMENTS TO THE MEETING 

Reasons to continue development on S-126 
NIPWG has currently three product specifications released, and they are, except for some examples and test case data, more or less dormant. The reasons are well-known; no production systems available, no on-board systems available, no S-101 available, no sufficient portrayal rules available ... 
NIPWG has the interest of Canada, Norway, the Netherlands and UNH who are all willing to accept the workload for the development of the S-126. Also, at the NIPWG6 meeting in Germany the Stakeholders (ICS in particular) were very keen on having the publications/SD text follow the path of the S-126 latest developments that were presented by UNH. 
This paper is a request to the NIPWG as well as HSSC to take the official development of the S-126 off hold. 
This is timely in that now two HO’s (Canada and Norway) are already in the process of making big changes with their own production systems to digitize and accommodate S-100 standards relating to nautical textual information. 
Things to resolve from past meetings 
From SNPWG18, Cadiz 2014 
• a. Is it possible to use the term ‘season’ in generalised descriptions of phenomena. (eg. Monsoon season)? 
 b. Is it permissible to use seasons instead of specific months (eg. Summer, winter etc)? a. For programming purposes it is best to use a range of months which is the recommendation 
 
 c. Do we need/want the ability to use links to other specialist documents where it is not appropriate to provide a full explanation of phenomena (eg. Mariner’s Handbook etc)? 
 d. Do we want links to specialist graphics (wind/temperature/swell/MSL etc)? 
 e. Do we want to include regional variants (external to region being described) of the same basic phenomenon (Hurricane/Typhoon/Cyclone)? 
 f. We need to decide on whether the terrestrial environment data set needs to contain man-made structures such as towns/built up areas/water collection. 
 g. how much textual data was necessary to display when describing the associated object on a chart. 

NIPWG6, Rostock 2019 
Just after the meeting a discussion ensued about warnings related to S-126 items, if there would be interoperation between them or possibly value-added information from the S-126 to corresponding warnings. It brought up the concern that S-124 messages didn’t have a category in the CodeList that was appropriate for the different items within the S-126. The specific case was focused on surface currents / tides related data, however other items within the S-126 should be covered as well. Right now the S-124_warningHazardType contains a value “tsunamis and other natural phenomena” which is the only value that would apply to all of the S-126 items. 
It is recommended to get samples of S-124 data with different items that overlap the S-126 themes and test to see if the S-126 data lends support to the S-124 in anyway. If it does, it is recommended to approach the S-124 group with more categories that could help to group the appropriate layers/topics of data together. 
The S-126 Vision 
Since the VONI workshop held at UNH in 2017 there have been more demonstrations and ideas about how the end result of this work should fulfill mariners and industry’s desires for customizable data that is displayed within the context of the chart. With overlay examples of surface currents, a few physical descriptions, and pilot services the NIPWG now has a better sense of what could be possible with continued work on the S-126. At NIPWG6 in Germany (2019) the stakeholders forum shared their desires for vectorized data (“using relevance, timing, and volume of data”) that allows for more flexibility in context of the ECDIS/ENC. (NOTE: The idea behind vectorization of publication data is that the information would be attached to existing features such as contact information attached to a pilot pickup point feature.) Also, at the meeting, Korea presented their vision of portraying the information on the chart with a new symbol set of icons. 
Recommendations 
Based on recent comments from and collaboration with Canada, Norway, and Germany as well as extensive work in the past from SNPWG, along with the past three years of work done by UNH on the S-126 related data, the following are suggestions for moving forward in developing the S-126 product. Note: FOR REASONS OF ECONOMY, DELEGATES ARE KINDLY REQUESTED TO BRING THEIR OWN COPIES OF THE DOCUMENTS TO THE MEETING 

There is an attached Annex A with Special Notes on items that are recommended to keep in mind as development continues, these are a type of best practices that have been compiled and should be officially recorded for consistency. 
Source 
It is recommended that the group agree that for the foreseeable future only the Sailing Directions SD be used as a source for the S-126 product. 
Harmonizing SD content 
It became clear while intensively scrutinizing aspects of the SD that to simplify the workload of the conversion of the SD into S-100 products each HO responsible would have to do some internal cleaning up that could be executed as soon as possible. 
Standardizing the Headers 
Since the headers in the SD are the basic categories laid out in the Data Scope of this document it is imperative that they become standardized to the same corpus. Eliminating headers that are specific to areas to make them more generic (e.g. Pepperell Cove Anchoring vs. Anchoring) greatly aids in the mapping process and allows for easier storage in the database with fewer entries and more resharing of data. 
Standardizing Nomenclature and layout 
Often there are multiple different ways to say the same thing. Choosing just one way and consistently using it throughout the document creates a template for specific categories of data that ultimately help to define the overall data structure for that category of information. The ordering can help as well since once there is an established order it is easier to pick out the patterns in other sections of the document. (Easier for humans but also for automated programs!) So, for example, if the Pilot information always contains an address, phone number and time schedule…rewrite the paragraphs to fit that order in every part of the document. That way it will be much easier to identify those matching components when assigning elements into an S-126 data structure. That also includes the way sentences are broken up or kept together, either always break them up or always keep them together, but BE CONSISTENT! This will greatly speed up the process when it comes time to mapping the data. 
This will also help greatly when it comes to the more complicated prose of physical descriptions. Scrutinize the paragraphs and sentences for every update and find ways to simplify and standardize what is being said, keeping what is absolutely necessary and eliminating extraneous ways to say things. 
Divide the work 
Break the S-126 into three manageable themes to be tackled one at a time: 
 1. Water related information a. Surface Currents – proposed in conjunction with S-111 
 b. Tides/Water-levels – proposed in conjunction with S-104 
 c. Waves - possible aid to S-412 
 d. Sea Ice – possible aid to S-411 
 
 2. Weather related information – possible aid to S-412 
 3. Physical Descriptions of the environment – interaction with S-101 note: all also have possible interactions with S-124 Navigation warnings. 

It is recommended to focus on the items with product specifications that have been released and stable to confirm the viability of supporting that product. It is essential to continue to develop in tandem with associated products and their working groups, to create test cases and proof-of-concept visualizations that will help to determine how the data can added value to the mariner’s experience as well as work out interoperable components. 
Bring back the breakout sessions 
It is recommended that while the NIPWG is in session there will be at least one afternoon dedicated to breakout sessions where work is done on very specific details of the products, this would include helping HO’s standardize their own SDs (see above on Harmonizing SD content), helping in the process to determine value-added-ness (see below on Determine value-added-ness) Note: FOR REASONS OF ECONOMY, DELEGATES ARE KINDLY REQUESTED TO BRING THEIR OWN COPIES OF THE DOCUMENTS TO THE MEETING 

Use Real Data 
From an action item at SNPWG11 in 2009, David Acland encouraged members to take a block of text from their own nautical publications and play around with it, like JHOD had done, in order to get a better grip of the problems we are likely to encounter. Ideally, a few samples of actual data (not made-up test data) in each topic (and sub-topics outlined earlier) from each Hydrographic Office would not only help to create more robust data models, but would encourage hands-on participation and increase the level of working knowledge of the group. 
Geo-referenced items first 
Within the real data used, it is recommended to focus first on items that have a geo-referenced location. These items can readily map to the S-101 ENC features and serve to test interoperability. Because they have a position on the chart, they are generally simpler to model and portray. 
As recommended from SNPWG11 in 2009 the items could be grouped by: 
• • Known geometry • Data like fog, swell, wind conditions, Regulations 
• 
• • Fuzzy/Imprecise geometry • general statements like information on military exercises, fishing methods 
• 
• • No geometry • Look through NPUBS for general reference material 
• 

Determine value-added-ness 
During the SNPWG17 meeting in 2014 at Rostock 
• • Items like general remarks, deeps, ridges and plateaus are on the chart and should not be included in this work. 

It would not be advisable to eliminate data from the Sailing Directions until it has passed a metric that can be followed (and repeatable) with specific steps. The data might add value as summary text, it might add value as full text, however it could also add value by breaking down the text into atomic parts that are associated to a modeled object or even add value by simply lending weight to associated ENC objects thereby calling attention to them; whatever helps reduce the cognitive burden of the mariner, collates relevant data and simplifies the amount of data contained within the SD will add value. 
The recommended plan to set up the testing metric should be as follow: 
1. Isolate the associated data on the chart in the associated area 
2. Add other associated data 
3. Choose a specific task that utilizes the data 
 4. Test different modes of presentation to determine helpfulness including: a. Full text 
 b. Summary text 
 c. Atomic element modeled data (not in prose) 
 d. Weighting associated ENC features For example: the feature on the chart has “duplicate” data written out in text. Text may not add value, however it may be important to keep track of the importance of that feature since it was important enough to be included in the SD as text in the first place. 
 

Once these steps have been taken and documented it should then be presented to the NIPWG with recommendations on the finding; if it IS considered value-added and if so, in what mode/format. 
Metadata 
It is recommended that the text contains categories to help in determining the value-added step of data testing and to allow for better collation, filtering and customizing of the data. Assigning these categories helps to set up specific data models as well as test those that may be most beneficial. These categories come from a Canadian study of the SD executed this year (2019). Note: FOR REASONS OF ECONOMY, DELEGATES ARE KINDLY REQUESTED TO BRING THEIR OWN COPIES OF THE DOCUMENTS TO THE MEETING 


• a. Navigator Use/Timeframe 1. Long-lead planning (feasibility) 
• 2. Short term planning (specific) 
• 3. Immediate execution (navigation) 
• 
• b. Ship Activity/Area 1. Oceanic Transit/Landfall 
• 2. Coasting 
• 3. Harbour Entry 
• 4. Port Operations 
• 
• c. Ship Type Applicability 1. Commercial Deep Sea (SOLAS) 
• 2. Professional Coastal (non-SOLAS) 
• 3. Private/Recreational 
• 4. All 
• 
• d. Info Type 1. Instructional 
• 2. Descriptive 
• 3. Informative 
• 4. Advisory 
• 5. Directive 
• 
• e. Level of Detail 1. Mention 
• 2. Summary 
• 3. Comprehensive 
• 4. Specific 
• 5. Realtime 
• 
• f. Activities/Use cases 1. Seasonal marine activities 
• 2. Cultural activities 
• 3. Tourist attractions 
• 4. Scientific activities 
• 
• g. Information form 1. Text 
• 2. Table 
• 3. Image 
• 4. Shape 
• 5. Link 
• 

Use UML to help visualize the big picture 
Once the text is selected, categorized and tested it should be set up in UML diagrams (Star UML is a free tool that is relatively simple and easy to use, although Enterprise Architect is the professional version used to create UML models for the official Product Specifications). These diagrams are instrumental in visually seeing the domain, associations within the domain, the scope of the domain and the bigger picture. 
A Unified vision of the S-126 within NIPWG 
If we don’t have a unified vision of the purpose and portrayal of the S-126 within the NIPWG we will be unable to clearly share it with HSSC or other interested parties. Before the end of this meeting (NIPWG7) this vision must be outlined clearly based on the recommendations made in this document as well as a basic statement of portrayal. It is understandable that details can and will evolve upon each testing phase, however, starting with a baseline that everyone can agree upon now will help to lay a stake in the ground from which this vision can grow. 
It is recommended that the vision includes: 
• • Use existing S-101 features whenever possible (and associate to those features using the MRN) 
• • the need to minimize new symbols on the chart to reduce clutter and 
• • selectively agree upon symbol use with agreement of DIPWG only if it helps to minimize text and yet is universal enough to intuitively understand by all. (HSSC has directed DIPWG to, "Develop symbology for portrayal of nautical publications in ECDIS – SNPWG12, 2010 Tokyo) 
Note: FOR REASONS OF ECONOMY, DELEGATES ARE KINDLY REQUESTED TO BRING THEIR OWN COPIES OF THE DOCUMENTS TO THE MEETING 


• • Minimize text where possible 
• • Maintain the outlined (above) level of textual detail for possible “drill-down” options for more comprehensive data when needed. 

Conclusions 
Many years of work have already gone into the foundation of the S-126 to convert textual data into S-57 formats. With the S-100 standards maturing and more interest in converting publication systems into these new standards it is the time to officially take the S-126 off of hold status and resume its work. If it follows the path of other products from the NIPWG it could take another 5-7 years if progress doesn’t resume soon. It has been stated by stakeholders at various meetings that the Nautical Textual Information is an important part of the mariner’s toolbox to give situational awareness, aiding in proper and safe planning of passages. There is much work to do, however, following the recommendations given in this document, 
Action Required of NIPWG 
The NIPWG is invited to: 
• a. endorse the recommendations proposed in this document 
• b. agree to the plans outlined and overall vision described 
• c. give advice and detailed changes where items are not agreed upon 
• d. note the timeline and special notes as the S-126 development continues 

Annex A Special Notes 
There were items of specific note from past meetings that were important to include in this comprehensive document that are the result of a mapping exercise of Sailing Directions data to S-57 objects and attributes. (SNPWG14 – 2012 Monaco) These could turn into specific recommendations in the future, for now they are considered more “best practices” for consistency. 
Geographic Object 
It was found despite the textual nature of the data in most cases info objects weren’t needed and that the geographic objects should be used whenever possible. (SNPWG07 – 2007 Monaco) 
Spatial linkages: sometimes a single geometry might not always apply to all vessels. One suggestion was to use feature object identifiers, which are supposed to uniquely identify a feature. It was noted that not all of the HOs maintain the feature object identifiers. (Now called the MRN – Maritime Resource Name) 
Place location: Nautical publications, in particular sailing directions, often identify locations verbally instead of by coordinate, e.g., by naming a buoy instead of providing its coordinates. It is often difficult to locate such named points in the ENCs; if the name is not coded in the ENC it is not possible to locate it without external (local or personal) knowledge about the area. 
Geographic features not in chart: There are mismatches between the ENC and the nautical publications, in the form of locations or features mentioned in the nautical publications (by name or otherwise) not being in the ENC. It was not always clear which source was the correct one. The mapping process led to the discovery of discrepancies in the charts, for example a feature displaced from its actual location. 
Proliferation of spatial objects: Different clauses in a regulation may apply to different sections of a waterway. The question arises whether it is better to define distinct spatial objects for sections where specialised rules apply, or to attach a larger chunk of text to fewer, larger spatial objects. In such situations a choice must be made between an overly complex result which requires more labour and an overly simple result which conflates information items which are distinct in the real world and may therefore be less useful to the mariner. 
String attributes 
The SNPWG is finding that they are going to have to use complex text. Where we have text, should we add tags? It was decided that we should use string attributes for regulations and that other text that must be fully explained, but we should use the other attributes whenever possible. String attributes should be used on a case by case basis and the other attributes should be used whenever possible. (SNPWG07) Note: FOR REASONS OF ECONOMY, DELEGATES ARE KINDLY REQUESTED TO BRING THEIR OWN COPIES OF THE DOCUMENTS TO THE MEETING 

Repeating attributes 
The group had a lengthy conversation and decided to use repeating objects when two or more attributes are dependent on one object. In the cases like “service hours” where there is a list of many attributes that impact different variables (times for various services may be different) the SNPWG decided not to use list attributes anymore. (SNPWG07) 
Items from SD to be eliminated 
• • Duplicated information should be eliminated (minimised) where practical. (SNPWG17) 
• • Ambiguous/generalised statements should be eliminated (SNPWG17) 



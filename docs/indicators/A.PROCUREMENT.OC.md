# Availability: Public procurement data

To what extent is detailed public procurement information available for public use? 


    
=== "Definitions"
    **Definitions and Identification**
    
    Governments enter into many different contracts for the provision of goods, services, and public works. They may publish data about these contracts in tender lists or through contract finder websites, procurement portals, or open data portals.
    
    In some countries, public procurement data may be held in a single system. In others, different stages of the procurement process—planning, tender (inviting bids), award (issuing a contract), implementation (monitoring performance of the contract)—may be held in different datasets, and a government may publish "notices," with or without identifiers, that make it possible to connect data from different stages of the procurement process.
    
    **Examples**
    
    - [Contracts Finder](https://www.gov.uk/contracts-finder) in the UK provides a [JSON API](https://www.contractsfinder.service.gov.uk/apidocumentation/Notices/1/GET-Published-Notice-OCDS-Search) and data dumps from a database designed to aggregate tender and award information for all government procurement above a given threshold. It provides machine-readable data and offers an OCDS export. However, a sample export of records reveals no links to spending, that documents are often missing, and company identifiers are only provided in some cases.
    
    - The Dominican Republic’s Dirección General de Contrataciones Públicas hosts an [open data portal](https://datosabiertos.dgcp.gob.do/opendata) to publish open procurement data; the portal provides public dashboards to analyze the data, an API, and exports in a variety of formats.
    
    - In Uganda, the Public Procurement and Disposal of Public Assets Authority publishes [procurement data in open format](https://gpp.ppda.go.ug/public/open-data/ocds/ocds-datasets) for more than 50,000 awards.
    
=== "Research Guidance"
    
    Look for services that aggregate data from across government, not just single departmental websites. However, if no such service is available, check a selection of the biggest government departments and note if they publish their contract data in any form.
    
    For examples of how the Open Contracting Data Standard (OCDS) is applied to the different procurement stages, you can explore relevant terms in its [release structure](https://standard.open-contracting.org/latest/en/schema/reference/#release-structure).
    
    **Starting points**
    
    - **Sources:**
    
    	- The Open Contracting Partnership maintains a [data registry of publishers disclosing procurement data](https://data.open-contracting.org/) following the Open Contracting Data Standard (OCDS). The registry includes direct links to the publisher's websites, including national and subnational procurement agencies.
    
    	- The country profiles in the[ Global Public Procurement Database](https://www.globalpublicprocurementdata.org/gppd/) provide links to procurement agency websites, national e-procurement systems, and, where available, links to OCDS data.
    
    	- Columns EB, EC, ED, and EE of the[ data spreadsheet](https://archive.doingbusiness.org/content/dam/doingBusiness/excel/db2020/DB2020_CwG_Data.xlsx) from the[ World Bank Doing Business module on Contracting with Government](https://archive.doingbusiness.org/en/data/exploretopics/contracting-with-the-government#data) include links to where public works contracts for roads are posted online for each country (based on data gathered before May 2020). This can be used to check whether public works contract data is in the same portal as other tender information.The World Bank’s new [Business Ready (B-READY)](https://www.worldbank.org/en/businessready) survey is expected to offer similar information.
    
    	- [This 2023 study](https://www.open-spending.eu/wp-content/uploads/2023/07/How-Open-is-EU-Procurement-Data-2023-2.pdf), by the Open Spending EU coalition, provides an overview on openness of procurement data across the EU and has an annex with the list of sources.
    
    	- The World Bank’s [ProACT Procurement Anticorruption and Transparency platform](https://www.procurementintegrity.org/) provides links of countries’ procurement portals where procurement data is available. The last update was in 2022.
    
    - **Search:**
    
    	- National data portals for "contracts" or "procurement" datasets;
    
    	- The website of the national procurement agency for open data, APIs, or data exports.
    
    - **Consult:**
    
    	- Transparency experts or journalists writing about procurement; ask about known limitations of contracting data.
    
    **What to look for?**
    
    To complete the assessment for this question you will need to access and explore the available data. This may involve running queries on datasets to check the variety of procurements included.
    
    Dashboards and other public analytic tools may help you to assess the comprehensiveness and coverage of the data.
    
    Look for evidence of:
    
    - The **stages of the procurement process for which data is available**—check for details of contact awards and implementation information (spending and performance).
    
    - **Goods and services contracts**—these can range from low-value to high-value contracts, covering a wide range of supplies to government.
    
    - **Public works contracts**—these are often higher-value contracts, involving construction work; for example, building schools and hospitals, roads, and other infrastructure.
    
    - **Procurement from a range of government departments**—does the data appear to contain only procurement from a single department? Or from across government more broadly?
    
    - **Procurement from subnational government units**—if you find procurement for subnational entities in the data, does this appear to be comprehensive, or could it just be voluntary publication by a few local government units?
    
    - **Bulk data access** via downloads or APIs. Can you, for example, export a search as XLSX and does the resulting data contain relevant data fields? Is there documentation for an API that allows access to full data records?
    
    - **Persistent data**—can you find data from last year? Or the year before? Does it appear that old data is being archived? Or does old data expire from the platform?
    
    - **The data is structured according to an established standard**—does the data follow a standard such as the[ Open Contracting Data Standard (OCDS)](https://standard.open-contracting.org/)?
    
    

=== "Question sub-components"

    <a class='toggle_sup_q' href='javascript:Array.from(document.querySelectorAll("blockquote")).forEach(function(el) {if (el.style.display === "none") {el.style.display = "block"; } else { el.style.display = "none";  }});'>Show/hide supporting questions</a>
    
    **Existence**
    
    * **Is this data available online in any form?**
        * Data is not available online.<blockquote class='supporting_questions'><strong>Supporting questions:</strong> <span class='supporting_question'>Are there other offline ways to access this data in the country? (e.g., attending an office to inspect it).</span></blockquote>
        * Data is available, but not as a result of government action.<blockquote class='supporting_questions'><strong>Supporting questions:</strong> <span class='supporting_question'>If government is not providing access to data, how is this data available? </span><span class='supporting_question'>Please provide a URL(s) for where this data can be found.</span></blockquote>
        * Data is available from government, or because of government actions.<blockquote class='supporting_questions'><strong>Supporting questions:</strong> <span class='supporting_question'>Please provide a URL(s) for where this data can be found.</span></blockquote>
    
    * **Extent of existence:**
    
    * **How nationally comprehensive is the data assessed for this indicator?** (The data assessed covers one or more localities, but there are many other localities without data available or with data of a lesser quality., The data assessed covers one or more localities and is representative of the kind of data that can be found for most but not all localities., The data assessed provides national coverage.)
    
        > **Supporting questions** (conditional)
    
        > If The data assessed covers one or more localities, but there are many other localities without data available or with data of a lesser quality. or The data assessed covers one or more localities and is representative of the kind of data that can be found for most but not all localities.: Which locality or localities does this data cover?
    
        > If The data assessed covers one or more localities, but there are many other localities without data available or with data of a lesser quality. or The data assessed covers one or more localities and is representative of the kind of data that can be found for most but not all localities.: Please explain your response.
    
        > If The data assessed covers one or more localities, but there are many other localities without data available or with data of a lesser quality. or The data assessed covers one or more localities and is representative of the kind of data that can be found for most but not all localities.: Please provide supporting URL(s) as necessary.
    
    * **How comprehensive, in terms of procurements, is the data assessed for this indicator?** (The data assessed covers a very limited number of public procurements and few other sources of data are available. (E.g., procurements are disclosed for just one government agency.), The data assessed covers or is representative of the data available for a significant number of public procurements, but some procurements are not covered., The data assessed covers or is representative of the data available for all or almost all public procurement (including below-threshold procurements).)
    
        > **Supporting questions** (conditional)
    
        > If The data assessed covers a very limited number of public procurements and few other sources of data are available. (E.g., procurements are disclosed for just one government agency.): Please describe the nature of the procurements the data covers.
    
        > If The data assessed covers or is representative of the data available for a significant number of public procurements, but some procurements are not covered. or The data assessed covers or is representative of the data available for all or almost all public procurement (including below-threshold procurements).: Please explain your answer
    
    * **Existence summary:**
    
    * **Please summarize your answers to the preceding existence sub-questions, including the extent of existence.** [Open Text] 
     *Drawing on the research you have conducted and the evidence you have gathered for this section, describe what you have found (or not found) when answering the existence sub-questions for this indicator.*
    
        > **Supporting questions**
    
        > Please provide the URL(s) for the evidence that supports the summary provided.
    
    **Elements**
    
    * **Kinds of data:**
    
    * **Procurement related to goods and services is included.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please provide the URL(s) where data on goods and services is located.
    
    * **Procurement related to public works is included.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please provide the URL(s) where data related to public works is located.
    
    * **The planning stage is covered.** (No, Partially, Yes)
     *Answer “Yes” if you can locate any data that describes the background of the contracting process in detail rather than just generally; for example, this might include details of the budget from which funds are drawn, related projects for the contracting process, or background documents such as a needs assessment, feasibility study, or project plan.*
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please provide the URL(s) where data on the planning stage is located.
    
    * **The tender stage is covered.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please provide the URL(s) where data on the tender stage is located.
    
    * **The award stage is covered.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please provide the URL(s) where data on the award stage is located.
    
    * **The implementation stage is covered.** (No, Partially, Yes)
     *Answer “Yes” if you can locate any data from after contract award and signature, such as spending transactions, confirmation that goods or services were delivered, contract amendments, or data on contract performance.*
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: What kind of implementation data is available?
    
        > If Partially or Yes: Please provide the URL(s) where data on the implementation stage is located.
    
    * **Data fields and specifics:**
    
    * **The data contains identifiers or other features that connect together data on each stage of a single procurement process.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially or Yes: Please explain your answer.
    
    * **The data contains names and unique identifiers for companies awarded contracts.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If No or Partially or Yes: Please explain your answer.
    
    * **The data contains start and end dates for tender processes and/or contracts.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially or Yes: Please explain your answer.
    
    * **The data contains the value (cost) of each tender, award, or contract.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially or Yes: Please explain your answer.
    
    * **The data contains, or can be linked to, information on spending against the contract.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially or Yes: Please explain your answer.
    
    * **The data contains a description of the goods, services, or works being procured.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially or Yes: Please explain your answer.
    
    * **The data is published according to one or more relevant data standards.** (No, Partially, Yes)
     *This means that the published data follows guidelines that define how data should be collected or recorded, thus ensuring it is comparable and interoperable with other datasets.*
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please briefly explain your “Partially” answer.
    
        > If Partially or Yes: Which standards are in use?
    
    * **The data contains links to accessible tender, award, or contract documentation.** (No, Partially, Yes)
     *Answer “Yes” if it is possible to follow links and download documentation (e.g., tender details, text of contracts) without barriers such as registration or login for all stages of the process covered by the data. Answer “Partially” if linked documents are accessible, but there are barriers to easy access, or documents are only available for some of the states in the data. Answer “No” if no links are available.*
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
    * **Data publication:**
    
    * **The data is available free of charge.** (No, Partially, Yes)
     *This means that the data is accessible without any cost, unlike cases where accessing datasets requires a one-off payment or a subscription fee.*
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
    * **The data is openly licensed.** (No, Partially, Yes)
     *This means that the data is provided under a license that clearly states that anyone may reuse it, with minimal restrictions on its reuse (e.g., attribution, share-alike).*
    
        > **Supporting questions** (conditional)
    
        > If No: If there are explicit restrictions placed on reuse of the data, briefly describe those.
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: If the data is provided with an explicit open license, please provide the name of that license and/or a link to it.
    
    * **The data is published with sufficient language coverage to make it accessible to all or almost all members of the public.** (No, Partially, Yes)
     *Assess this sub-question using the list of languages provided by your regional coordinator. If the country has only one official language (or de facto official language) and no national languages but there are other languages in use in the country, answer “Partially” if the data is available only in a single language. If the country has multiple official, national, or co-official regional languages, answer “Yes” if the data is available in the majority of these languages.*
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please briefly describe the language coverage available.
    
    * **There are accessible and open official tools available to help users explore data.** (No, Partially, Yes)
     *Answer “Partially” if tools make it possible to get at extracts of data without having to download a full dataset. Answer “Yes” if there is an interactive tool that displays user-filtered extracts of the data to answer simple questions without downloading data at all.*
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially: What are the main barriers to accessibility and usability?
    
        > If Partially or Yes: Do these tools rely on AI or machine-learning tools? For example, as interfaces. Please briefly explain.
    
        > If Partially or Yes: Please provide URL(s).
    
    * **The data is timely and updated.** (No, Partially, Yes)
     *If you have also assessed an associated governance framework, evaluate timeliness by comparing against the relevant schedule laid out in that framework. If there is no such schedule, look first for other indications of an expected schedule (e.g., does the site say the data is updated once a year?), and then examine the frequency, regularity, and recency of updates.*
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially: If only some of the relevant data is updated, please explain which.
    
        > If Partially or Yes: When was the most recent update to this data?
    
    * **Historical data is available that allows users to track change over time.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: For what time period(s) (i.e., start and end dates) is data available? 
    
    * **The data is provided in machine-readable format(s).** (No, Partially, Yes)
     *Assess the datasets you have provided in response to this indicator’s sub-questions; if there are multiple datasets, use the best example you can locate in terms of availability of open data. Note this selection in the elements summary box and then also answer the following sub-question (on bulk downloading) with respect to that specific dataset.*
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially: What prevents you from assessing this data as fully machine-readable? 
    
        > If Partially or Yes: Please provide a comma separated list of the formats available
    
        > If Partially or Yes: Please provide the URL(s) where machine-readable data is located. 
    
    * **The machine-readable dataset is available as a whole.** (No, Partially, Yes)
     *Answer “No” if it's only possible to access individual records. Answer “Partially” if it's possible to export extracts of the data. Answer “Yes” if there are bulk downloads or APIs providing access to the whole dataset without financial, technical, or legal barriers.*
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please provide the URL(s) where bulk download access is available or described.
    
        > If Partially or Yes: If bulk access is provided through an API, please provide a link to where the API is described.
    
    * **Negative scoring:**
    
    * **This information is missing required data.** (There is no evidence of data gaps., There is evidence that a portion of mandated data is missing., There is evidence of widespread omissions in mandated data.)
     *In cases where the indicator itself identifies a dataset(s) to assess against—or a separate governance indicator has asked you to determine data requirements of a relevant governing framework—assess against that. In cases where there is no such identified dataset(s) or related governance indicator, please assess based on: the parameters laid out in the publication of the information (e.g., are some fields entirely empty when they shouldn't be?); your local knowledge (e.g., if the data is supposed to include information for all public officials, does the number of total entries seem reasonable?); and any broader research you may have done for this topic (e.g., have media articles decried the incompleteness of this data?). Note: this sub-question examines omissions only of mandated data; so if, for example, laws do not require the reporting of data below certain thresholds, that data is not considered “missing.”*
    
        > **Supporting questions** (conditional)
    
        > If There is evidence that a portion of mandated data is missing. or There is evidence of widespread omissions in mandated data.: Please briefly explain.
    
    * **Nonscoring:**
    
    * **There is evidence of use of this data.** (No, Partially, Yes)
     *Answer “Yes” for more than one example; answer “Partially” for a single example.*
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: In the example(s) provided, who is using this data? E.g., government, civil society, private sector, media, academia, others.
    
        > If Partially or Yes: In the example(s) provided, for what purpose(s) is the data being used? E.g., for accountability, to improve access for marginalized populations, to influence policy for equity or inclusion, for red flag analysis, etc.
    
        > If Partially or Yes: Please provide URL(s) for example(s).
    
    * **Elements summary:**
    
    * **Please summarize your answers to the preceding element sub-questions.** [Open Text] 
     *Drawing on the research you have conducted and the evidence you have gathered for this section, describe what you have found (or not found) when answering the element sub-questions for this indicator.*
    
        > **Supporting questions**
    
        > Please provide the URL(s) for the evidence that supports the summary provided.


=== "Indicator Justification"

    
    A wide range of stakeholders may use public procurement data, from private firms seeking government contracts, to civil society organizations monitoring procurement processes, to governments using their own data to get better value for money. Numerous agreements, including the G8 Open Data Charter, G20 Anti-Corruption Working Group Open Data Principles, and others recognize contracting data as an essential open dataset that can bring social and economic benefits.
    
    Many use cases for public procurement data require that the data connects across the different stages of the procurement process. Many use cases also rely on the availability of a number of core data fields, and benefit from the ability to link to other datasets. This indicator draws on the[ Open Contracting Data Standard](https://standard.open-contracting.org/), developed to support reusable public procurement data.
    
    This indicator also enables time-series continuity with the previous Open Data Barometer study. The 3rd, 4th, and leaders editions of the ODB included a data availability indicator on public contracts, focused on award data. Because this GDB indicator—asked in the first GDB edition and now again with minor refinements in this second edition—supports the disaggregation of data on stages of the contracting process, a more-or-less directly comparable benchmark (availability of award data) can be generated between the GDB and the previous ODB.
    
    However, this GDB indicator is also sensitive to the availability of information for the planning, tender, and implementation stages, as well as to the completeness of the available dataset (that is, whether it represents only a few procurement processes or all the procurement processes carried out by a country). 
    
    Consequently, the GDB version of this indicator may allow countries which only make information on the tender stage available as structured or open data to score more highly than they did in the ODB (which would have given a zero score to a country with no award information). This current GDB indicator may also lead countries that only make information for the award stage partially available and don't provide contract performance information to receive lower scores than the comparable ODB indicator.
    
    [//]: # (column is not supported)
    
    [//]: # (table_of_contents is not supported)
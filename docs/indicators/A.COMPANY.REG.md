# Availability: Company register

To what extent is detailed company information available for public use? 


    
=== "Definitions"
    **Definitions and Identification**
    
    A national company register should contain details of companies that are incorporated within that country. This should include basic company information, such as company name, legal form, status, and registered address, as well as unique identifiers for each company, structured data on company accounts, and details of each director. 
    
    Some countries have only a few forms of corporate entities and registration practices; others have many, from private limited firms, to partnerships, mutual societies, financial institutions, and listed companies. Responsibility for company registration may belong to national registrars, handled through national gazettes, delegated to business associations and chambers of commerce, or to commercial franchise holders operating the registry. Listed companies in particular are often subject to the disclosure requirements of the stock exchange on which they are listed, which can have substantial variations, particularly with respect to the information available on shareholders. 
    
    Many countries operate corporate registration at a subnational level. However, it is increasingly common to find systems that aggregate or search across subnational registers. For example, [Colombia](http://www.rues.org.co/RM) and [Germany](https://www.handelsregister.de/) both have comprehensive portals to access information from local registrars, and [Canada has a beta service](https://beta.canadasbusinessregistries.ca/) covering seven of Canada’s provinces and territories. A notable exception at present is the United States, although third parties have been able to [aggregate data from the majority of states](https://blog.opencorporates.com/2020/12/21/opencorporates-10-years-of-corporate-transparency-and-what-comes-next/). 
    
    To achieve the highest scores on this indicator, it should be possible to easily access data about **all companies** in a country. This might be achieved by:
    
    - Having a central register of companies;
    
    - Government providing an aggregation service that brings together data from local registers; or
    
    - Having standardized or comparable-quality data available from every subnational register, such that a third party can easily aggregate the data. 
    
    **Examples**
    
    - In India, the Ministry of Corporate Affairs maintains a [searchable online register](https://www.mca.gov.in/content/mca/global/en/mca/master-data/MDS.html) that publishes a range of company information, including details about directors. Data can be exported as Excel files from individual entries as well as downloaded in bulk from India’s [Open Government Data Platform.](https://data.gov.in/resource/registrars-companies-roc-wise-company-master-data) 
    
    - Kosovo’s [company register](https://arbk.rks-gov.net/) is searchable not only by business name, fiscal number, and owner’s or authorizer’s ID, but also by business activity. Both the register and related help materials are available in Albanian and Serbian (the country’s official languages), as well as English, and the Kosovo Business Registration Agency publishes aggregate gender analyses [quarterly](https://arbk.rks-gov.net/Page/41).
    
    - New Zealand publishes company information through a searchable online [register](https://companies-register.companiesoffice.govt.nz/) and an API. Bulk downloads in JSON and CSV formats—as well as custom data extracts—are available for free but require [request](https://www.companiesoffice.govt.nz/data-services/ways-to-get-our-data/), which includes signing a [Bulk Data Access Agreement](https://www.companiesoffice.govt.nz/data-services/ways-to-get-our-data/bulk-data-access-agreement/).
    
=== "Research Guidance"
    
    If there are multiple forms of companies in this country operating under different frameworks, you should **focus your assessment on the most common domestic form**, as identified in the [World Bank's Doing Business report](https://archive.doingbusiness.org/en/data) as the country’s “standardized form” (select your country under “Economy Snapshots” and then scroll down). If there are notable variations in the assessment you would make for other common forms of company, please briefly comment on this in the justification.
    
    **Starting points**
    
    - **Sources:** 
    
    	- The [Open Company Data Index](http://registries.opencorporates.com/) includes assessments for most countries in the world; the small print at the bottom of country pages provides links to company register websites. A some assessments were carried out as early as 2012, you will need to check the current state of data availability carefully by reviewing the register itself.
    
    	- The World Bank’s new [Business Ready (B-READY)](https://www.worldbank.org/en/businessready) and previous [Doing Business (2004-2020)](https://archive.doingbusiness.org/en/doingbusiness) surveys include details of countries’ registrars.
    
    - **Search:** 
    
    	- The company register page for details of data downloads or APIs.
    
    - **Consult:** 
    
    	- Third parties who appear to be using bulk data from the company register to ask whether they access this from an open data source or via some other route. 
    
    **What to look for?**
    
    To complete the assessment for this question you will need to access and explore the available data. This may involve running queries on datasets to check the variety of fields included. Look for well-structured data that could be accessed or read into a database row by row. 
    
    Look for evidence that can answer the following questions:
    
    - Is company information **available as structured, open data**?
    
    - **What company data is available? **
    
    	- Does the dataset have a field with a **unique identifier** for each company? 
    
    	- Is** basic company information** available, including company name, legal form, status, and registered address?
    
    	- Are **annual accounts** for each registered company available as structured data?
    
    	- Is information about the **directors **of each company, including names and a unique identifier, available?
    
    	- Is information about the **legal owners/shareholders** of each company, including names, number, and category of shares (e.g., ordinary shares, non-voting shares, preference shares, etc.) available?
    
    <br/>
    
    

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
    
    * **Existence summary:**
    
    * **Please summarize your answers to the preceding existence sub-questions, including the extent of existence.** [Open Text] 
     *Drawing on the research you have conducted and the evidence you have gathered for this section, describe what you have found (or not found) when answering the existence sub-questions for this indicator.*
    
        > **Supporting questions**
    
        > Please provide the URL(s) for the evidence that supports the summary provided.
    
    **Elements**
    
    * **Data fields and specifics:**
    
    * **The data contains unique identifiers for each company.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please provide the URL(s) where company identifiers are located.
    
    * **The data contains basic company information, including company name, legal form, status, and registered address.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially: If one or more of the basic company data features is not covered, please list which (e.g., registered address).
    
        > If Partially or Yes: Please provide the URL(s) where basic company information is located.
    
    * **The data contains details of each director.** (No, Partially, Yes)
     *Data should list all directors for a company, or at least all executive directors. Where a company register clearly only makes details of a single director available it should not be considered to meet even the “Partially” threshold.*
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please provide the URL(s) where directors’ details are located.
    
    * **The data contains details of each shareholder, including names, number of shares, and category of shares.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially: If one or more of the shareholder details is not covered, please list which (e.g., category of shares).
    
        > If Partially or Yes: Please provide the URL(s) where shareholder data is located.
    
    * **Structured data on company accounts is available for each registered company.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please provide the URL(s) where company account data is located.
    
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
    
    * **The data includes information about individuals' sex and/or gender.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please describe what data includes sex and/or gender information.
    
        > If Partially or Yes: Please provide the URL(s) where sex and/or gender information is located.
    
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

    
    [Tabatabai Hesari and Safizade](https://doi.org/10.22059/jcl.2019.284928.633860) (2020) describe an evolution of company registration through three phases, from early  “administrative systems” that focused on allowing founders to obtain a certificate of corporate registration in return for providing some basic information, through a “supportive system” emerging after the economic crisis of the 1930s in which registers sought to also collect financial-economic information in order to reduce information asymmetries between internal and external stakeholders of a company, to a more recent “inexpensive systems” phase in which the emphasis is placed on streamlining company formation and functioning ([Tabatabai Hesari and Safizade 2020](https://doi.org/10.22059/jcl.2019.284928.633860)). 
    
    While some countries may have only a few forms of corporate registration and corporate registers associated with them, in others there are many forms of corporate entity and registration practices applying to different forms of corporation or association, from private limited firms, to partnerships, mutual societies, financial institutions, and listed companies. Responsibility for company registration may belong to national registrars, handled through national gazettes, delegated to business associations and Chambers of Commerce, or to commercial franchise holders operating the registry. Listed companies in particular are subject to the disclosure requirements of the stock exchange on which they are listed, which can have substantial variations, particularly with respect to the information available on shareholders.
    
    The distributed and fragmented nature of corporate registration both within and across countries has meant that, while trade and financial flows have globalized, information on firms has remained surprisingly siloed. The Global Legal Entity Identifier Foundation maintain a list of over 700 business registers around the world. A number of notable efforts to address this fragmented landscape include: the creation of proprietary company information products, such as Dun and Bradstreet’s company information products, used particularly in corporate due diligence and supply chain management; the work of OpenCorporates to scrape existing company registers and publish them as open data; and the creation of the global Legal Entity Identifier (LEI) at the request of the Financial Stability Board to support identification of entities involved in financial markets. However, it remains unclear how far interested parties have effective access to structured and open data on firms across the world—this indicator seeks to address this knowledge gap.
    
    Sustained civil society campaigns have called for greater openness of company records, particularly in the European Union (see, for example, [Quintanilla and Darbishire 2016](https://phplist.access-info.org/uploadimages/files/CompanyRegisters_Report_7April2016.pdf)). In 2019, the [EU Open Data Directive](http://data.europa.eu/eli/dir/2018/843/oj/eng) included “Companies and company ownership” as one of six data categories “having a particular high value for the economy and society,” although campaigners have expressed concern that implementation of this commitment has been slow, in part because governments are reluctant to challenge current funding model of registers that charge for access to data ([Domínguez 2021](https://www.access-info.org/2021-02-08/access-info-call-open-company-registers/)). 
    
    To develop this indicator we have considered both international agreements on company registration and user needs for corporate data. We drew in particular on the interpretive notes of Financial Action Task Force Recommendation 24, which state that, “All companies created in a country should be registered in a company registry” that should record basic information about a company, including “company name, proof of incorporation, legal form and status, the address of the registered office, basic regulating powers (e.g. memorandum & articles of association), a list of directors, and unique identifier such as a tax identification number or equivalent.” The FATF also states that a company should maintain “a register of its shareholders or members, containing the names of the shareholders and members and number of shares held by each shareholder and categories of shares (including the nature of the associated voting rights)” in coordination with the country’s company registry, although it does not require this information to be centrally collected ([FATF/OECD 2023, 94](https://www.fatf-gafi.org/content/dam/fatf-gafi/recommendations/FATF%20Recommendations%202012.pdf.coredownload.inline.pdf)). 
    
    Company information, and company identifiers in particular, is used in a wide range of contexts, including:
    
    - Supporting anti-corruption and anti-money laundering investigations;
    
    - Enabling business intelligence and corporate due diligence;
    
    - Facilitating business processes and data management;
    
    - Supporting cross-border and wealth taxation;
    
    - Generating economic statistics and supporting economic policymaking;
    
    - Analyzing social, environmental, and equity issues across the economy; and
    
    - Improving consumer choice.
    
    This indicator should be broadly comparable to the Open Data Barometer indicator that assessed the availability of company register data, defined as: “A list of registered (limited liability) companies in the country including name, unique identifier, and additional information such as address, registered activities. The data in this category does not need to include detailed financial data such as balance sheet, etc.” (ODB.2013.D7). 
    
    [//]: # (column is not supported)
    
    [//]: # (table_of_contents is not supported)
    
    <br/>
# Availability: Budget and spending data

To what extent is detailed government budget and spending information (budget execution) available for public use? 


    
=== "Definitions"
    **Definitions and Identification**
    
    Most governments carry out an annual budget process, involving proposing and approving a budget, and reporting spending against that budget. The [Open Budget Survey](https://www.internationalbudget.org/open-budget-survey) provides a regular assessment of how transparent this process is, with a focus on the documents involved in the budget process. This indicator complements the evidence collected by the Open Budget Survey by looking specifically at whether structured data is available on: proposed budget, amended budget, approved or enacted budget, government spending, extrabudgetary spending, social security spending, and public corporation spending.
    
    **Budget** *documents* often present summary tables that describe the proposed and enacted budgets. The budget part of this indicator asks whether the *data* behind such summary tables is available. This will usually take the form of a dataset organized with rows that contain the value of each budget line (possibly including proposed, agreed, and amended values), along with columns that provide classifications of the line.
    
    Reporting on **spending** or budget performance should involve showing the total spend against each line of a budget. It may extend to showing information on how the goods, works, or services to be funded by that budget line have been delivered. Structured data on performance might include a dataset, or a column in a budget-related dataset, that shows how much has been spent to date against each budget line.
    
    For budget performance, the indicator asks not only whether the data is available in gross terms, but also on an **accrual basis**—that is, showing the timing of when revenues are earned and expenses incurred.
    
    Further, this indicator assesses the presence of **structured budget classification data **consistent with internationally agreed standards. It asks for checks on four kinds of classification, though researchers are encouraged to add notes in the justification about other forms of notable classification used (e.g., geographical):
    
    - **Administrative classification** identifies the entity that is responsible for managing the public funds described by a budget line, such as the ministry of education and health or, at a lower level, schools and hospitals. 
    
    - **Economic classification **identifies the type of expenditure incurred; for example, salaries, goods and services, transfers and interest payments, or capital spending.
    
    - **Functional classification** categorizes expenditures according to the purposes and objectives for which they are intended. 
    
    - **Program classification** categorizes expenditures according to the programs used to enact public policies, thus aligning policies and programs with administrative structures.
    
    (Sources: [IMF Technical Note on Budget Classification](https://www.imf.org/external/pubs/ft/tnm/2009/tnm0906.pdf) and IMF's [Fiscal Transparency Handbook](https://www.elibrary.imf.org/doc/IMF069/24788-9781484331859/24788-9781484331859/Other_formats/Source_PDF/24788-9781484348598.pdf) (2018))
    
    Data should be disaggregated both at the transaction level and with regard to cross-cutting programs. **Transaction-level spending data** records spending at a granular level, often with many rows of transaction data for each line of the budget; transactional data may include details of each counterparty (e.g., buyer and supplier). 
    
    Two sub-questions of this indicator ask researchers to assess whether the data has identifiers or other features that make it easy to connect:
    
    - Budget and performance/spending
    
    - Budget and procurement
    
    This may take the form of clearly documented classifications that uniquely identify budget lines, or the presence of stable unique identifiers for budget lines. 
    
    **Examples**
    
    - South Africa’s National Treasury partnered with civil society organizations to design and implement [Vulekamali](https://vulekamali.gov.za/), its fiscal transparency portal. Vulekamali provides financial information in different national languages and publishes a wide range of regularly updated financial data—such as government budgets, expenditure reports, and audits—that can be accessed by API or exported as csv files. 
    
    - In Mexico, the government publishes [financial data](https://www.transparenciapresupuestaria.gob.mx/Ciclo-Presupuestario) for federal agencies, social security institutions, state-owned enterprises, and public corporations—covering key government actions such as transfers to local governments, infrastructure projects, subsidies, federal revenue, and procurement—with coordinated fields and identifiers to enable tracking across databases.
    
    - Armenia’s Ministry of Finance publishes [budget and spending information](https://minfin.am/hy/page/interaktiv_byuje) as structured data and provides an easy-to-use interactive tool that allows users to filter and explore data by entities and by functional and economic classifications.
    
=== "Research Guidance"
    
    **Starting points**
    
    - **Sources:** 
    
    	- The Open Budget Survey contains assessments by budget experts on the availability of budget documents. [Country results pages](https://www.internationalbudget.org/open-budget-survey/country-results) contain full researcher responses for each question along with the URLs to data that Open Budget Survey researchers identified. Check carefully to validate the technical assessments made by OBS researchers. This will usually involve opening and examining linked files, and checking if there are other alternative sources of information if the data linked from the OBD survey presents only summary tables. 
    
    		- Question EB-5 asks about the availability of machine-readable data on enacted or approved budgets. 
    
    		- Question IYRs-5, MYRs-5 and YER-5 ask about the availability of machine-readable in-year, mid-year, and year-end reports that may contain data on budget performance.
    
    		- Question GQ-1b asks about the presence of a consolidated dataset of budget information. 
    
    	- The World Bank [produced a dataset (last updated 2017) with details of countries’ financial management information systems (FMIS)](https://datacatalog.worldbank.org/dataset/fmis-and-open-budget-data-global-dataset), including whether or not they provide public data and where it may be located. This can serve as a starting point to identify current budget data sources.
    
    	- The [BOOST Public Expenditure Database](https://datacatalog.worldbank.org/group/boost-public-expenditure-database) contains details of World Bank–supported budget data publication for a number of low- and middle-income countries. 
    
    - **Search:** 
    
    	- "Open budget data" + [country]
    
    - **Consult:** 
    
    	- Open data advocates.
    
    	- Investigative journalists who report on government budgets and expenditures or public finance more broadly, particularly any who appear to be using aggregate public finance data.
    
    	- Officials of civil society organizations that advocate for transparency and accountability regarding public finance.
    
    **What to look for?**
    
    To complete the assessment for this question you will need to access and explore the available data. This may involve running queries on datasets to check the variety of fields included. Look for well-structured data that could be accessed or read into a database row by row. 
    
    Look for evidence that can answer the following questions:
    
    - **What budget data is available? **Does the country publish proposed, amended, and enacted budgets, not just as summary tables, but as the data itself? 
    
    - **What spending data is available?** Does the country publish government spending data, both in gross terms and on an accrual basis, including spending in annual and multi-annual investment projects? Does it do the same for extrabudgetary spending, social security spending, and public corporations spending? 
    
    - **What types of classification are used?** Administrative, economic, functional, program? Are these consistent with internationally agreed standards?
    
    - **Is the data disaggregated both at transaction level and for cross-cutting programs?**
    
    - **Does the data include common identifiers** that support easy analysis across budget and performance, budget and project?
    
    

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
    
    * **How comprehensive, in terms of parts of government covered, is the data?** (The data assessed covers one or more agencies, but there are many agencies without data available., The data assessed covers one or more agencies and there is similar data available for many other parts of government, but the data does not cover the majority of the public sector., The data assessed covers the majority of the public sector (including state-owned enterprises or corporations, extrabudgetary funds, etc.; i.e., a consolidated dataset).)
    
        > **Supporting questions** (conditional)
    
        > If The data assessed covers one or more agencies, but there are many agencies without data available. or The data assessed covers one or more agencies and there is similar data available for many other parts of government, but the data does not cover the majority of the public sector. or The data assessed covers the majority of the public sector (including state-owned enterprises or corporations, extrabudgetary funds, etc.; i.e., a consolidated dataset).: Please explain your answer.
    
    * **Existence summary:**
    
    * **Please summarize your answers to the preceding existence sub-questions, including the extent of existence.** [Open Text] 
     *Drawing on the research you have conducted and the evidence you have gathered for this section, describe what you have found (or not found) when answering the existence sub-questions for this indicator.*
    
        > **Supporting questions**
    
        > Please provide the URL(s) for the evidence that supports the summary provided.
    
    **Elements**
    
    * **Kinds of data:**
    
    * **There is structured data available on the executive budget proposal in gross terms, including spending on annual and multi-annual investment projects.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please provide the URL(s) where data on the executive budget proposal is located.
    
    * **There is structured data available on the approved or enacted budget in gross terms, including spending on annual and multi-annual investment projects.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please provide the URL(s) where data on the approved or enacted budget is located.
    
    * **There is structured data available on amended budgets (when applicable) or amendments of the enacted budget.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please provide the URL(s) where data on amended budgets is located.
    
    * **There is structured data about government budget execution or spending, in gross terms and on an accrual basis, including spending in annual and multi-annual investment projects.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please provide the URL(s) where data on government spending is located.
    
    * **There is structured data about the government's extrabudgetary funds spending, in gross terms and on an accrual basis.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please provide the URL(s) where data on extrabudgetary spending is located.
    
    * **There is structured data about the government's social security spending, in gross terms and on an accrual basis.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please provide the URL(s) where data on social security spending is located.
    
    * **There is structured data about public corporations' spending, in gross terms and on an accrual basis.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially: Please explain your “Partially” response.
    
        > If Partially or Yes: Please provide the URL(s) where data on public corporations' spending is located.
    
    * **Data fields and specifics:**
    
    * **Budget entries have administrative classifications to an internationally agreed standard.** (No, Partially, Yes)
     *Answer “Partially” if there are administrative classifications, but their alignment with international standards cannot be confirmed.*
    
        > **Supporting questions** (conditional)
    
        > If Partially or Yes: Please provide the URL(s) where administrative classifications are located.
    
    * **Budget entries have economic classifications to an internationally agreed standard.** (No, Partially, Yes)
     *Answer “Partially” if there are economic classifications, but their alignment with international standards cannot be confirmed.*
    
        > **Supporting questions** (conditional)
    
        > If Partially or Yes: Please provide the URL(s) where economic classifications are located.
    
    * **Budget entries have functional classifications to an internationally agreed standard.** (No, Partially, Yes)
     *Answer “Partially” if there are functional classifications, but their alignment with international standards cannot be confirmed.*
    
        > **Supporting questions** (conditional)
    
        > If Partially or Yes: Please provide the URL(s) where functional classifications are located.
    
    * **Budget entries have program classifications according to an internationally agreed standard.** (No, Partially, Yes)
     *Answer “Partially” if there are program classifications, but their alignment with international standards cannot be confirmed.*
    
        > **Supporting questions** (conditional)
    
        > If Partially or Yes: Please provide the URL(s) where program classifications are located.
    
    * **Information about individual financial transactions or expenditures is available at the most disaggregated level of the economic classification level.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially or Yes: Please explain your answer.
    
    * **Data is disaggregated by cross-cutting programs, or issues such as SDGs, climate action, gender budgeting, etc,** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially or Yes: Please explain your answer.
    
    * **The data contains common identifiers to connect budget and budget performance data.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially or Yes: Please explain your answer.
    
        > If Partially or Yes: Please provide the URL(s) where these identifiers are located.
    
    * **The data contains identifiers that can be used to connect budget data with data on major projects (e.g., infrastructure construction) and procurement processes.** (No, Partially, Yes)
    
        > **Supporting questions** (conditional)
    
        > If Partially or Yes: Please explain your answer.
    
        > If Partially or Yes: Please provide the URL(s) where these identifiers are located.
    
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

    
    Public financing is critical to achieving the 2030 Agenda. As the International Budget Partnership explains, budgets offer a concrete means to track a country's commitments to achieving the goals, while information on spending reveals whether countries have followed through on these commitments ([2017:1–2](https://www.internationalbudget.org/wp-content/uploads/tracking-spending-sustainable-development-goals-ibp-budget-brief-2017.pdf)). Transparency in public finance supports delivery of SDG 16 on effective, accountable, and inclusive institutions. Indicator 16.6.1 investigates primary government expenditures as a proportion of original approved budget, by sector (or by budget codes or similar). Similarly, indicators for SDG 1 on No Poverty require detailed information on government spending and resource allocation, particularly those for targets 1.a and 1.b. 
    
    While transparency has long been an important principle of public financial management, increasingly fiscal transparency efforts have emphasized providing not only fiscal documents, but also disaggregated data. Perhaps the most impactful use of public finance data is the improvement of public financial management and budget allocation. Data can be used to support gender budget analysis, green budget analysis, and evaluation of the impact of fiscal policy on minorities and marginalized groups. This indicator thus examines the extent to which government budget and spending information—also known as budget execution—is available as structured open data.
    
    <br/>
    
    [//]: # (column is not supported)
    
    [//]: # (table_of_contents is not supported)
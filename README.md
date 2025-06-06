# TimberReach
## Assessing merchantability on NFS lands

The USDA Forest Service (FS) conducts timber sales on National Forests (NFs) for
economic and environmental benefits, such as decreasing fire hazard through removal of
biomass, as well as increasing income to the agency. “No-bids,” or unsold timber offerings, can
cause planned management activities to be delayed, deferred, or require additional time and cost.

Not all acres suitable for timber management are merchantable. Merchantability is subject to factors such as: proximity to mill, road networks, species composition and form, among others. Through prior no-bids research (Bruck and Frey 2023; Frey et al. 2023; Frey at al. 2024; Bruck et al. 2025), we have identified crucial factors that result in timber sales. In addition, we
have found that there are several disparate data sources, many of which are maintained by the FS
Enterprise Data Warehouse (EDW). Once aggregated, we will identify areas of the National Forest landscape that are more or less likely to sell, if advertised.  

### What are National Forest timber sales?

Timber sales are sales of harvestable timber that have mertachability for the private timber market. In this context, they are sales on National Forest lands sold by the U.S. Forest Service – National Forest System as part of their forest management plan. There are three important components to understanding timber sales:

- Where they are sold (The National Forest System)
- How they are prepared (The Gate System)
- What contracts are used to sell them (Types of Contracts)

#### National Forest System

<!-- image -->

#### The Gate System

The easiest way to understand the preparation of timber sales is probably to watch [this video](https:/www.fs.fed.us/forestmanagement/video/GatesNew-3/GatesNew-3.html) about the Gate System, which is the Forest Service’s timber sale preparation process. For reference, see graphic below:

<!-- image -->

The Gate System is numbered 1-6, with 1-3 involving planning and preparation and 4-6 dealing with the advertisement and award of a timber sale. Gate 1 is the initial planning of a timber sale project, including scoping and plan development that identifies the purpose and need of the project. It also identifies potential project plan areas, volume targets, among other things, but does not necessarily specifically identify an individual timber sale. The District Ranger or Forest Supervisor is the appropriate authority for signing off on this phase. Gate 2 is Project Analysis, commonly referred to as the “planning gate” because this is where the environmental analysis required for all timber sale projects on National Forests happens. It also develops alternative designs and an analysis of financial efficiency. A “NEPA decision” which is an approval of the ecological and environmental considerations that are compliant with the National Environmental Policy Act (NEPA), is also signed during this stage. Gate 3 is the preparation of a timber sale where the plan identified and approved in Gate 2 gets divided out as individual sales, where all the subsequent data is done. Gate 4 is when a timber sale gets appraised, input into the TIM system to generate a contract, and advertised. Gate 5 is the bid opening where they hold an auction, if needed, and purchasers input the amount they’re willing to bid. Gate 6 awards the timber sale contract to the apparent high bidder. The gate system provides the basic structure for NFS timber sales from design to award and is integral to understanding the various processes and thresholds that need to be met for the success of timber sales.

#### Types of Contracts

Timber sales are categorized based on different timber sale contracts, depending on their primary use. Though there are various contract types, including those for decked timber or Christmas trees, there are three that are commonly referenced regarding no-bid timber sales:

1.	FS-2400-6/6T. Commonly called “traditional timber sales” that are used for complex sales that cannot be contained in simpler contract forms.

2.	FS-2400-13/13T. Commonly called “stewardship sales” because they cut timber but also include environmental restoration into the contract. Integrated Resource Timber Contracts (IRTC) are utilized when the cost of the timber exceeds the value of the service work.

3.	FS-2400-33/33T. Also commonly called “stewardship sales” for the same reason. However, Integrated Resource Service Contracts (IRSC) are utilized when the cost of the service work exceeds the value of the timber.

All of these sales can either be “scaled”, meaning they are measured for payment after the felling, or “tree measurement”, meaning they are measured for payment after the felling. Tree measurement sales are denoted by the “T” at the end of the contract type (e.g., FS-2400-33T).

For more information on timber sale contracts, [click here](https:/www.fs.fed.us/forestmanagement/products/contracts.shtml) for the USFS Forest Management website.

In addition to the contract, other agreements often come up when discussing no-bid timber sales, such as [Good Neighbor Authority (GNA)](https:/www.fs.usda.gov/managing-land/farm-bill/gna) and [Small Business Set-Asides (SBA)](https:/www.sba.gov/document/report-rin-3245-ag69-small-business-timber-set-aside-program) .

#### What are no-bids?

No-Bid Timber Sales, sometimes referred to as “no-bids”, are simply the absence of a bid on an advertised timber sale. These can occur for a variety of reasons on any timber sale in the National Forest that has a bidding component to it. The issue with no-bids is that they are stopping or delaying treatment to forested lands, forcing that forest or district to re-work and/or re-advertise the sale. This culminates in a loss of money, time, and acres treated, as well as a reduction in the likelihood of meeting that year’s timber targets.

#### Why its important

The Washington Office of Forest Management with the US Forest Service measured their timber sale accomplishments by yearly timber targets. These timber targets are set (nationally) by the USDA and then divvyed up across regions and forests. According to the 2021 budget justification, a total of 4 billion board feet (2021 budget justification) is their target for the year, an 8% increase from the 2020 target of 3.7 billion board feet. Timber targets are not always met, however. In 2020, only 85% of that target was attained. However, if the no-bids originally offered in 2020 had been sold, the US Forest Service would have achieved 99% attainment for the year. For the previous five years, unsold sales had the potential to increased sale volume between 12-19%, which would have exceeded 100% attainment (PTSAR 2015-2020).

### Industry Professionals Interviews

##### How did we decide who to interview?

Due to the Paperwork Reduction Act, we only had the ability to interview 9 people without gaining prior approval for the process. Since there are nine regions, we sought to have a representative from each region as a complement to the NFS personnel interviews and any subsequent research. We asked for one recommendation for a “regional representative” from our NFS personnel interviewees. When they gave us more than one individual, we just chose the middle person on the list. Interviews were conducted over the phone, recorded (with permission), and transcribed.


### TIM Access and Data Extraction

##### What is TIM?

TIM is the Timber Information Management system used by National Forest System employees to input timber sale information and make the contract for the sale. It records everything from Gate 3 onward and has a variety of queries that you can pull from to gain information about timber sales. The queries most commonly utilized will be detailed below in the “What are the important queries to utilize?” section.

##### How do you access it?

TIM is accessed from Natural Resource Manager (NRM) using ONLY Internet Explorer.

Note: you will need to be granted access to TIM/NRM database. The easiest way to do that is to call the FS Help Desk (1-866-945-1354) and tell them you need access to TIM/NRM. You should be able to make that request online through the CEC Digital Workplace ( [https://usdacts-myit.fed.onbmc.com/dwp/app/#/catalog](https:/usdacts-myit.fed.onbmc.com/dwp/app) ) but it’s probably easier to just call.

Once you have access:
Link: [http://fsweb.nrm.fs.fed.us/](http:/fsweb.nrm.fs.fed.us)

<!-- image -->

Click: Login to NRM
Click: Default NRM Dashboard and it will redirect you to eAuthentication (should be an automatic login)

Click: Topics &gt; Business Areas &gt; Timber &gt; Contracts &gt; User Views (shown below)

<!-- image -->

Once you’ve reached this User Views screen, you will start your queries by clicking on a specific Module Name. An example of what it looks like when you click a particular query is shown below. To utilize, click through the desired Field Names and then click Run.

<!-- image -->

The screen when it’s downloading/downloaded:

<!-- image -->

##### What are the important queries to utilize?

A list of important queries are detailed in the codebook, found [here](../../../No_Bids/TIM%20Data/Merged_TIM_queries_+codebook_04262021.xlsx) . The most common queries/user views to utilize are: Latest Sale Gate, Sale Bid Winners, Sale Details, Sale Payment Unit Volume, and No-Bid History. The two most comprehensive for our purposes are **Sale Bid Winners &amp; No-Bid History** . However, as this research continues (and as they update TIM), others might bring more information. It is important to explore all the queries as an exercise just so you understand what is there.

##### What do you do with the query once it’s downloaded?

Once a query is downloaded, it can be used a standalone worksheet in excel or merged if you need multiple columns from different queries. The easiest solution is to merge the queries together using excel, stata, r, or some other software. In order to merge the queries, you’ll need a unique identifier in each worksheet, typically the sale number and sale name. Because different regions, forests, and districts make their own sale numbers and sale names, there are duplications. If you are trying to merge a sheet on a national scale, you’ll likely need both sale name and sale number. Using region code, forest code, and district code will also work. The most updated worksheet can be found right [here](../../../No_Bids/TIM%20Data/Merged_TIM_queries_+codebook_04262021.xlsx) . The first sheet is the code for all variables and short descriptions of each.

##### What have we done so far?

To date, the worksheets downloaded from TIM have been utilized to present basic information and descriptives about no-bid timber sales. The most important variables to the Washington Office for understanding their no-bid situation is: total volume (MBF + CCF), count of no-bids, and contract type. The worksheets and their associated powercharts are available in excel (and some powerpoints) [in this folder](../../../No_Bids/TIM%20Data/TIM%20analysis_powercharts) .

##### What if I have to create a new merge of TIM data?

As mentioned above, we have merged the queries. If the situation arises to have to merge a new set of queries, it is important to know that some user views/queries present a lot of duplicate information. In particular, those that present species descriptions or engineering components will have multiple sale names/numbers rows because they create a row for each portion of road or each species. These will have to be aggregated or summed in order to get an accurate single row for each sale. If those variables are not needed for your analysis, the easiest solution is to exclude them in that particular merge.

##### How is a no-bid defined in TIM?

This is important to understand and will not be immediately intuitive. Though it is mentioned in the codebook, it is important to re-state. No-bids in TIM need to be sorted by INFO\_TYPE. There are three “info types”: 7005 with reoffer, 7005 without reoffer, and previously saved info. 7005 with reoffer means it went no-bid but was reoffered, 7005 without reoffer means it went no-bid but it was not reoffered at any point, and previously saved info is just a vestige of when they reoffered the sale. For the purposes of this research, we are currently defining no-bids as those that went no-bid and were not reoffered, as well as those that went no bid and were reoffered. **This may change!** However, as of right now, most analysis has combined the 7005 with/without reoffer as the definition of “no-bid”. Previously saved info is useful, however, because it tells you *how many times* as sale has been reoffered. Otherwise, it is just a duplication of the 7005’s.

Regions do not generally count a “no-bid” as those that were reoffered so the numbers generated might not match what a report out from the region is about their no-bids situation.

##### What else do I need to know?

TIM is tricky. There are a **lot** of variables and it can be hard to reconcile them all. If you’re not sure, there is a [TIM Contracts Help](http:/fsweb.nrm.fs.fed.us/support/help/tim/Contracts/#t=Overview_book.htm) that is marginally helpful. Otherwise, I have found that talking to people who have extensive TIM experience is helpful. Ashton Hargrave and Carl Maass are some WO folks that are always willing to help. Seth Tiffner is a Regional employee (and interviewee) that has been really helpful regarding TIM.

### Drivers of No-Bids Framework

##### The Framework

<!-- image -->

##### How was it created?

It was created based on the NFS personnel interviews and their most frequently mentioned themes. It is also divided into sale-specific factors (also referred to as proximate, immediate, or direct drivers) and underlying factors. Sale-specific factors are the immediate reasons a purchaser would choose not to bid. Underlying factors are those other factors, often interrelated, that can influence those immediate reasons. It was developed based on deforestation literature, namely [this article](../../../No_Bids/No-Bids%20Manuscript%20Drafts/Literature%20-%20No%20Bids/Geist%20&%20Lambin%20(2002)%20Proximate%20Causes%20of%20Underlying%20Driving%20Forces%20of%20Tropical%20Deforestation.pdf) from Geist &amp; Lambin. A concise explanation of the framework is summarized in [this briefing paper](../../../No_Bids/Research%20Framework/Frey-Wilkens_USDA%20Briefing%20Paper%20on%20No-Bid%20Timber%20Sales%20in%20the%20National%20Forest%20System.pdf) .

##### How has it been utilized?

This framework has been used in briefing papers, as a basis for the surveys that were/will be distributed (details below), and as part of the Forest Product Modernization’s initiative to reduce no-bids. The Washington Office – Forest Management have adopted this framework to help explain no-bids and you might see it pop up in presentations and such.

### National Forest System Personnel Survey

##### What is it?

The National Forest System Personnel Survey was a survey distributed to all National Forest System personnel who work in all levels (district, forest, supervisor, and regional offices). It was made based on the drivers of no-bids framework and the interviews with NFS personnel. The survey itself was made using Microsoft Forms and can be accessed [here](https:/forms.office.com/Pages/DesignPage.aspx?fragment=FormId%3D5zZb7e4BvE6GfuA8-g1GlxRB59TLgrpKiACQQdO_yOtUOE04M1BMUERLVkJBQjFPSVZNTU1BMDFKUi4u%26Token%3D5ea482d3a83b4771b65bb48bc8877cab) (Greg might need to approve your access). It was beta tested with Regional and Forest-level staff and several Washington Office staff also tested the survey for clarity and readability.

##### How was it distributed?

It was distributed by Washington Office in a memo sent to all Regional Foresters who then distributed it to all their Forest- and District-level staff on all National Forests. View a copy of the memo [here](../../../No_Bids/NFS%20Personnel%20Survey/NFS%20Personnel%20Survey%20-%20Memo%20Draft_2_abw%20dww.docx) . The survey was open from February 26 – March 26.

##### How did we analyze the results?

The results of the survey are available [here](../../../No_Bids/NFS%20Personnel%20Survey/National%20Forest%20System%20Personnel%20Questionnaire%20on%20Timber%20Sales(1-784).xlsx) . Since the survey was completed so close to the end of this fellowship, only basic analysis was done to show the amount of respondents and their distribution across regions, forests, and position. The worksheets associated with these charts can be found [in this folder](../../../No_Bids/NFS%20Personnel%20Survey/Results) , along with a generic presentation of results (and Region 2 results) can be found. A basic analysis using Nvivo was done to autocode for themes of the open-ended questions in the survey, including the positive and negative sentiments found in the survey. The nvivo file can be found [here](../../../No_Bids/NFS%20Personnel%20Survey/NFS%20Personnel%20Survey%20Results.nvp) .

### Customer Satisfaction Survey (Industry Professionals Survey)

##### What is it?

The Customer Satisfaction Survey is a complement to the rest of the research and is made in conjunction with the Forest Products Modernization team. A fairly extensive no-bids section is a part of this survey. A word document draft of the survey can be found [here](../../../No_Bids/Timber%20Purchasers%20Customer%20Satisfaction%20Survey/Timber%20purchaser%20customer%20satisfaction%20survey_final.docx) . It was sent through the Generic Clearance for Collection of Routine Customer Feedback with the Office of Management and Budget (OMB). The submission document can be found [here](../../../No_Bids/Timber%20Purchasers%20Customer%20Satisfaction%20Survey/Fast-TrackGenericSubmissionTemplate-FPM%20Customer%20Survey_v2_20210212.docx) .

##### What is the status of this now?

It has gone through a lot of iterations and is currently in somewhat of a limbo stage. Ashley Warriner will be your best point-of-contact on updates to this survey.

## No-bid Sale Contracts

No-Bid Timber Sales are a nuanced and complex issue that impacts all levels of the USDA Forest Service – from a timber marker on a unit to the Chief of the Forest Service to even the Congressional committee who sets yearly timber targets. There is no eliminating no-bids. There is no silver bullet to make the issue disappear. However, we can create a targeted approach to assisting with no-bids that can provide resources on the ground, ensure that the issue is understood at all levels, and maintain the long-haul fight to eliminate no-bids where they can be eliminated. In order to do that, we have to make the first big step of deciding: what is a no-bid? What counts?

As a simple definition, a no-bid is a timber sale that does not receive a bid. In this context, it is a sale that does not receive a bid on National Forest lands. In the data collection phase, it is our experience that any sale that does not receive a bid is counted as a no-bid. This includes any contract type, re-offered/re-advertised bids, and sales that never get sold. Informally, however, we believe that some people “write off” certain no-bid sales because they feel they have no control over those. The issue that comes out of that is the subjectivity of control. Some forests feel that they have no control over SBA set-asides because they *have* to be advertised to small businesses first. Others feel they have no control over traditional timber sales because they have no/limited markets. It is highly dependent on forest and highly dependent on a particular person’s perception.

## Purpose of this GitHub

This Github will house open source data and code for TimberReach. Check back for interim products. 

## Literature and resources

[Literature & Resources](literature.md)

## Collaboration 

This research is made possible via a collaboration with the North Carolina State University Center for Geospatial Analytics and USFS-SRS

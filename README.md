# Research & Development Data Sets 2000 - 2022

This repository contains visualisations and data sets relating to Research & Development Expenditure sourced from Eurostat. The source data has been processed to improve usability.

Source data can be found here:
https://ec.europa.eu/eurostat/databrowser/product/page/RD_E_GERDACT

Datasets are split by the factors detailed below.
Animated visualisations are in the Animations folder.

## Field Definitions

|       Field       | Field Description |
| ----------------: | :---------------- |
|        geo        | Geography / Country Code |
|      geo_name     | Geography / Country Label |
|     sect_perf     | Sector of Performance Code |
|  sect_perf_names  | Sector of Performance Label |
|        unit       | Unit of Measure Code |
|     unit_name     | Unit of Measure Label |
|      rnd_act      | R&D Activity Code |
|    rnd_act_name   | R&D Activity Label |
|        year       | Year |
|        value      | Value of measurement in the specified units |
|     value_note    | Note on measurement |
| interpolated_flag | Indicator of whether or not the value was interpolated |

      

## Geography / Country
<details> 
<summary>Expand Geography / Country</summary>

### Geography
- Euro area - 19 countries  (2015-2022)   
- Euro area – 20 countries (from 2023)      
- European Union - 27 countries (from 2020)

|  |  |  | 
| --- | --- | --- |
| Austria | Bosnia and Herzegovina | Belgium |
| Bulgaria | China except Hong Kong | Croatia |
| Cyprus | Czechia | Denmark |
| Estonia | Finland | France |
| Germany | Greece | Hungary |
| Ireland | Iceland | Italy |                                 
| Japan | Lithuania | Luxembourg |
| Latvia | North Macedonia | Malta |
| Netherlands | Norway | Poland |
| Portugal | Romania | Serbia |
| Switzerland | South Korea | Spain |
| Sweden | Slovenia | Slovakia |
| Türkiye | United Kingdom | United States |

</details>

## Sector of Performance
<details> 
<summary>Expand Sector of Performance</summary>

  ### Business Enterprise
The Business Enterprise sector comprises:
- All resident corporations, including not only legally incorporated enterprises, regardless of the residence of their shareholders. This group includes all other types of quasi-corporations, i.e. units capable of generating a profit or other financial gain for their owners, recognised by law as separate legal entities from their owners, and set up for the purpose of engaging in market production at prices that are economically significant. They include both financial and non-financial corporations.
-  The unincorporated branches of non-resident enterprises deemed to be resident and part of this sector because they are engaged in production on the economic territory on a long-term basis.
- All resident non-profit institutions (NPIs) that are market producers of goods or services or serve business. The former NPI category comprise independent research institutes, clinics and other institutions whose main activity is the production of goods and services for sale at prices designed to recover their full economic costs. The latter category of NPIs serving business comprises entities controlled by business associations and financed by contributions and subscriptions.
- Specifically excluded are units that belong to the Higher education sector. However, commercial firms owned by higher education institutions, for example as a result of agreements that give the university a major shareholding position in a spin-off company set up by staff and/or students, should be treated as business enterprises.

Source: Frascati Manual 2015, Section 7.2

### Government  
The Government sector comprises all units of central (federal), regional (state) and municipal (local) government, including social security funds, except those units that fit the description of higher education institutions as well as all nonmarket non-profit institutions that are controlled by government units, and that are not themselves part of the Higher education sector. 

Source: Frascati Manual 2015, Section 8.2

### Higher Education
The Higher Education sector is composed of:
- All universities, colleges of technology and other institutions providing formal tertiary education programmes, whatever their source of finance or legal status
- All research institutes, centres, experimental stations and clinics that have their R&D activities under the direct control of, or administered by, tertiary education institutions.

Source: Frascati Manual 2015, Section 9.2

### Private Non-Profit
The Private Non-Profit sector comprises:
- All non-profit institutions serving households (NPISH), as defined in the SNA 2008, except those classified as part of the Higher education sector
- For completeness of presentation, households and private individuals engaged or not engaged in market activities.
- Examples of units within this sector may include independent professional and learned societies, and charitable organisations that are not controlled by units in the Government or the Business enterprise sectors. Such NPIs provide individual or collective services to households either without charge or at prices that are not economically significant. In practice, institutions in this sector may be called foundations, associations, consortia, joint ventures, charities, non-governmental organisations (NGOs), etc.

Source: Frascati Manual 2015, Section 10.2

### Total
Total Gross Expenditure on Reasearch and Development. Please note that totaling the other four sectors for any given year may not result in an equal value to TOTAL in the dataset. This is due to the use of interpolated values. 

</details>

## Research & Development Activity
<details> 
<summary>Expand Research & Development Activity</summary>

### Applied research
- Applied research is original investigation undertaken in order to acquire new knowledge. It is, however, directed primarily towards a specific, practical aim or objective.
- Applied research is undertaken either to determine possible uses for the findings of basic research or to determine new methods or ways of achieving specific and predetermined objectives. It involves considering the available knowledge and its extension in order to solve actual problems. In the Business enterprise sector, the distinction between basic and applied research is often marked by the creation of a new project to explore promising results of a basic research programme (moving from a long-term to a medium-short term perspective in the exploitation of the results of intramural R&D).
- The results of applied research are intended primarily to be valid for possible applications to products, operations, methods or systems. Applied research gives operational form to ideas. The applications of the knowledge derived can be protected by intellectual property instruments, including secrecy.

Source: Frascati Manual 2015, Section 2.5

### Basic research
- Basic research is experimental or theoretical work undertaken primarily to acquire new knowledge of the underlying foundations of phenomena and observable facts, without any particular application or use in view.
- Basic research analyses properties, structures and relationships with a view to formulating and testing hypotheses, theories or laws. The reference to no “particular application in view” in the definition of basic research is crucial, as the performer may not know about potential applications when doing the research or responding to survey questionnaires. The results of basic research are not generally sold but are usually published in scientific journals or circulated to interested colleagues. Occasionally, the publication of basic research may be restricted for reasons of national security

Source: Frascati Manual 2015, Section 2.5

### Experimental development
- Experimental development is systematic work, drawing on knowledge gained from research and practical experience and producing additional knowledge, which is directed to producing new products or processes or to improving existing products or processes.
- The development of new products or processes qualifies as experimental development if it meets the criteria for identifying R&D activity. An example is uncertainty about the resources needed to achieve the goal of the R&D project in which the development activity is taking place. In these datasets, the “D” in R&D refers to experimental development.
- **Not “product development”** The concept of experimental development should not be confused with “product development”, which is the overall process – from the formulation of ideas and concepts to commercialisation – aimed at bringing a new product (good or service) to the market. Experimental development is just one possible stage in the product development process: that stage when generic knowledge is actually tested for the specific applications needed to bring such a process to a successful end. During the experimental development stage new knowledge is generated, and that stage comes to an end when the R&D criteria (novel, uncertain, creative, systematic, and transferable
and/or reproducible) no longer apply. As an example, in a process aimed at developing a new car, the option to adopt some technologies could be taken into consideration and tested for use in the car under development: this is the stage when experimental development is performed. It will lead to new results by dealing with new applications of some general knowledge; it will be uncertain, because testing could give rise to negative results; it will have to be creative, as the activity will focus on the adaptation of some technology to a new use; it will be formalised, by needing the commitment of a specialised workforce; and it will involve a codification, in order to translate the results of the tests into technical recommendations for the further stages of the product development process. However, there are cases of product development without R&D that are discussed in the economics literature, especially in the case of SMEs.
- **Not “pre-production development”** The concept of experimental development should not be confused with “pre-production development”, which is the term used to describe nonexperimental work on a defence or aerospace product or system before it goes into production. Similar cases apply in other industries. It is difficult to define precisely the cut-off point between experimental development and preproduction development; the distinction between these two categories requires “engineering judgement” as to when the element of novelty ceases and the work changes to routine development of an integrated system.

Source: Frascati Manual 2015, Section 2.5

### Not specified
R&D activities without a specified category

### Total
Total Gross Expenditure on Reasearch and Development. Please note that totaling the other four sectors for any given year may not result in an equal value to TOTAL in the dataset. This is due to the use of interpolated values. 

</details>

## Unit of Measure
- Purchasing Power Parity at 2005 prices. (Euro) - RD_PPS_KP05.csv

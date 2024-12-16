# CARBON BUDGET ANALYSIS WITH THE TIMES-IRELAND MODEL (TIM)

## Third iteration of modelling to support CCAC Carbon Budgets Working Group <br><br>

### Background
UCC’s Energy Policy and Modelling Group (EPMG) is supporting the Climate Change Advisory Council (CCAC) as part of the Carbon Budgets Working Group (CBWG) in the Council’s statutory role of making recommendations to Government for carbon budgets 3 (covering 2031-35) and carbon budget 4 (2034-40), by the end of 2024. The CBWG is tasked with developing an evidence base for the Council’s carbon budget proposals, including the provision of modelling and analytical support. 

As part of this process, the EPMG is modelling future potential pathways for Ireland’s energy system consistent with different levels of decarbonisation ambition, covering energy supply, electricity, transport, buildings and industry. The purpose of these scenarios is to indicate the pace and depth of change across the energy system necessary to meet different levels of mitigation ambition, including the timing of introducing new technologies, indicating the reliance on speculative technologies, and the role of energy demand reduction. 

The EPMG has already produced two modelling iterations in December 2023 and June 2024, and has undertaken rounds of stakeholder engagement, and adopted feedback from the CCAC following each iteration. 

This webpage includes detailed results for the final iteration of modelled scenarios, presented to the CBWG in August 2024. A detailed accompanying technical report will be submitted to the CCAC by October 2024, and will be published by the CCAC. 

### Scenario assumptions

The TIM scenarios incorporate two types of carbon budget constraints for different periods:

**(1) CB 2021-2050**: This is the overall carbon budget constraint that sets the maximum allowable CO<sub>2</sub> emissions from energy systems for the period 2021 to 2050. 

Five different Carbon Budgets (CB) for the period 2021-2050 are modelled.

* 450Mt CO<sub>2</sub> 

* 400Mt CO<sub>2</sub> 

* 350Mt CO<sub>2</sub> 

* 300Mt CO<sub>2</sub> 

* 250Mt CO<sub>2</sub>

The specified amount reflects the limits in scenario names. For example, the *350Mt* scenario assumes a maximum of 350 million tonnes of CO<sub>2</sub> emissions from energy systems from 2021 to 2050.

**(2) CB 2021-2030**: This budget represents the maximum allowable CO<sub>2</sub> emissions from energy systems for the period 2021 to 2030. In core scenarios, it is assumed that Sectoral Emissions Ceilings (SECs) are met, as outlined in the [Table 3.2 Climate Action Plan](https://www.gov.ie/pdf/?file=https://assets.gov.ie/296414/7a06bae1-4c1c-4cdc-ac36-978e3119362e.pdf#page=null). The total SECs for the periods 2021-2025 and 2026-2030 have a maximum limit of 275 Mt of CO<sub>2</sub> and is fixed across all carbon budget scenarios, apart from WEM and WAM scenarios. In these scenarios, it is assumed that there is an overshoot of the SECs in the period to 2030 according to the emissions as projected by the Environmental Protection Agency, under current and planned policies. 

The figure below shows the CB allocations for various scenarios. In the 250Mt scenario, the CB allocated for 2021-2030 is greater than the total budget for the entire period from 2021 to 2050. The model has limited ability to counterbalance emissions with a negative emissions technology, Bioenergy with Carbon Capture and Storage (BECCS). If in a given scenario the model cannot deliver a given carbon budget considering all the constraints applied, then a "backstop" negative emissions technology is deployed, at a cost of €2000 per tonne of CO<sub>2</sub>. 

<img src="https://github.com/user-attachments/assets/d20c25e9-99cd-4945-8790-0d44f936dd10" alt="Carbon budget3" width="600" />

&nbsp;


#### Core scenarios
These scenarios have an overall carbon budget of 250Mt to 450Mt applied from 2021 to 2050. All five CB scenarios are modeled using a business-as-usual (BAU) demand projection and do not have a suffix, such as "*250Mt*". 

#### Other scenarios
* **Low Energy Demand (LED)**: Four of the lower CBs are modelled using a LED projection. They have LED suffixes such as "*250Mt-LED*". For the detailed assumptions of LED scenarios see Gaur et. al (2022) [Article](https://www.sciencedirect.com/science/article/pii/S2667095X22000083).

* **WAM** & **WEM**: In these scenarios, emissions projections from the Environmental Protection Agency are used as the lower bound for emissions in the pre-2030 period.
* However, the overall CBs remain the same for the 2021-2050 period, using BaU energy demand projections. For example, "*350Mt-WEM*" indicates an overall carbon budget of 350 million tonnes for 2021 to 2050 and 310 million tonnes for 2021 to 2030.

* **LowBio**: This scenario group restricts biomass imports to current levels and no increase is allowed beyond the existing import levels, such as "*250Mt-LowBio*"

* **HighSolarPV**: This scenario significantly increases solar PV adoption, with the maximum allowable capacity rising from 10GW in the core scenarios to 18GW.

### References
##### TIM Documentation Paper
* O. Balyk et al., “TIM: Modelling pathways to meet Ireland’s long-term energy system challenges with the TIMES-Ireland Model (v1.0)” Geoscientific Model Development, vol. 15, 2022 [Link](https://gmd.copernicus.org/articles/15/4991/2022/)
  
##### TIM Application Papers
* **Accelerated vs Delayed Climate Action:** V. Aryanpur et al., “Implications of accelerated and delayed climate action for Ireland’s energy transition under carbon budgets” Nature Portfolio, npj Climate Action, vol. 3, 2024 [Link](https://www.nature.com/articles/s44168-024-00181-7)
* **Decarbonising Trucks:** V. Aryanpur, F. Rogan, “Decarbonising road freight transport: The role of zero-emission trucks and intangible costs” Nature Scientific Reports, vol. 14, 2024 [Link](https://www.nature.com/articles/s41598-024-52682-4)
* **District Heating:** J. Mc Guire et al., “Is District Heating a cost-effective solution to decarbonise Irish buildings?” Energy, vol. 296, 2024 [Link](https://www.sciencedirect.com/science/article/pii/S036054422400882X)
* **Decarbonising Private Cars:** V. Aryanpur et al., “Decarbonisation of passenger light-duty vehicles using spatially resolved TIMES-Ireland Model” Applied Energy, vol. 316, 2022 [Link](https://www.sciencedirect.com/science/article/pii/S0306261922004676)
* **Low Energy Demand:** A. Gaur et al., “Low energy demand scenario for feasible deep decarbonisation: Whole energy systems modelling for Ireland” Renewable Sustainable Energy Transition, 2022 [Link](https://www.sciencedirect.com/science/article/pii/S2667095X22000083)
* **Residential Sector:** J. Mc Guire et al., “Developing decarbonisation pathways in changing TIMES for Irish homes” Energy Strategy Reviews, vol. 47, 2022 [Link](https://www.sciencedirect.com/science/article/pii/S2211467X23000366)
* **Power Sector:** X. Yue et al., “Least cost energy system pathways towards 100% renewable energy in Ireland by 2050” Energy, vol. 207, 2020 [Link](https://www.sciencedirect.com/science/article/pii/S0360544220313712)

### Model and Data Availability
The data used in this research are publicly available on GitHub [link](https://github.com/MaREI-EPMG/times-ireland-model/tree/v1.0.3) and archived on Zenodo [link](https://zenodo.org/records/14337533):

### ACKNOWLEDGEMENTS
We acknowledge and are grateful for the contributions of past and current members of UCC’s Energy Policy and Modelling Group, particularly those who contributed to the development of TIM and its predecessor, the TIMES-Ireland Model. We are also thankful to the CCAC and members of the CBWG, particularly SEAI’s energy modelling team and Prof. John FitzGerald, for constructive feedback on previous iterations of this research. This research was part-funded by the Department of Environment, Climate and Communications through the CAPACITY project. 

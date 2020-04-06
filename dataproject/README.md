# Data analysis project

Our project is titled **Do developed countries manage plastic waste better?**. 
Mismanaged plastic waste is, by ``ourworldindata.org``, defined as "plastic that is either **littered** or **inadequately disposed**". Inadequately disposed waste is not formally managed and it includes disposal in dumps or uncontrolled landfills, where it cannot be fully contained. This waste then might eventually enter the oceans trough water streams, wastewater outflows, or it can be transported by wind.

GDP is one of the indicators of economic activity and it is considered as "world's most powerful statistical indicator of national development and progress". The main objective of this project is to show whether more developed countries can manage plastic waste better than developing countries. In other words, this project focuses on answering these questions:

- Does higher GDP lead to a lower amount of mismanaged plastic waste?
- If more people live in the coastal area, does this country produce a higher amount of mismanaged plastic waste?
- Which continent manages plastic waste the most inadequately?

The **results** of the project can be seen from running [dataproject.ipynb](dataproject.ipynb).

This **loades five datasets**:

1. [per-capita-mismanaged-plastic-waste-vs-gdp-per-capita.csv](per-capita-mismanaged-plastic-waste-vs-gdp-per-capita.csv) downloaded from ourworldindata.org/plastic-pollution
2. [coastal-population-vs-mismanaged-plastic.csv](coastal-population-vs-mismanaged-plastic.csv) downloaded from ourworldindata.org/plastic-pollution
3. [plastic-waste-generation-total.csv](plastic-waste-generation-total.csv) downloaded from ourworldindata.org/plastic-pollution
4. [inadequately-managed-plastic.csv](inadequately-managed-plastic.csv) downloaded from ourworldindata.org/plastic-pollution
5. [country-and-continent-codes-list.csv](country-and-continent-codes-list.csv) downloaded from datahub.io/JohnSnowLabs/country-and-continent-codes-list

**Dependencies:** Apart from a standard Anaconda Python 3 installation, the project requires the following installations:

``pip install matplotlib-venn``

1. Sources
The core dataset comes from the [California Department of Public Health](http://www.cdph.ca.gov/programs/immunize/Pages/ImmunizationLevels.aspx].

2. Definitions of variables in original CA Department of Public Health data
  - Up to date:
    - Four doses of polio vaccine (three doses are acceptable if at least one dose was received on or after the fourth birthday)
    - Five DTP/DT vaccine doses (four doses are acceptable if at least one dose was received on or after the fourth birthday)
    - Two doses of measles-containing vaccine, at least one of which must be measles, mumps, and rubella combined. Both doses must have been received on or after the first birthday
    - Three doses of hepatitis B vaccine
    - One dose of varicella vaccine or physician-documented varicella (chickenpox) disease.
  - Conditional:	A student who does not meet all requirements. This student must be followed up because he/she: lacks (i.e., is not yet due for) at least one dose and does not have a personal beliefs or permanent medical exemption; orhas a physician affidavit of Temporary Medical Exemption for one or more doses; or is a transfer student who has no record available yet.
  - Permanent Medical Exemption	Granted upon the filing with the school of a written statement from a licensed physician to the effect that the physical condition of the student or medical circumstances relating to the student are such that immunization is permanently not indicated.
  - Personal Belief Exemption	A parent signs an affidavit requesting an exemption from the immunization requirements for school entry because all or some immunizations are contrary to the parent's beliefs. 

3. Manipulations on original CA Department of Public Health data
The data, originally on a per-school basis has been aggregated in the following ways:
- Per public school district (excluding private schools from the count).).
- Private vs. Public school totals
- Per-vaccination type

4. Aggregations
We used U.S. Census and ACS data to retrieve additional information about each school district, for the following variables:

- Children 5-17 in poverty - [Small Area Income and Poverty Estimates](http://www.census.gov/did/www/saipe/data/statecounty/data/2012.html)
- Free/Reduced Price Meal Count K-12  - [Student Poverty - FRPM Data](http://www.cde.ca.gov/ds/sd/sd/filessp.asp). In adding this information, we counted only the schools mentioned in the core dataset by California Department of Public Health
- Families with income below poverty level - [National Center for Education Statistics](http://nces.ed.gov/surveys/sdds/framework/tables.aspx?ds=acsProfile&y=2012)

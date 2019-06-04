---
layout: page
title: "Workshop data"
permalink: /data/
---

All of the social science lessons use the same data set throughout. 
The data is tabular (rows and columns), similar in structure to what
you might have in a spreadsheet. 

## The SAFI Teaching Database

Available on FigShare: [https://figshare.com/articles/SAFI_Survey_Results/6262019](https://figshare.com/articles/SAFI_Survey_Results/6262019)

**CITATION:** Woodhouse, Philip; Veldwisch, Gert Jan; Brockington, Daniel; Komakech, Hans C.; Manjichi, Angela; Venot, Jean-Philippe (2018): SAFI Survey Results. doi:10.6084/m9.figshare.6262019.v1

SAFI (Studying African Farmer-Led Irrigation) is a currently running
project which is looking at farming and irrigation methods. This is 
survey data relating to households and agriculture in Tanzania and 
Mozambique. The survey data was collected through interviews 
conducted between November 2016 and June 2017 using forms downloaded
to Android Smartphones. The survey forms were created using the ODK 
(Open Data Kit) software via an Excel spreadsheet. The collected data 
is then sent back to a central server. The server can be used to 
download the collected data in both JSON and CSV formats. This is a 
teaching version of the collected data that we will be using. It is not the full dataset.

The survey covered such things as; household features (e.g. 
construction materials used, number of household members), 
agricultural practices (e.g. water usage), assets (e.g. number and 
types of livestock) and details about the household members.

The basic teaching dataset used in these lessons is a JSON 
formatted dataset which is used directly in the Python lesson.  For
the other lessons a subset of the JSON dataset is used and has been 
converted into CSV format. 

The individual fields and the survey questions asked to produce the 
data in the CSV formatted version are given below. We will only 
reference a subset of the fields in the lessons.

| column_name | description | 
| ----------- | ----------- | 
| key_id | Added to provide a unique Id for each observation. (The InstanceID field does this as well but it is not as convenient to use) | 
| interview_date | Date of interview | 
| quest_no | Questionnaire number | 
| start | Timestamp of start of interview |
| end | Timestamp of end of interview | 
| province | Province name | 
| district | District name | 
| ward | Ward name |
| village | Village name |
| years_farm | Number of years the household have been farming in this area |
| agr_assoc | Does the head of the household belong to an agricultural association? | 
| no_membrs | How many members in the household? |
| _members_count | Internal count of members | 
| remittance_money | Is there any financial assistance from family members not living on the farm | 
| years_liv | How many years have you been living in this village or neighboring village? |
| parents_liv | Did your parents live in this village or neighboring village? |
| sp_parents_liv | Did your spouse's parents live in this village or neighbouring village? | 
| grand_liv | Did your grandparents live in this village or neighbouring village? |
| sp_grand_liv | Did your spouse's grandparents live in this village or neighbouring village? | 
| respondent_roof_type | What type of roof does their house have? | 
| respondent_wall_type | What type of walls does their house have (from list) |
| respondent_wall_type_other | What type of walls does their house have (not on list) | 
| respondent_floor_type | What type of floor does their house have  | 
| window_type | Does the house have glass in at least one window? | 
| buildings_in_compound | How many buildings are in the compound?  Do not include stores, toilets or temporary structures. | 
| rooms | How many rooms in the main house are used for sleeping? | 
| other_buildings | Does the DU own any other buildings other than those on this plot | 
| no_plots | How many plots were cultivated in the last 12 months? | 
| plots_count | Internal count of plots | 
| water_use | Do you bring water to your fields, stop water leaving your fields or drain water out of any of your fields? |
| no_group_count | How many plots are irrigated? | 
| yes_group_count | How many plots are not irrigated? | 
| no_enough_water | Are there months when you cannot get enough water for your crops? Indicate which months. | 
| months_no_water | Please select the months | 
| period_use | For how long have you been using these methods of watering crops? (years) | 
| exper_other | Do you have experience of such methods on other farms? | 
| other_meth | Have you used other methods before? | 
| res_change | Why did you change the way of watering your crops?  | 
| memb_assoc | Are you a member of an irrigation association? | 
| resp_assoc | Do you have responsibilities in that association? | 
| fees_water | Do you pay fees to use water? | 
| affect_conflicts | Have you been affected by conflicts with other irrigators in the area? | 
| need_money | If you started or changed the way you water your crops recently, did you need any money for it? | 
| money_source | Where did the money came from? (list) | 
| money_source_other | Where did the money came from? (not on list) | 
| crops_contr | Considering fields where you have applied water, how much do those crops contribute to your overall income? | 
| emply_lab | In the most recent cultivation season, did you employ day labourers on fields? | 
| du_labour | In the most recent cultivation season, did anyone in the household undertake day labour work on other farm? | 
| liv_owned | What types of livestock do you own? (list) |
| liv_owned_other | What types of livestock do you own? (not on list)| 
| liv_count | Livestock count
| poultry | Own poultry? | 
| du_look_aftr_cows | At the present time, does the household look after cows for someone else in return for milk or money? | 
| items_owned | Which of the following items are owned by the household? (list) | 
| items_owned_other | Which of the following items are owned by the household? (not on list) | 
| no_meals | How many meals do people in your household normally eat in a day? | 
| months_lack_food | Indicate which months, In the last 12 months have you faced a situation when you did not have enough food to feed the household? | 
| no_food_mitigation | When you have faced such a situation what do you do? | 
| gps_Latitude | Location latitude (provided by smartphone) | 
| gps_Longitude | Location longitude (provided by smartphone) |
| gps_Altitude | Location altitude (provided by smartphone) |
| gps_Accuracy | Location accuracy (provided by smartphone) |
| instanceID | Unique identifier for the form data submission |

---
title: Workshop data
permalink: /data/
---

All of the social science lessons use the same data set throughout.
The data is tabular (rows and columns), similar in structure to what
you might have in a spreadsheet.

## The SAFI Teaching Database

Available on FigShare: [https://figshare.com/articles/SAFI\_Survey\_Results/6262019](https://figshare.com/articles/SAFI_Survey_Results/6262019)

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

| column\_name                | description                                                                                                                      | 
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| key\_id                     | Added to provide a unique Id for each observation. (The InstanceID field does this as well but it is not as convenient to use)   | 
| interview\_date             | Date of interview                                                                                                                | 
| quest\_no                   | Questionnaire number                                                                                                             | 
| start                      | Timestamp of start of interview                                                                                                  | 
| end                        | Timestamp of end of interview                                                                                                    | 
| province                   | Province name                                                                                                                    | 
| district                   | District name                                                                                                                    | 
| ward                       | Ward name                                                                                                                        | 
| village                    | Village name                                                                                                                     | 
| years\_farm                 | Number of years the household have been farming in this area                                                                     | 
| agr\_assoc                  | Does the head of the household belong to an agricultural association?                                                            | 
| no\_membrs                  | How many members in the household?                                                                                               | 
| \_members\_count             | Internal count of members                                                                                                        | 
| remittance\_money           | Is there any financial assistance from family members not living on the farm                                                     | 
| years\_liv                  | How many years have you been living in this village or neighboring village?                                                      | 
| parents\_liv                | Did your parents live in this village or neighboring village?                                                                    | 
| sp\_parents\_liv             | Did your spouse's parents live in this village or neighbouring village?                                                          | 
| grand\_liv                  | Did your grandparents live in this village or neighbouring village?                                                              | 
| sp\_grand\_liv               | Did your spouse's grandparents live in this village or neighbouring village?                                                     | 
| respondent\_roof\_type       | What type of roof does their house have?                                                                                         | 
| respondent\_wall\_type       | What type of walls does their house have (from list)                                                                             | 
| respondent\_wall\_type\_other | What type of walls does their house have (not on list)                                                                           | 
| respondent\_floor\_type      | What type of floor does their house have                                                                                         | 
| window\_type                | Does the house have glass in at least one window?                                                                                | 
| buildings\_in\_compound      | How many buildings are in the compound?  Do not include stores, toilets or temporary structures.                                 | 
| rooms                      | How many rooms in the main house are used for sleeping?                                                                          | 
| other\_buildings            | Does the DU own any other buildings other than those on this plot                                                                | 
| no\_plots                   | How many plots were cultivated in the last 12 months?                                                                            | 
| plots\_count                | Internal count of plots                                                                                                          | 
| water\_use                  | Do you bring water to your fields, stop water leaving your fields or drain water out of any of your fields?                      | 
| no\_group\_count             | How many plots are irrigated?                                                                                                    | 
| yes\_group\_count            | How many plots are not irrigated?                                                                                                | 
| no\_enough\_water            | Are there months when you cannot get enough water for your crops? Indicate which months.                                         | 
| months\_no\_water            | Please select the months                                                                                                         | 
| period\_use                 | For how long have you been using these methods of watering crops? (years)                                                        | 
| exper\_other                | Do you have experience of such methods on other farms?                                                                           | 
| other\_meth                 | Have you used other methods before?                                                                                              | 
| res\_change                 | Why did you change the way of watering your crops?                                                                               | 
| memb\_assoc                 | Are you a member of an irrigation association?                                                                                   | 
| resp\_assoc                 | Do you have responsibilities in that association?                                                                                | 
| fees\_water                 | Do you pay fees to use water?                                                                                                    | 
| affect\_conflicts           | Have you been affected by conflicts with other irrigators in the area?                                                           | 
| need\_money                 | If you started or changed the way you water your crops recently, did you need any money for it?                                  | 
| money\_source               | Where did the money came from? (list)                                                                                            | 
| money\_source\_other         | Where did the money came from? (not on list)                                                                                     | 
| crops\_contr                | Considering fields where you have applied water, how much do those crops contribute to your overall income?                      | 
| emply\_lab                  | In the most recent cultivation season, did you employ day labourers on fields?                                                   | 
| du\_labour                  | In the most recent cultivation season, did anyone in the household undertake day labour work on other farm?                      | 
| liv\_owned                  | What types of livestock do you own? (list)                                                                                       | 
| liv\_owned\_other            | What types of livestock do you own? (not on list)                                                                                | 
| liv\_count                  | Livestock count                                                                                                                  | 
| poultry                    | Own poultry?                                                                                                                     | 
| du\_look\_aftr\_cows          | At the present time, does the household look after cows for someone else in return for milk or money?                            | 
| items\_owned                | Which of the following items are owned by the household? (list)                                                                  | 
| items\_owned\_other          | Which of the following items are owned by the household? (not on list)                                                           | 
| no\_meals                   | How many meals do people in your household normally eat in a day?                                                                | 
| months\_lack\_food           | Indicate which months, In the last 12 months have you faced a situation when you did not have enough food to feed the household? | 
| no\_food\_mitigation         | When you have faced such a situation what do you do?                                                                             | 
| gps\_Latitude               | Location latitude (provided by smartphone)                                                                                       | 
| gps\_Longitude              | Location longitude (provided by smartphone)                                                                                      | 
| gps\_Altitude               | Location altitude (provided by smartphone)                                                                                       | 
| gps\_Accuracy               | Location accuracy (provided by smartphone)                                                                                       | 
| instanceID                 | Unique identifier for the form data submission                                                                                   | 



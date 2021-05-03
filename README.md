# 2021_Spring_finals
### Team Members:
1) Nikhil Shenoy (nshenoy3), GitHub: nshenoy3 <br>
2) Anish Pai (asp8), GitHub: anishpai07 <br>
3) Vedant Desai (vdesai29), GitHub: vedantdesai28 <br>

## Vaccine Adverse Effect Reporting System (VAERS) Analysis for COVID-19 Vaccines. <br>

### About VAERS
Established in 1990, the Vaccine Adverse Event Reporting System (VAERS) is a national early warning system to detect possible safety problems in U.S.-licensed vaccines. VAERS is co-managed by the Centers for Disease Control and Prevention (CDC) and the U.S. Food and Drug Administration (FDA). VAERS accepts and analyzes reports of adverse events (possible side effects) after a person has received a vaccination [1].

### Project Goal
Our goal is to analyze COVID-19 vaccination data by exploring the VAERS Vaccination, VAERS Patient Data and VAERS Symptoms datasets [2]. We will not only be exploring three different COVID Vaccines (MODERNA, PFIZER, JANSSEN) related data but will also look into Patient data such as age, any pre-existing medical conditions, allergies, etc. Finally, also want to get an idea of which vaccine has proven to be the most efficient in terms of preventing the recontraction of COVID and minimum resulting symptoms in the patient. 

### Hypothesis 1
Conducting a test to identify which vaccine manufacturer had the lowest count of reported adverse effects. <br>
Note: This is indicative only of the REPORTED cases within the VAERS Datasets, and does not take into account the total number of cases across all vaccinations. <br>
Hence we can only prove correlation and not causation.

H0: Vaccines manufactured by Moderna have the lowest count of reported adverse effects. <br>
HA: Vaccines manufactered by Morderna do not have the lowest count of reported adverse effects.

<img src="https://user-images.githubusercontent.com/71370024/116842764-4a547500-aba3-11eb-9837-baa5533200f6.png" width="450" height="520">

### Hypothesis 2

<b>Hypothesis :</b> People with underlying health conditions or allergies are more likely to develop symptoms after taking a vaccine.<br>

The Aim of this hypothesis is to determine if any existing allergies and health conditions played a role in person developing symptoms post covid vaccination.<br>

<b>Note:</b> For presentation purpose we have just cleaned the complete data set to normalize existing allergies and existing medical history column so that we could do some analyses.<br>
We have analyzed for now how many people with exiting issues developed any symptom against people with no existng issues developing symptoms post getting vaccinated.

<img src="Capture.PNG" width="450" height="450">
<br>


<b>Future Implementation:</b><br>
For more more complex analysis we will then add correlation between existing health condition and the type of symptoms developed by the patient and then draw a comparison graph of which existing medical condition caused or was associated to how any symptoms.

### Hypothesis 3
<b>Hypothesis: </b>Experts predict that usually the onset of the symptoms from the side effect of vaccines usually start to hit within 24 hours of the dose and do not stretch 7 days post the vaccination <br>
<br>
A lot of data is the dataset was missing. This dataset there were lot of typing mistakes as well, which were affecting the graphs and the calulations. Hence a lot of data cleaning had to be performed on this dataset <br>
I have considered the data of the 3 Major vaccines: Moderna, Pfizer and Jannsen.

H0: Onset of symptoms from the vaccine start with 24 hours of the vaccination <br>
HA: Onset of symptoms from the vaccine start after 24 hours of the vaccination

<img src="moderna.jpg" width="450" height="450">

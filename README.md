# Hospital Mortality Prediction
## CPSC392 by Ariel Kuo, Jonathan Vergonio, McKinley Pieper

Our group wanted to investigate what predictors or health conditions can lead to in-hospital mortality, and provide recommendations/inform healthcare professionals about these vital signs. Our dataset had originally had 51 variables and 428 datapoints. Dataset was provided via Kaggle.

## Variables Description
* Outcome(B): Patience outcome (0 Alive, 1 Dead).
* Age(D): Age of patient at the time of hospital admission.
* Gender(CA): Gender 1 and Gender 2 (data set does not specify which gender is which).
* BMI(C): Body Mass Index of patient at the time of hospital admission.
* Hypertensive(B): High Blood Pressure Low (0 = Doesn’t Have, 1 = Has).
* Atrialfibrillation(B): irregular Heart Rhythm (0 = Doesn’t Have, 1 = Has).
* CHD with no MI(B): Congenital heart defects with No Myocardial Infarction (0 = Doesn’t Have, 1 = Has).
* Diabetes(B): Diabete (0 = Doesn’t Have, 1 = Has).
* Deficiencyanemias(B): Iron deficiency (0 = Doesn’t Have, 1 = Has).
* Depression(B): Depression (0 = Doesn’t Have, 1 = Has).
* Hyperlipemia(B): High cholesterol  (0 = Doesn’t Have, 1 = Has).
* Renal failure(B): Inability of the kidneys to perform excretory function leading to retention of nitrogenous waste products from the blood (0 = Doesn’t Have, 1 = Has).
* COPD(B): Chronic Obstructive Pulmonary Disease (0 = Doesn’t Have, 1 = Has).
* Heart rate(C): Heart Rate.
* Systolic blood pressure(C): Measures the pressure in your arteries when your heart beats.
* Diastolic blood pressure(C): Measures the pressure in your arteries when your heart rests between beats.
* Respiratory rate(C): Breathing rate.
* Temperature(C): Body temperature.
* SP O2(C): Saturation Pulse Oxygen: Blood oxygen level.
* Urine output(C): Urine output in first 24 hours.
* Hematocrit(C):  The percentage by volume of red cells in your blood.
* RBC(C): Red Blood Cell Count.
* MCH(C): Mean Corpuscular Hemoglobin - A measurement of the average amount of hemoglobin in each red blood cell
* MCHC(C): Mean Corpuscular Hemoglobin Concentration - A measure of the concentration of hemoglobin in red blood cell
* MCV(C): Mean Corpuscular Volume - A measure of the average volume of a red blood corpuscle.
* RDW(C): Red Blood Cell Distribution Width - Measures the differences in the volume and size of your red blood cells
* Leucocyte(C): A cell that circulates in the blood and body fluids and is involved in counteracting foreign substances and disease; a white (blood) cell. 
* Platelets(C): Cells that form clots and stop or prevent bleeding
* Neutrophils(C): White Blood Cell that kills and digests bacteria and fungi.
* Basophils(C): White Blood cells thats sound an alarm when infectious agents invade your blood.
* Lymphocyte(C): White Blood cell that creates antibodies to fight against bacteria, viruses, and other potentially harmful invaders.
* PT(C): Prothrombin Time: Measures how long it takes for a clot to form in a blood sample.
* INR(C): International Normalized Ratio: Calculation based off of PT.
* NT-proBNP(C): Heart failure by measuring the amount of BNP or its prohormone NT-proBNP in the bloodstream, respectively.
* Creatine kinase(C): Measure of enzyme that's found in your skeletal muscle, heart muscle and brain/
* Creatinine(C): Measure of chemical waste product of creatine.
* Urea nitrogen(C): Measures the amount of urea nitrogen in your blood.
* Glucose(C): Measures blood sugar.
* Blood potassium(C): Measures blood potassium.
* Blood sodium(C):  Measures blood sodium.
* Blood calcium(C):  Measures blood calcium.
* Chloride(C): Measures Chloride(a type of electrolyte.
* Anion gap(C): A way to check the acid-base balance (pH balance) of your blood. 
* Magnesium ion(C): Measure of water hardness.
* PH(C): Hydrogen Ion Concentration: The logarithm of the reciprocal of the hydrogen ion concentration in gram moles per liter.
* Bicarbonate(C): Measures how many millimoles of carbon dioxide is in a liter, or about a quart, of fluid (mmol/L).
* Lactic acid(C): Measures the level of lactic acid made in the body.
* PCO2(C): The measure of carbon dioxide within arterial or venous blood.
* EF(C or intervals): A measure of how much blood was pushed out of the left side of the heart.

# Foodborne Illness Outbreaks
### Common cause of disease
- 48 million people get sick each year in the United States
- 128,000 hospitalizations
- 3,000 deaths
### Terminology
    - Foodborne illness
        - Medical: gastroenteritis
- Common: food poisoning
- Pathogen: an organism with potential to cause disease; typically:
    - Virus
    - Bacteria
    - Fungus
    - Parasite
- Infection: pathogen causing disease
### Treatment
    - Supportive care
        - Oral rehydration salts
        - Intravenous fluids
    - Antibiotics typically do not improve outcomes, and are generally reserved for cases requiring hospitalization
    - Some anti-toxins are effective
### Data
    - CDC foodborne illness outbreak investigation reports
    - Obtained from Kaggle
    - 19,119 investigations from 1998 - 2015
    - Source (food) identified in 10,156 outbreaks (53.1%)
    - Etiology (cause) identified in 16,500 outbreaks (65.4%)

<br />
<br />

![Sources](https://github.com/heathcliffs34/capstone_1/blob/master/figures/present/etiologies.png)
- Salmonella is the cause of typhoid, and was the subject of a well-known epidemiologic study that traced numerous outbreaks to Mary Mallon AKA Typhoid Mary in New York in the early 20th century
- Norovirus is well-known for causing gastroenteritis on cruise ships
- Staphylococcus aureus
    - Commonly known as ‘Staph infection,’ especially if it occurs on the skin
    - Named MRSA if it is resistant to methicillin, an antibiotic in the penicillin family
- Escherichia coli is also known as E. coli
- Shigella is the most common cause of dysentery, or bloody diarrhea

<br />
<br />

![Mortality](https://github.com/heathcliffs34/capstone_1/blob/master/figures/present/mortality_and_rate.png)
- Listeria causes both the highest absolute and relative number of fatalities
- Mycotoxins are fungal-derived toxins that can pass through the food chain without being degraded by digestion
- Botulism primarily affects infants who don’t yet have a full complement gut flora
- Cholera infections are highly correlated with sanitation

<br />
<br />

![In-Hospital-Mortality](https://github.com/heathcliffs34/capstone_1/blob/master/figures/present/mortality_per_hospitalization.png)
- Rotavirus is common among children
    - Young people have high resilience so may be more advanced disease at the time of presentation
    - No curative treatment available
- Listeria can cause meningitis in newborns, and pregnant women are advised to avoid unpasteurized dairy

<br />
<br />

![Top-Hospital-Mortality](https://github.com/heathcliffs34/capstone_1/blob/master/figures/present/top_hospitalizations_fatality_rates.png)

<br />
<br />

![Rates](https://github.com/heathcliffs34/capstone_1/blob/master/figures/present/top_rates.png)

<br />
<br />

![Sources](https://github.com/heathcliffs34/capstone_1/blob/master/figures/present/sources.png)
- Inaccurate natural language processing limits generalizability in this representation
- Inconsistencies with how similar exposures were recorded
- Multiple foods listed in individual outbreaks with unclear relationship

<br />
<br />

# If the source (food) of an outbreak is known, what is the probability of each potential etiology (cause)?
![Food_Given_Disease](https://github.com/heathcliffs34/capstone_1/blob/master/figures/present/food_given_disease.png)
- For readability, only data from foods with minimum (n > 100) number of illnesses were included
- Again, innacture natural language processing dilutes this effect

<br />
<br />

# If the etiology(cause) of an outbreak is known, what is the probability it came from each potential source(food)?
![Disease_Given_Food](https://github.com/heathcliffs34/capstone_1/blob/master/figures/present/disease_given_food.png)
- All diseases are represented, but manual cleaning was employed to select targets, which were reported in a hetergeneous way

<br />
<br />

![Annual_State_Illnesses](https://github.com/heathcliffs34/capstone_1/blob/master/figures/present/annual_states.png)

<br />
<br />

# Reportable Infectious Diseases in Maine: 2007 Summary

“Enteric diseases - Giardiasis, campylobacteriosis, and salmonellosis were the three most commonly reported enteric infections in Maine in 2007. Multiple outbreaks of gastrointestinal disease were reported during the year; an etiologic agent was not identified in many cases.”

<br />
<br />

![Norovirus](https://github.com/heathcliffs34/capstone_1/blob/master/norovirus.png)

<br />
<br />

![Norovirus-Winter](https://github.com/heathcliffs34/capstone_1/blob/master/figures/present/norovirus_winter.png)
- Prior probability includes that ‘disease’ is a given
- Non-overlapping curves suggest that norovirus’ nickname is warranted

<br />
<br />

![Bacillus-Rice](https://github.com/heathcliffs34/capstone_1/blob/master/figures/present/bacillus_rice.png)
- If Bacillus cereus is identified, food source is most likely rice
- Classic teaching from medical school that is also supported by this data


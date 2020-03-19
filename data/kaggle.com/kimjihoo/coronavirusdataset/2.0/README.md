#Case.csv

Columns
case_id

the ID of the infection case
province

Special City / Metropolitan City / Province(-do)
city

City(-si) / Country (-gun) / District (-gu)
group

TRUE: group infection / FALSE: not group
infection_case

the infection case (the name of group or other cases)
confirmed

the accumulated number of the confirmed
latitude

the latitude of the group (WGS84)
longitude

the longitude of the group (WGS84)


# PatientInfo.csv

Columns
patient_id

the ID of the patient
global_num

the number given by KCDC
sex

the sex of the patient
birth_year

the birth year of the patient
age

the age of the patient
country

the country of the patient
province

the province of the patient
city

the city of the patient
disease

TRUE: underlying disease / FALSE: no disease
infection_case

the case of infection
infection_order

the order of infection
infected_by

the ID of who infected the patient
contact_number

the number of contacts with people
symptom_onset_date

the date of symptom onset
confirmed_date

the date of being confirmed
released_date

the date of being released
deceased_date

the date of being deceased
state

isolated / released / deceased

# PatientRoute.csv

Columns
patient_id

the ID of the patient
global_num

the number given by KCDC
date

YYYY-MM-DD
province

Special City / Metropolitan City / Province(-do)
city

City(-si) / Country (-gun) / District (-gu)
latitude

the latitude of the visit (WGS84)
longitude

the longitude of the visit (WGS84)

# Region.csv

Columns
code

the code of the region
province

Special City / Metropolitan City / Province(-do)
city

City(-si) / Country (-gun) / District (-gu)
latitude

the latitude of the visit (WGS84)
longitude

the longitude of the visit (WGS84)
elementary_school_count

the number of elementary schools
kindergarten_count

the number of kindergartens
university_count

the number of universities
academy_ratio

the ratio of academies
elderly_population_ratio

the ratio of the elderly population
elderly_alone_ratio

the ratio of elderly households living alone
nursing_home_count

the number of nursing homes

# SearchTrend.csv

Columns
date

YYYY-MM-DD
cold

the search volume of 'cold' in Korean language
flu

the search volume of 'flu' in Korean language
pneumonia

the search volume of 'pneumonia' in Korean language
coronavirus

the search volume of 'coronavirus' in Korean language

# Time.csv

Columns
date

YYYY-MM-DD
time

Time (0 = AM 12:00 / 16 = PM 04:00)
test

the accumulated number of tests
negative

the accumulated number of negative results
confirmed

the accumulated number of positive results
released

the accumulated number of releases
deceased

the accumulated number of deceases

# TimeAge.csv

Columns
date

YYYY-MM-DD
time

Time
age

the age of patients
confirmed

the accumulated number of the confirmed
deceased

the accumulated number of the deceased

# TimeGender.csv

Columns
date

YYYY-MM-DD
time

Time
sex

the gender of patients
confirmed

the accumulated number of the confirmed
deceased

the accumulated number of the deceased

# TimeProvince.csv

Columns
date

YYYY-MM-DD
time

Time
province

the province of South Korea
confirmed

the accumulated number of the confirmed in the province
released

the accumulated number of the released in the province
deceased

the accumulated number of the deceased in the province

# Weather.csv

Columns
code

the code of the region
province

Special City / Metropolitan City / Province(-do)
date

YYYY-MM-DD
avg_temp

the average temperature
min_temp

the lowest temperature
max_temp

the highest temperature
precipitation

the daily precipitation
max_wind_speed

the maximum wind speed
most_wind_direction

the most frequent wind direction
avg_relative_humidity

the average relative humidity

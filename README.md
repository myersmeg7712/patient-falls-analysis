# Patient Falls Analysis

## Project Overview

This project analyzes a fictional dataset of 120 inpatient fall events to identify patterns that may help guide fall-prevention efforts.

The analysis was approached from a nursing informatics perspective, combining clinical knowledge with data analysis to identify trends, recognize limitations in the available data, and develop recommendations for further investigation.

## Tools Used

- Microsoft Excel
- PivotTables
- PivotCharts
- Interactive slicers
- Healthcare data analysis
- Clinical workflow analysis

## Analysis Questions

The analysis focused on several questions:

- Where are patient falls occurring most frequently?
- What types of falls are most common?
- How severe are fall-related injuries?
- Are there patterns associated with staffing levels?
- Are there patterns related to time of day?
- What additional clinical data would be needed to better understand fall risk?

## Key Findings

### Patient Rooms Were the Most Common Fall Location

Patient rooms accounted for 50 of the 120 recorded fall events (41.7%), making them the most common location for falls.

Of the 50 falls occurring in patient rooms, 25 (50%) were unassisted.

This suggests that patient-room workflow and fall-prevention practices may warrant further investigation.

### Approximately One in Four Falls Resulted in Injury

Of the 120 fall events:

- 89 resulted in no injury
- 22 resulted in minor injury
- 9 resulted in moderate injury
- 0 resulted in major injury

Overall, 31 falls (25.8%) resulted in some level of injury.

### Staffing Patterns Require Additional Context

Adequate staffing was documented during 92 fall events (76.7%), while below-target staffing was documented during 28 events (23.3%).

These counts alone cannot determine whether staffing level affects fall risk because the dataset does not include the total number of adequately staffed and below-target shifts or patient-hours.

### Evening Falls May Warrant Further Investigation

Approximately 32% of recorded falls occurred between 18:00 and 23:59.

From a clinical workflow perspective, this period may include evening medication administration, bedtime care, shift-transition activities, and increased confusion among some hospitalized patients.

Additional analysis would be needed to determine whether these factors are associated with the observed fall events.

## Clinical Recommendations

Based on the patterns identified, I would recommend further evaluation of patient-room fall-prevention processes.

One potential intervention would be a standardized safety check whenever staff leave a patient's room. The check could include:

- Confirming patient needs have been addressed
- Ensuring the call light is functioning and within reach
- Confirming appropriate bed-alarm use
- Ensuring required mobility aids are accessible
- Reinforcing instructions to request assistance before ambulation

Because a relatively large proportion of falls occurred during the evening period, staffing workflow during this timeframe should also be reviewed. Leadership could evaluate whether additional support staff during evening medication administration and bedtime care could improve patient supervision and fall-prevention practices.

These recommendations should be evaluated with additional data before implementation.

## Data Limitations

Several limitations prevent conclusions about the causes of falls.

The dataset contains fall events but does not include a comparison group of patients who did not fall. Therefore, it cannot determine whether specific characteristics increase a patient's probability of falling.

Unit census and patient-day data are also unavailable. Although the orthopedic unit accounted for the largest proportion of recorded falls, the dataset cannot determine whether this unit had a higher fall rate because patient volume differs between units.

Call-light availability was documented, but the dataset does not indicate whether the call light was functioning, within reach, activated by the patient, or responded to by staff.

Additional useful variables would include:

- Bed-alarm status
- Call-light activation and response time
- Patient census and patient-days by unit
- Staffing hours and staffing ratios
- Mobility assistance requirements
- Whether prescribed assistive devices were being used
- Cognitive status or acute confusion
- Total patient population, including patients who did not fall

## Dashboard

An interactive Excel dashboard was created to summarize the findings. The dashboard includes:

- Total fall events
- Most common fall location
- Most common fall pattern
- Percentage of falls resulting in injury
- Injury severity
- Fall location
- Fall type by location
- Interactive filters for hospital unit and fall type

## Dataset

The dataset used for this project is fictional and was created for educational and portfolio purposes. It does not contain real patient information or protected health information (PHI).

# Data Sprint #8: Audit Data

Predict the fraudulent firm

# Context
What Is an Audit?

The term audit usually refers to a financial statement audit. A financial audit is an objective examination and evaluation of the financial statements of an organization to make sure that the financial records are a fair and accurate representation of the transactions they claim to represent.

<p align="center">
  <img src="https://dphi-courses.s3.ap-south-1.amazonaws.com/Datathons/audit-blackboard-planning.jpg" width="500" title="hover text">
</p>

Exhaustive one-year non-confidential data in the year 2015 to 2016 of firms is collected from the Auditor Office of India.

# Objective
The goal here is to help the auditors by building a classification model that can predict the fraudulent firm on the basis of present and historical risk factors.

# About the Data
The information about the sectors and the counts of firms are listed respectively as Irrigation (114), Public Health (77), Buildings and Roads (82), Forest (70), Corporate (47), Animal Husbandry (95), Communication (1), Electrical (4), Land (5), Science and Technology (3), Tourism (1), Fisheries (41), Industries (37), Agriculture (200)

# Data Description
Many risk factors are examined from various areas like past records of audit office, audit-paras, environmental conditions reports, firm reputation summary, on-going issues report, profit-value records, loss-value records, follow-up reports etc. After in-depth interviews with the auditors, important risk factors are evaluated and their probability of existence is calculated from the present and past records.

 

Some of the columns/features are:

Sector_score: sector score of the firm

LOCATION_ID: location id of the firm

score_X: different types of score values

risk_X: different types of risk levels

Inherent_Risk: the risk posed by an error or omission in a financial statement due to a factor other than a failure of internal control.

CONTROL_RISK: Control Risk is the risk of a material misstatement in the financial statements arising due to absence or failure in the operation of relevant controls of the entity.

Detection_Risk: Detection Risk is the risk that the auditors fail to detect a material misstatement in the financial statements.

Audit_Risk: Audit risk (AR) refers to the risk that an auditor may issue an unqualified report due to the auditor's failure to detect material misstatement either due to error or fraud. This risk is composed of Inherent risk (IR), Control risk (CR), and Detection risk (DR)

Audit risk can be calculated as:

AR = IR × CR × DR

Money_Value: Value for money of an audit

Risk: Whether the firm is fraudulent or not. The target value

Feel free to use Google for some of the terms that you don't understand.

# Evaluation Criteria
Submissions are evaluated using F1 Score.

<p align="center">
  <img src="https://dphi-courses.s3.ap-south-1.amazonaws.com/Datathons/f1_score.png" width="500" title="hover text">
</p>

# Sears Home Warranty and Protection Agreements Data

## Data Dictionary

Column Name | Description
------------ | -------------
GID | Deduped hashed ID for a member
CID | Hashed unique ID for Sears Home Services customers – same member could have multiple of these.
AGR_SUF_NO | Agreement suffix number. Unique number assigned for each agreement of a customer.
CUR_ITM_CVR_QT | Number of items covered in the agreement. Protection Agreement can cover multiple items and this value indicates that. By default Home Warranty covers up to 10 appliances in a home and it shows 0 for these contracts.
SVC_PRD_CD | Service Product Code: indicates the type of contract. PA1: Protection Agreement. HWP: Home Warranty
AGR_CNC_IND_FL | Indicator for agreement cancellation before its expiry. (Y/N)
SL_DT | Agreement sale date.
CUR_STA_DT| Agreement start date.
CUR_EPR_DT | Agreement expiry date, adjusted for cancellations.
ORI_EPR_DT | Original agreement expiry date.
MTH_CVR_NO_QT | Agreement duration at the time of sale, indicated for PAs and as 0 for HW.
ITM_SUF_NO | Unique number assigned to the appliance covered. HS_CUS_NO + ITM_SUF_NO gives a uinque ID for an appliance.
CUR_STA_DT_ITEM | Start date of agreement on the appliance when multiple appliances are covered in a PA.
CUR_EPR_DT_ITEM | Expiry date of agreement, adjusted for cancellations, for the appliance when multiple appliances are covered in a PA.
ORI_EPR_DT_ITEM | Original expiry date of agreement for the appliance when multiple appliances are covered in a PA.
MTH_CVR_NO_QT_ITEM | Agreement duation corresponding to the appliance when multiple appliances are covered in a PA.
AGR_ITM_STS_CD | Agreement status code corresponding to the appliance when multiple appliances are covered in a PA.
CNC_DT | Cancellation date corresponding to the appliance when multiple appliances are covered in a PA.
SL_DT_ITEM | Sale date corresponding to the appliance when multiple appliances are covered in a PA.
APPLIANCE | Type of appliance covered.
PSV_ITM_MDL_NO | Appliance model number.
PRD_ITM_NO | Sears product number.
PSV_MDS_SRL_NO | Serial number.
MFG_BND_NM | Brand




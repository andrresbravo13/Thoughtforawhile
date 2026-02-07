# Data Governance

This program uses a simple default: **public data or synthetic data** unless there is a formal, approved reason to do otherwise.

## Data sources (default order)
1) Public datasets (with clear licenses)
2) Synthetic data and simulated vignettes
3) Governance-approved institutional data (only if properly authorized)

## What never goes public
- Patient-identifying information
- Screenshots or exports of real clinical charts
- Private institutional datasets or documents
- Any data that violates consent, policy, or law

## Documentation standards
For every dataset used in a project:
- A **Dataset Card** (source, license, composition, limitations, ethics notes)
- Documented splits (train/val/test)
- A note on representativeness and potential bias

## If clinical collaboration happens
Before any real institutional data is used:
- Confirm governance requirements (REB/IRB/QI determination)
- Data sharing agreement (DSA) and access controls
- De-identification and secure storage plan
- Defined scope, endpoints, and evaluation plan
- A publication and attribution plan (if applicable)

## Practical promise
If it’s not clearly allowed, **I won’t use it**.

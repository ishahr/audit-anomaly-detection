
# Financial Transaction Audit & Anomaly Detection

Audit-style anomaly detection across 3,320 company transactions, using Excel formulas to flag patterns commonly associated with fraud, error, or compliance risk.

## Key Findings
- **Duplicate payments**: 70 transactions share vendor + amount with another entry, including two vendors paid identical amounts 3x across the year by different approvers
- **Round-number bias**: 52 transactions had suspiciously round amounts (exact multiples of ₹1,000)
- **Threshold structuring**: 71 transactions clustered just under a likely ₹10,000 approval limit
- **Weekend activity**: 900 transactions flagged on weekends — analysis showed this matched random chance in this dataset, illustrating the importance of validating flags against a baseline rather than assuming all flags are meaningful

## Tools Used
Excel (COUNTIFS, MOD, conditional flagging formulas)

## Data
https://1drv.ms/x/c/f18e03df3ac13079/IQBhtOaBIhNtQrsblmKJqQbTAXdcqJpIsZImtL9n43rvVaw?e=fO6IG4
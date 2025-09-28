# Approval Process for High-Value Deals

## Process Details
- **Object**: Opportunity
- **Process Name**: High_Value_Deal_Approval
- **Unique Name**: High_Value_Deal_Approval
- **Entry Criteria**: Amount > 10,000,000 (1 crore)
- **Approver**: Sales Manager (from role hierarchy)

## Existing Role Hierarchy
- CEO (top role)
  - Sales Manager (reports to CEO)
    - Agent (reports to Sales Manager)

## Approval Process Configuration
- **Field Used for Routing**: None (using role hierarchy)
- **Record Editability**: Administrators OR current approver can edit
- **Approver Selection**: Automatically assign to Sales Manager from role hierarchy

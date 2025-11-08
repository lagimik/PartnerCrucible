```mermaid
flowchart TD


Start --- A1{**1. Identify _Scope_**}
    A1 --> A1a[Subscriptions]
    A1 --> A1b[Resource Groups]
    A1 --> A1c[Resources]
A1a --> D
A1b --> D
A1c --> D
click A1 "https://www.github.com" _blank

D{**2. Identify or create _Identity_ with _Owner_ or _Contributor_ RBAC role to scope**}
  D --> D1a[Your user account]
  D --> D1c[Customer user account
  on your behalf]
  D --> D1b[Service principal
  recommended for automation]

click D "https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/link-partner-id#get-access-from-your-customer
" _blank
  

 D --- D2>Group RBAC:
  If identity is in a group with RBAC,
  PAL recognition applies to users in that group]
   
  D1a --> E
  D1b --> E
  D1c --> E

  E{**3. Determine PAL _Association Method_**}
  E --> E1[Azure portal
  <quickest>]
  E --> E2[PowerShell
  <automatable>]
  E --> E3[Azure CLI
  <automatable, cross‑platform>]
  E --> E4[DevOps, CI-CD Pipeline
  recommended]

  click E1 "https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/link-partner-id#use-the-azure-portal-to-link-to-a-new-partner-id" _blank
  click E2 "https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/link-partner-id#use-powershell-to-link-to-a-new-partner-id" _blank
  click E3 "https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/link-partner-id#use-the-azure-cli-to-link-to-a-new-partner-id" _blank
  

 E4 --- S3>Best practice:
  Use dedicated service principals for CI/CD
  and long‑lived operations\]


  E1 --> I[Done: PAL active]
  E2 --> I[Done: PAL active]
  E3 --> I[Done: PAL active]
  E4 --> I[Done: PAL active]




  ```
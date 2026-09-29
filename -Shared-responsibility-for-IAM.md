# WHO OWNS IDENTITY? Shared Responsibility Model

| Layer | Microsoft (Cloud Provider) Owns | My Company (Customer / IAM Team) Owns |
|---|---|---|
| Physical building, power, internet | YES | NO |
| Entra ID servers are online | YES | NO |
| Creating / deleting users | NO | YES - This is IAM |
| Turning on MFA | NO | YES - This is IAM |
| Reviewing if old employees still have access | NO | YES - This is GRC |


In IAM/GRC, my work is 100% on the CUSTOMER side. Microsoft does not create users for us. If we forget to delete an ex-employee, it is OUR breach, not Microsoft's. This is why GRC audit exists.

# What is MTTR?
 MTTR = Average time taken to fix a problem and restore system 
 
 MTTR = Total downtime / Number of incidents

 ## Flow Diagram
 System Running]
 
        ↓
   ❌ Failure
   
        ↓
   🔔 Alert Trigger
   
        ↓
   👨‍💻 Investigation
   
        ↓
   🛠️ Fix Applied
   
        ↓
   ✅ Service Restored
   
        ↓
   📊 Calculate MTTR

   ### Example:
Incident 1: 20 mins

Incident 2: 40 mins

Incident 3: 30 mins

MTTR = (20 + 40 + 30) / 3 = 30 mins






# Interview

"MTTR measures how quickly we recover when something breaks in production. Earlier, teams didn’t track recovery time, so outages could last hours without clear visibility. MTTR helps measure and improve how quickly we fix issues. In DevOps, this is very important because faster recovery means less downtime, better user experience, and reduced business loss. For example, if a server crashes and we recover it in 5 minutes instead of 1 hour, our MTTR improves significantly. So overall, it’s a key metric for system reliability and operational efficiency."
   

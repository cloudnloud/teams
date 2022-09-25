# Cloud dataprotection and storage 

## Storage 
- AWS/Azure/GCP/On-premise storage
- Iternity storage
- AWS FSx file system
  - FSx for Netapp
  - FSx for OpenZFS
  - FSx for Windows file server
  - FSx for Lustre
- AWS S3 
- AWS EBS
- AWS gateway

## Data protection
- AWS/Azure/GCP/Data protection 
- AWS backup
  - Cloud native backup 
  - Hybrid data protection
- AWS Market place thirdparty dataprotection
  - Commvault
  - Netbackup
  
## Data migration 
- Double take migration 
- Storage X file migration
- Komprise file migration
- AWS snowball
- AWS Snowmobile
- AWS Kinesis Firehose
- AWS Migration Hub


# Architecture Review Template - Topics
- 𝟏: Problem Statement
-- Data  on premise and cloud
- 2: Business case
-- Cost
-- Management
-- Compliance 
-- Security   
- 3: Current System architecture
-- Onpremise data archival 
-- Vendor dependency
- 4: Proposed solution
      - Archival on cloud 
- 5: In Proposed solution – What are the new Services and Why those Services ? [List each service and what is the purpose ?]
      - API based AMAZON S3
      - Deep glacier for archival data       
- 6: Proposed Architecture
      - AWS gateway 
      - Backup software
- 7: Advantages of Proposed architecture
- 7.1 - Non Funtional Requirements
- 8: Conclusion
- 9: Q&A

# Asset Security

## INFO
Each heading below represents an exam topic. For each exam topic, I have added my notes for that topic. This is not an exhaustive list, this cannot be used as the only source of information. Please ensure that you seek information from many sources and be sure to fact check.

## Identify and classify information and assets
- Data classification
- Asset Classification

### Notes
Need to look at the **value of the asset** to the organisation and potential value to an adversary.  

Data Classification can be used with sensitivity labels to ensure the appropriate handling of the data takes place.

Classification and value can change over time.

## Determine and maintain information and asset ownership

### Notes
Determining **asset ownership** is discovered through the data and asset classification process.  

You then need to maintain the tracking of asset owners through the lifecylce of the assets.

## Protect privacy
- Data owners
- Data processers
- Data remanence
- Collection limitation

### Notes
**Data Anonymisation**. Protect privacy via aggregating non-unique data, throwing away PII where possible.  



## Ensure appropriate asset retention

### Notes
This is a combination of both the types of data that need to be retained *and* for how long the data needs to be retained. There are some circumstances where data does not need to be stored, simply used as a part of a process then destructed. There also may be a need to store personally identifiable information for a long period of time. 

## Determine data security controls
- Understand data states
- Scoping and tailoring
- Standards selection
- Data protection methods

### Notes

Data can be **at rest** - long term, or short term storage. Cached in memory or stored on disk, tapes, etc.  

Data can be **in transit** - travelling from one place to another. From CPU to RAM, CPU to HDD, Client PC to Server, Server to Server etc.  

Various methods including encryption can help protect the confidentiality of data at rest (encryption, full-disk encryption) and in transit (TLS, SSL).

You need to find the most appropriate protections based on the state of the data, the legal or regulatory requirements or business policies.  

Strong authentication and authorisation management.  
Data loss prevention systems

Obfuscation/Masking data - replace data with stars or hashes etc.

Tokenisation of data. Don't provide the data, but a verifiable representation of the data or a link to the data in a more tightly controlled environment.

Data can also be protected using System hardening and baselining
  - reduce attack surface (hardware and software)
  - implement secure baselines e.g. CIS Framework
  - remove unused services
  - make sure patching is up to date
  - ensure system firewalls/HIDS/HIPS are installed and enabled
  - do not use default accounts

Don't forget about the cloud; You still have a responsibility to ensure the confidentiality of your data!

Data Rights Management or Information Rights Management.

## Establish information and asset handling requirements

### Notes

Redundacy and retention of data.  

What are the retention policies? (how long do we need to keep the data for?)  

How often do we need to run backups? How long to we need to keep the data that we have backed up?  

Ensure that there is security to protect the backed up data.  

Regular testing of the backup and restoration procedures.  

Ensure you have a way to run eDiscovery over the data.  

Securely disposing of data. Storage medium re-use without sanitisation can lead to data leakage.  

Ensure that retired equipment is disposed of with physical destruction of storage media.

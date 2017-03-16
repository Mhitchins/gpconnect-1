---
title: Personal Demographic Service
keywords: spine, pds, integration, patient, demographics
tags: [integration]
sidebar: overview_sidebar
permalink: integration_personal_demographic_service.html
summary: "Overview of the role of the Personal Demographic Services (PDS) <br/>and the Spine Mini Services PDS (SMSP) within GP Connect."
---

## Personal Demographic Service (PDS) ##

GP Connect systems SHALL be capable of performing [Personal Demographic Service](https://digital.nhs.uk/Demographics){:target="_blank"} (PDS) tracing of patients to obtain their NHS Number, Date of Birth and current GP organisation.

GP Connect systems SHALL follow the guiding principles of [how systems should integrate with PDS](http://webarchive.nationalarchives.gov.uk/20160921135209/http://systems.digital.nhs.uk/demographics/spineconnect). This describes in particular the principles governing how systems should synchronise with PDS as the master repository of demographics data to ensure local system data does not become stale.

## Spine Mini Service PDS (SMSP) ##

GP Connect systems MAY utilise the [Spine Mini Service PDS](http://systems.digital.nhs.uk/ddc/spine-mini-service){:target="_blank"} (SMSP) as a lighter weight alternative to integrating with the full Spine Personal Demographic Service (PDS).


{% include important.html content="As the SMSP service does not return multiple possible matches for the patient it is typically only suitable to be used where there is enough information to achieve a single matched trace." %}


## Demographics Batch Service (DBS) ##

GP Connect systems MAY utilise the [Demographics Batch Service (DBS)](http://developer.nhs.uk/library/systems/demographic-batch-service-dbs/){:target="_blank"} to perform batch PDS Tracing.

The suitability of the use of DBS to perform batch PDS tracing would be assessed as part of the Consumer Accreditation process.
---
aliases:
- /blog/sqftrpt/
author:
  name: Glen C. Falk
date: "2016-07-01"
linktitle: sqftrpt
series:
- Hugo 101
tags:
- apache
- capstone
- github
- linux
- mit
- mysql
- php
- project
- tomcat
- uga
- watershed
title: UGA FMD Sq. Ft. Report
type:
- post
- posts
weight: 10
---

- Synopsis: 
  - Each year a [square footage report](https://glencfalk.rbind.io/UGaFMD_FI_SqFtRpt.pdf) is submitted to the Board of Regents Budget Office.
  - This is an opportunity for UGA to amend the reported square footage used for Resident Instruction, or RI.
  - This report is typically due at the end of June.

- Goal:
  - The goal is to find all added buildings (addition), omitted buildings (deletion), or differences in gross sq ft (either addition or deletion that will alter net RI space.
  - It also includes any new buildings that will come on line within the next two years.

- Data Sources:
  - FIDB: Compare the FRPT60A report with the current facilities data.
  - Lease Data:Compare the current list of leases obtained from the Real Properties Office with last year's lease data.
  - New Developments: (or information not yet forwarded to this office) Send an email to all UGA employees, i.e. “The Players” who may have further information on planned projects.

- Players:
  - FMD Executive Branch.
  - FMD Dept. Heads.
  - FMD Budget.
  - Office of Institutional Research.
  - Office of University Architects.
  - Real Estate and Space Mgt.
  - Board Of Regents.

- Workflow: The square footage report [workflow](https://glencfalk.rbind.io/UGaFMD_FI_SqFtWorkflow.pdf) is essentially a year round process. The bulk of the work is completed in the last quarter of the fiscal year.

Usage: The Board Of Regents uses the Square Footage Report to identify future funding requests to help formulate USG’s capital budgeting decisions.

## Built With:

- Database Engine: [AiM](https://www.assetworks.com/iwms/facility-management-software/)
- Repository Hosting Platform: GitHub
- Backend Integration: [AutoCAD](https://www.autodesk.com/products/autocad/overview)
- Application Server: Apache Tomcat
- Frontend Development: MS Access, MS Excel, VBA

## License

This website is licensed under the MIT License - see the [LICENSE.md](/LICENSE) file for details.

## Acknowledgments

- [*UGA Facilities Management*](https://www.fmd.uga.edu/)

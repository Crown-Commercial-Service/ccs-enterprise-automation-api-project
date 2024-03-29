# CCS Enterprise Automation - API Project Template
_Codeless solution is the next generation in test automation. CCS test automation reaches next wave of automation with this! And we bridge skill gap between resources or teams, anyone can automate tests now_

This is the CCS Test Automation Solution for automating API tests without writing single line of code, ie, no coding for api automation. We "democratizes" what used to be only for tester with strong programming skills to make it available for everyone.This solution supports test case modelling in json format. We aim to achieve accelerated test automation and zero dependency on programming skills.

**To learn/understand the solution and how to use it, please refer detailed user guide here:** [Documentation](https://github.com/Crown-Commercial-Service/ccs-enterprise-automation-api-project/wiki)

Guiding Principles for Test Automation Solution Usage:
1. The end users must use this CCS project template for test automation. 
2. The master code repository should not be referenced in other frameworks.
3. The end users (testers) should not make any modifications/enhancements at Project level. All such new entries will be ignored by CCS master. All changes / enhancements should be made via CCS master. E.g. : If we need to ‘add a new feature to enable test case modelling in yaml file format’, that should be done in master. Admins will deploy updated master artifact to Nexus and notify all teams about new version with release notes. Teams can update version of master dependency at project level and new changes will get reflected.
4. If a team needs an additional feature, they can send suggestion to admins : <email>
5. The CCS Master will have 3 administrators, and any changes need to be reviewed/approved by at least 2 Admins

![image](https://user-images.githubusercontent.com/89130649/152338982-b8972f59-4edd-4b0b-83eb-679274869872.png)

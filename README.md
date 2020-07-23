# DevNet Security Dev Center Update [please replace this readme before publishing]

## INTRODUCTION
Activities requested from volunteers: 
* Writing of learning lab (101, 102) and/or updating older content
* Adding code to Code Exchange (from labs, but maybe also extra use case)
* Presenting or creating webinar/slide-deck
* Writing blogpost on new features/API's on topic. This needs to be done 2 weeks in advance of the Webinar!
* Optionally you can also create a Workflow for SecureX Orchestrator (also add the JSON export to Code Exchange).

## SCHEDULE 

Q1:

1. Week of 31st of August – API Overview Webinar [Oxana]
2. Week of 21st of September – ASA/FMC/FTD/CDO [Patrick, Sudhir, Veer, Freddy and Jared]
3. Week of 5th of October – Stealthwatch [Kyle, Ed, Christopher]
4. Week of 26th of October – App First Security [Randy, Ed, Eddie, Gyorgy]

Q2:

5. TBA - AMP + Threat Grid [Oxana, Shaun, Vasily]
6. TBA – Umbrella + Cloudlock [Yaron, Gyorgy, Christopher]
7. TBA – ISE [Eddie, Gabriel, Hakan]
8. TBA/Q3 – Content Security [Ismeet, Rovert, Shaun] 
9. TBA/Q3 – Other (Open Source, Cognitive, PSIRT, Cyber Vision)

## LEARNING LAB STRUCTURE: 
* Format for learning labs: https://github.com/CiscoDevNet/devnet-writing-guidelines/ 
* Learning lab structure: 
    * Tracks > Modules > Labs 
    * 1 module per technology 
    * 2-5 labs per module, minimal recommendation: 
    * Introduction to API’s:
        * Overview API’s
        * Documentation 
        * Authentication 
        * API call constructions 
        * Basic GET call 
    * Hands-on (postman and/or python) 101 
        * Learning Objectives 
        * Exercises Overview 
        * Lab Steps 1-X 
        * Brief Summary
    * Hands-on (postman and/or python) 102 
        * Learning Objectives 
        * Exercises Overview 
        * Lab Steps 1-X 
        * Brief Summary 

## CODE EXCHANGE SUBMISSION  
Sample python code [NOTE: make sure to adhere to PEP 8: https://www.python.org/dev/peps/pep-0008/]:  
* Python example: https://github.com/CiscoSE/cisco-sample-code/tree/master/examples/python 

Template for GitHub Repo: 
* Automatic Cookiecutter Template: https://github.com/CiscoDevNet/code-exchange-repo-template 
* Manual: https://github.com/CiscoDevNet/code-exchange-repo-template/tree/master/manual-sample-repo 

Sample code license:  
* GitHub: https://github.com/CiscoSE/cisco-sample-code/tree/master/cisco-sample-code-license/v1.1 
* Text: https://developer.cisco.com/site/license/cisco-sample-code-license/ 

## WEBINAR PPT  [NOTE: make sure info is Cisco Public, slides will be shared in PDF] 
Template PPT: 
* Use PPT CX dark template: https://salesconnect.cisco.com/open.html?c=2b60fd05-90ff-4cbb-99ff-7971ca29f405 
* CX light template: https://salesconnect.cisco.com/open.html?c=73bc3a15-05ed-4531-a722-b172a7fe5073 

Structure PPT: 
* Overview slide webinar series with dates  
* Agenda slide 
* Intro to technology (e.g. Umbrella) 
* Overview API’s 
* Deep dive on specific API (based on new learning lab content, e.g. Umbrella Reporting API) 
* Cool use case with the API (e.g. pulling events from Umbrella into Threat Response via reporting API, or SIEM/SOAR etc.) 
* Demo of new script (based on code exchange submission, e.g. retrieve security events past 24 hours) 
* Conclusion and closing with links to: 
    * Learning labs
    * Blog posts
    * Code exchange submission
    * Dev Center microsite

## BLOG POST STRUCTURE: 
* Short intro the blog/webinar series (same for every blog post) 
* Brief intro to technology and API (e.g. Umbrella) 
* Discuss cool use case for a specific API (e.g. Umbrella Reporting API with Splunk)
* Links to: learning lab, blog, code exchange submission, dev center microsite 

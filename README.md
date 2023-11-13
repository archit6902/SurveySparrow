
REACT.JS WEB APPLICATION BY ARCHIT S.
DEVELOPER EMAIL: archit69.appdeveloper@gmail.com.
GOOGLE FORMS MIGRATION TO SURVEY SPARROW FORM USING SURVEY SPARROW DEVELOPMENT KIT (SSDK).
LAST EDITED ON 13-11-2023 AT 11:30 PM IST.

This web application built using React.JS, is intended to migrate Google Forms to SurveySparrow Surveys
with the help of SurveySparrow Development Kit (SSDK).
SSDK is a Command Line Interface (CLI) used to create, configure and run web applications specific
to SurveySparrow Domain from the Terminal of React.JS Project.


Google Forms Migration To SurveySparrow - HOW TO USE?
    1.  The user will be prompted to Sign In with their Google Account.
    2.  Upon signing in, the user has to type the "GOOGLE FORM ID" of 
        the Google Form he/she "has access" to and wants to migrate to SurveySparrow.
    3.  If the typed Google Form ID is valid, the questions will be displayed on the web page.
    4.  Then the user can select questions which he/she wants to include in the new SurveySparrow Survey.
    5.  The questions which are selected will be analysed for the presence of any toxic content.
    6.  The presence of toxic content is detected using "Perspective API".
    7.  If a question has any toxic content, then that question cannot be included.
    8.  After selecting the necessary questions, the user can create the SurveySparrow Survey.


Google Forms Migration To SurveySparrow - PREREQUISITES?
    1.  The developer who is willing to integrate this web application, should create a new project in
        Google Cloud Platform (GCP) and create a OAuth Client ID.
        Reference: https://support.google.com/cloud/answer/6158849?hl=en.
    2.  For the created project, the developer should also create an API Key from the GCP Console.
    3.  The developer should create a SurveySparrow Account and save the Access Token.
    4.  The developer should follow the basic steps mentioned in the SurveySparrow website
        to create a React.JS Web Application Template using SurveySparrow Development Kit (SSDK).
        References:
        https://codelabs.surveysparrow.com/codelabs/level-1-simple-app/index.html?index=..%2F..index#0
        https://codelabs.surveysparrow.com/codelabs/level-3-react-app/index.html?index=..%2F..index#0
    5.  The developer should create a new "Perspective API Key" by following the steps described 
        on the Perspective API Website.
        Reference: https://support.perspectiveapi.com/s/docs-enable-the-api?language=en_US 


Google Forms Migration To SurveySparrow - HOW IT WORKS?
    1.  The user will be prompted to Sign In with their Google Account.
    2.  Upon signing in, the user has to type the "GOOGLE FORM ID" of 
        the Google Form he/she "has access" to and wants to migrate to SurveySparrow.
    3.  If the typed Google Form ID is valid, the questions will be displayed on the web page.
    4.  The Google Form data is fetched using "Google Forms API" by passing the "GOOGLE FORM ID" as
        an a parameter along with the headers containing authorization token, using GET METHOD.
    5.  The fetched data will be parsed and displayed on the screen, along with 
        "Form Title", "Form Description", so that the users can select questions which they want 
        to include in their new SurveySparrow Survey.
    6.  Then the user can select questions which he/she wants to include in the new SurveySparrow Survey.
    7.  The questions which are selected will be analysed for the presence of any toxic content.
    8.  The presence of toxic content is detected using "Perspective API".
    9.  If a question has any toxic content, then that question cannot be included.
    10. After selecting the necessary questions, the user can create the SurveySparrow Survey.
    11. SurveySparrow APIs are used to create surveys and questions for each survey.
    12. This web application is restricted to creating SurveySparrow Survey using API due 
        to certain technical difficulties in the SurveySparrow API.

DEVELOPER DETAILS:
    NAME:                   ARCHIT S.
    EMAIL:                  archit69.appdeveloper@gmail.com
    COLLEGE:                B.S. ABDUR RAHMAN CRESCENT UNIVERSITY
    COLLEGE EMAIL ID:       200171601009@crescent.education
    COLLEGE REGISTER NO.:   200171601009
    PROJECT SOURCE CODE:    https://bit.ly/google_forms_migration_to_surveysparrow_by_archit_project_files
    LINKEDIN PROFILE:       www.linkedin.com/in/archit6902

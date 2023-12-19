# <span style="text-decoration:underline;">Getting Started - Authorization to Access Data</span>

#### This guide is for the authorization process to use the Jupyter Notebook, which is needed to access the cognitive assessment data. It outlines the steps that need to be completed by each team member who plans to pull this data. Before following this guide, you should have your cognitive assessments 'plugged in' into your chosen platform and test that these display properly. 

**If you are an external collaborator outside of PSU and you have yet to contact us, please reach out to us immediately at m2c2@psu.edu and do not proceed.**  

* Go to this URL: [https://prod.m2c2kit.com/docs#/authentication/sign_up_auth_register_post](https://prod.m2c2kit.com/docs#/authentication/sign_up_auth_register_post)  

* Click ‘Try it out’  

* Fill out the fields: <br>
   email <br>
   phone_number <br>
   first_name <br>
   last_name <br>
   affiliation <br>
   username <br>
   password <br> <br>
   (Leave grant_type, scope, client_id, and client_secret blank)


![Click ‘Try it out’](authorize_register1.png "Click ‘Try it out’")

![Click ‘Try it out’](authorize_register_userpass.png "Click 'Try it out'")

* Select 'Execute' (big blue button). 

![Select 'Execute' (big blue button).](authorize_register_button.png "Select 'Execute' (big blue button).")

* If successful, you will see 'Responses' below the blue 'Execute' button (see screenshot below). 

![If successful, you will see 'Responses' below the blue 'Execute' button (see screenshot below).](authorize_register_successful.png "If successful, you will see 'Responses' below the blue 'Execute' button (see screenshot below).")

* Contact our team to add the study name to our system by filling out this study form: **[Authorization Study Creation Request Form](https://airtable.com/app0JQhjqc5VNZMpZ/shrAqgkD5GD3hHOKI)**  **IMPORTANT:** This form only has to be completed *ONCE* for your study. Skip this step and the next step if a team member has already completed this form.

* Wait for us to confirm that the study has been successfully created. We will send you an email confirming this. (Again, skip this step if a team member has already completed the above form)

**CHECK THAT YOU HAVE BEEN ADDED TO YOUR STUDY**
* Once you have been confirmed to have been authorized and the study has been added, click ‘Authorize’ located at the very top of the form (https://prod.m2c2kit.com/docs#/) and input your username and password.  

![Once you have been confirmed to have been authorized and the study has been added, click ‘Authorize’ located at the very top of the form and input your username and password.](authorize_register2.png "Once you have been confirmed to have been authorized and the study has been added, click ‘Authorize’ located at the very top of the form and input your username and password.")

![Once you have been confirmed to have been authorized and the study has been added, click ‘Authorize’ located at the very top of the form and input your username and password.](authorize_register3.png "Once you have been confirmed to have been authorized and the study has been added, click ‘Authorize’ located at the very top of the form and input your username and password.")

* Once this is confirmed, close this pop-up window.  

* Next, go to whoami endpoint (located under authentication) and expand the window by hitting the down arrow. This will expose more content.
   
* Click on ‘try it out’ in the top-right-hand corner.



![Click on ‘try it out’ in the top-right-hand corner.](authorize_register4.png "Click on ‘try it out’ in the top-right-hand corner.")



* Then, select ‘Execute’. 




![Then, select ‘Execute’.](authorize_register5.png "Then, select ‘Execute’.")




* Your information will be displayed below (see example)


![Your information will be displayed below (see example)](authorize_register6.png "Your information will be displayed below (see example)")

* Next, fill out our Airtable form to capture details about who should be allowed to pull data: **[Usernames for Data Access Form](https://airtable.com/app0JQhjqc5VNZMpZ/shr2FrUEAeaZV7RzF)**.
* Once you receive your study ID and API key, use the url generator to put produce links and insert into your survey platform: [**Link Generator**](https://prod.m2c2kit.com/link-generator). 
* You are now ready to use the Jupyter Notebook:  \
 \
[https://github.com/m2c2-project/m2c2kit-integration-guides/blob/main/jupyter_notebooks/M2C2Kit_Data_Query_Notebook.ipynb](https://github.com/m2c2-project/m2c2kit-integration-guides/blob/main/jupyter_notebooks/M2C2Kit_Data_Query_Notebook.ipynb)  

    * Follow the guide and download the Jupyter Notebook from the GitHub repo to use on your device.  

Questions? Please submit the **[Question Form](https://airtable.com/app0JQhjqc5VNZMpZ/shrFeHYs7coh4FEni)**. Although the Question Form is the fastest way to alert us, you may also reach us at m2c2@psu.edu. 

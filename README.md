# ServiceNow-Update-incident-Management

Modify the Incident form so that it can support a new process for troubleshooting 
technical issues reported by Strawberry sFone users. To enable this, you will need to create a new 
field, configure the default view of the Incident form, and add a new choice (sFone) to the 
Category field.

1. Create a new field and add it to the Default view of the Incident form.
2.  Navigate to All > Incident > Create New.

<img width="726" height="349" alt="image" src="https://github.com/user-attachments/assets/73e8f342-1531-4969-981d-06580537e4f1" />


3. Select the Additional Options Menu, then select Configure > Form Layout.

<img width="757" height="407" alt="image" src="https://github.com/user-attachments/assets/801a0b8d-5671-4560-95f5-1e7d05d83c62" />









<img width="1621" height="776" alt="image" src="https://github.com/user-attachments/assets/bbca6ec0-ce38-49b4-b29b-602e2ba18b29" />

4. Ensure Default view is selected in the View name choice field under the Form view and 
section.

<img width="373" height="158" alt="image" src="https://github.com/user-attachments/assets/7dc27f05-4057-4766-bf3a-28c631b725e2" />

Under the Create new field section, populate the properties as follows:  

• Name: sFone Model 
• Type: String 
• Field length: Small (40) 

6. Select Add. 

<img width="394" height="184" alt="image" src="https://github.com/user-attachments/assets/f700342f-4ea3-40de-8631-20b1d98ac9f7" />

7. Move the sFone Model field up under Configuration item in the Selected column.
<img width="161" height="155" alt="image" src="https://github.com/user-attachments/assets/9f941904-ee75-4537-8885-61c50b5660ce" />

B. Add a Choice Field Option 

Add a new choice value to the Category field. 
1. From the Incident record, right-click on the Category field label. 
2. Select Configure Choices.

<img width="712" height="263" alt="image" src="https://github.com/user-attachments/assets/d1a7d9ff-6bd7-4663-916a-79fbfc7e4826" />

3. Type sFone into the Enter new item field.
 <img width="493" height="67" alt="image" src="https://github.com/user-attachments/assets/ede3a3ac-f882-45a4-9acd-9446b377c541" />

Select Add


Select Save to return to the incident record. Confirm the sFone choice appears last on 
the list for the Category field.
<img width="398" height="312" alt="Screenshot 2025-07-13 182953" src="https://github.com/user-attachments/assets/0c76424d-150c-46ff-9651-964a94de1dfc" />



Create a Non-P1 sFone Incident to put your form changes into action. 

1. Navigate to All > Incident > Create New. 
2. Populate the form with the following properties: 
• Caller: Megan Burke 
• Category: sFone 
• Short Description: My sFone will not turn on. 
3. Select Submit.

<img width="1535" height="598" alt="image" src="https://github.com/user-attachments/assets/1a7544e2-4a8a-4ef6-8db6-f3fcf60526c5" />











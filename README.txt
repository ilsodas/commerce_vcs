Configuring the VCS (Virtual Card Services) module to work on your Commerce Kickstart website.

Step 01:
  - Log into your website (http://your-domain.com/user)

Step 02:
  - Go to http://your-domain.com/admin/modules (Site settings, Modules)

Step 03:
  - Find the VCS (Virtual Card Services) module. Enable the module and all corresponding modules.

Step 04:
  - Once the module has been enabled, you can go to http://your-domain.com/admin/commerce/config/payment-methods (Store settings, Payment methods).

Step 05:
  - Find the VCS (Virtual Card Services) method. Select the 'Edit' button.

Step 06:
  - Scroll down to find the "Actions" tab. There will be a line titled "Enable payment method: VCS" - select the 'Edit' button.

Step 07:
  - Now input your VCS Terminal ID as provided by VCS (usually a 4 digit ID: XXXX) - Get your ID here: http://website.vcs.co.za/customer-info/applications/

Step 08:
  - Select the 'Save' button. 
  - Note: make sure that the live option is selected for your customers to make payments.

Step 09:
  - Log into VCS Merchant back-office
  
Step 10:
  - Go to Merchant Administration
  
Step 11:
  - Go to "3. VCS Interfacing (page1)"
  
Step 12:
  - Add full "Approved page URL" and "Declined page URL" can be custom content nodes. Must include http or https
  
Step 13:
  - Go to "6. Callback Settings"
  
Step 14:
  - Add "Approved Callback URL" and "Declined Callback URL"  to be http:your-domain.com/commerce_vcs/itn/%commerce_payment_method_instance where %commerce_payment_method_instance = payment instance id default instance id = commerce_vcs|commerce_payment_commerce_vcs
  - EG: http://www.examle.com/commerce_vcs/itn/commerce_vcs|commerce_payment_commerce_vcs

Step 15:
  - Set "CallBack Method" to POST
    
**You have now successfully configured the VCS (Virtual Card Services) to work on your Commerce Kickstart website.**

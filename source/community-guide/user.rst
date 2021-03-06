.. _user-profile:

User Profile
============

.. figure:: ../includes/user.png
	:align: center
	:width: 30%
	:figclass: img-container-border


Find out how to sign-in using **EO-SSO**, access your **Cloud** account by providing a valid **certificate** and prove your identity, or even link your profile with your **Github** account.


Sign in
-------

Once registered on ESA EO Single Sign On (EOSSO), you can simply sign-in using the username and password provided by ESA and you will be automatically redirected to the platform homepage.
At the first access, you may be asked to check your inbox in order to confirm your address

.. figure:: ../includes/email_confirmation1.png
	:figclass: img-border
	:scale: 80%

If you never received the confirmation email, you can ask the system to send it again by clicking on the link **send again the confirmation email**:

.. figure:: ../includes/email_confirmation2.png
	:figclass: img-border
	:scale: 80%

After clicked the link received by email, you'll be able to see your profile page of the portal:

.. figure:: ../includes/email_confirmation3.png
	:figclass: img-border
	:scale: 80%


Edit your profile
-----------------

.. figure:: ../includes/user_profile.png
	:figclass: img-border
	:scale: 80%
	
Fill in your profile:

1. Edit information such as first and last names, email, ... (username can not be modified though).
2. Once you are done, just click on **Submit** to save your changes.

.. NOTE::
		Direct access to your EO-SSO account is provided by clicking on *EO-SSO account*.

.. req:: HEP-TS-DES-014
	:show:

	This section describes how a user can update profile information.

Change your password
--------------------

To change your EO-SSO password:

1. On your profile page, click on **EO-SSO account**.
2. On the EO-SSO account page, click on **Change user password**.
3. Write your old password, and your new password (twice).
4. Click on **Submit**.
5. Your password is updated.

.. NOTE::
		If your UMSSO password is different from the one recorded in your profile, a message will appear in your profile (see image below).
		*Terradue Support Team* needs to perform manual operations as the email is associated to the certificate and the cloud account.

.. figure:: ../includes/user_profile_email_change.png
	:figclass: img-border
	:scale: 80%

Link your account to the Terradue Cloud Platform
------------------------------------------------

To access the Cloud resources, you need to have an account on the Terradue Cloud Platform. From this page, you can check that you have a valid account, or create a new one.

Don't have a Terradue account ?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you don't have yet an account on the Terradue Cloud Platform

.. figure:: ../includes/user_profile_cloud_no.png
	:figclass: img-border img-max-width
	:scale: 80%

1. Click on the button "Create" 
2. Enter a password for the Terradue account (see below for password recommandations)
3. A new account will be created on https://www.terradue.com using your EO-SSO email/username

.. figure:: ../includes/t2_password_rules.png
	:figclass: img-border
	:scale: 80%

.. NOTE::
	If you want to create an account with a different username or email, you can do it directly at https://www.terradue.com/signup (but a least one of Username or email shall be the same as in EO-SSO).

Already have a Terradue account ?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you already have an account on the Terradue Cloud Platform, the portal will be able to detect it by itself and display the Opennebula Sunstone logo. 
If not the case, it means that you have a different username/email than on your EO-SSO profile. In this case, please contact us so we can manually link your accounts.

.. figure:: ../includes/user_profile_cloud.png
	:figclass: img-border img-max-width
	:scale: 80%

Link your Github account
------------------------

.. figure:: ../includes/user_github.png
	:figclass: img-border
	:scale: 70%

Link your Github account to your profile will allow you to use Github as Software repository for the developments on your Sandboxes. You can also release and share your code there.

..note:: Link your github account is not mandatory but highly recommanded.

To link your Github account:

1. Fill in your github name and validate by clicking on |user_github_edit.png|.
2. You should add your ssh public key to your github account. If you don't have a Terradue certificate, you will need to add it manually. Finally click on **Add your public key** and accept the request on your Github account.

.. |user_github_edit.png| image:: ../includes/user_github_edit.png

See your groups
---------------

To find out to which groups you belong, just go to the **Groups** tab on your profile page.
The groups in which you are a member are listed here.

.. req:: HEP-TS-DES-014
	:show:

	This section describes how a user can get analytics report on belongings groups.

See your usage
--------------

To find out how you are using the platform, just go to the **Usage** tab on your profile page.
You will see what is your level for each type of usage of the platform.

.. req:: HEP-TS-DES-014
	:show:

	This section describes how a user can get analytics report.

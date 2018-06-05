# Guide To CakePHP 

Find below few code snapets and useful links for cakePHP :



1- Select List Code For CakePhp 

echo $this->Form->input('gender', array(
    'options' => array('male' => 'Male', 'female' => 'Female'),
    'empty' => '(choose one)'
));

Note : Multiple options can be added 


2- Check Box Inside the Form 

echo $this->Form->input('usertype', array('type' => 'checkbox'));

Note : Add the check box For Term and Conditions 


3- Set The value of checkBox As 1 or 0 

echo $this->Form->checkbox('usertype', array(
   'value' => 'Y',
  'hiddenField' => 'N'
));


4- Ajax CakePhp Contact Form 

Link : https://github.com/ITHHKN/AjaxCakePHPContactForm.git


5- User Login Authentication System 

Link : http://miftyisbored.com/a-complete-login-and-authentication-application-tutorial-for-cakephp-2-3/

Note : User Login and Signup System with Source Code 


6-User Login And Athentication System

Link : http://www.webistrate.com/cakephp-login-system-using-the-authentication-component/
Note : User Login And Athenticaion System in Cakephp


7- User Login Athentication System with Email Activation System 
URL : http://my-cakephp.blogspot.com/2009/11/creating-complete-user-registration.html

Note: USer Login And Athentication System and Check Activation using Email address

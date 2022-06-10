<p align="center"><a href="https://v3.yo-coach.com/" target="_blank"><img src="https://v3.yo-coach.com/images/yocoach-logo.svg" width="400"></a></p>

<p align="center">**Version RV-3.0.0**</p>

## About YoCoach

Yo!Coach is a ready-made software to create a tutoring and consultation platform based on video conferencing functionality. The eLearning software is integrated with a suite of interactive features to enable smooth navigation and workflows for both learners and tutors. As a fully customizable solution, Yo!Coach can be deployed to cater to many common and vital functionalities in platforms like Verbling, Preply, Italki, and Cambly.

Yo!Coach powered online tutoring or consulting platforms incorporate a full-blown marketing module instrumental in gaining wider reach and business promotion.

## Features

|   Users Management |   1 to 1 Lessons |  Lessons Subscriptions |
| ------------ | ------------ | ------------ |
|   Users Management |   1 to 1 Lessons |  Lessons Subscriptions |
|   Group Classes | Class Packages  |  Sales Reports |
|CMS Management|Order Management|General Settings|
|Commission Management|PWA Support|YoCoach Wallet|
|Multilingual | Multicurrency|  Review/Ratings|
| Giftcards/Coupons|Multiple Payment Methods|SEO-Friendly|

## System Requirements

The following technical requirements are needed to set up Yo!Coach:

| SrNo | Software | Version | Help|
| ------------ | ------------ | ------------ | ------------ |
| 1 | Ubuntu x86, x86-64 | 20.04+  | [Ubuntu](https://ubuntu.com/)  |
| 2 | Web Servers | Apache 2.4.x | [Apache](https://httpd.apache.org/)  | 
| 3 | PHP Version | 7.4.x |  [PHP](https://www.php.net/) | 
| 4 | MySQL Version | 8.0+ | [MySQL](https://www.mysql.com/)  | 

### Required PHP Extentions

GD with Free Font support, Zlib with zip support, DOM, Mbstring should be enabled, Iconv function should be enabled, Fileinfo function should be enabled, Ioncube Loader
          i. Safe_mode off
          ii. Memory_limit 32M or more (Some pages with advanced feature may need upto 128M)

## Setup on AWS 

Yo!Coach can be set up with t2.medium, however, will require upgradation once the number of users begin to increase. Our general recommendation is t2.large instance type.
The configuration of various EC2 instances can be viewed at [AWS Instance Types](https://aws.amazon.com/ec2/instance-types/)

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 2000 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

[More Info Here](https://www.fatbit.com/faqs/content-7/what-are-the-technical-specifications-required-to-set-up-yocoach-427.html)


### Clients Feedback

- **[Z'era Labs](https://www.zeralabs.com.my/)**
- **[Adrosline](https://www.adrosonline.com/)**
- **[Instrumently](https://instrumently.co/)**
- **[Online Lessons](https://www.onlinelessons.ie/)**
- **[Ace My App](https://https://acemyapp.com//)**

## Installation Guide


## License

Copyright © 2022 Yo!Coach Developed by [FATbit Technologies](https://www.fatbit.com/).



## Change Log

### Release Number: RV-2.4.0
### Release Date: 2022-05-25

Updates:
    #93036 - Demo Set up for Marketing team
    #94505 - Client Feedback Finalized Points
    #94862 - Attachments in Messages
    #94961 - Unread Message Notifications
    #95064 - Website and Email Theme Management
    #91988 - Merge API for Mobile app

Fixes:
    #064489 - fix User Listing on Admin is Loading very slow
    #063976 - Theme inverse color
    #064522 - Removed restore header bar for app
    #064514 - Fixed Report issue
    #064515 - Fixed Lesson plan bug
    #064442 - saturday schduling issue
    #062321 - Optimize the query of teacher profile page.
    #062509 - Decrese Teacher profile loading time
    #062589 - Logo alt txt
    #062586 - Url rewrite for dashboard url
    #062577 - fixed full availbility mobile view
    #062553 - Removed overlay in profile photo
    #062572 - Add new extensions for photo id
    #062638 - Fixed group classes status not updating
    #062651 - Fixed blog post duplicate
    #062810 - Update teach lang search
    #063190 - Report issue payment
    #063120 - send email to admin when apply to teach
    #063093 - Get Timezone from client browser
    #063107 - Image manageable from admin
    #062810 - Make teach language search
    #063139 - Admin:Theme management: theme activated message is not correct.
    #063109 - Message Contact: file uploaded not coming at teacher/learner in messaging section. for initial conversation
    #063108 - Message section: No file 'size' to upload and 'extensions' given in message section when learner tries to contact teacher for first time.
    #063138 - Admin: group classes : filter issue
    #063137 - Teacher registration : Resume:Invalid file extension
    #063128 - Message section: No 'validation message' when file is uploaded above limit defined
    #063136 - File extension mention in message section is not mentioned in other upload areas. 
    #063294 - Meeting tool : link used no longer valid after reset and unschedule from admin 
    #063319 - Admin: CMS:Banner:Removal of Block Second after Hompage Slider as no significance Un-Assigned.
    #063321 - 'Find a teacher page' the rating of a teacher changes from 0 to 5 when user visits to teacher profile.
    #063365 - Group class: Add group class:Weekday titles are jumbling up in group classes calender.
    #063317 - On find a teacher page the rating of a teacher is not updating 
    #063315 - Drop Down list should be responsive when user click on other side of the footer.
    #063290 - Contact section: file is uploaded from choosen file and displayed at dashboard without filling message.
    #063330 - Attachments on the emails and on the dashboard is not downloading in Safari browser 
    #063426 - Message section : Invalid extension message not given with .xlsx extension
    #063421 - Message:contact: Uploaded file extension .gif and message not send 

-------------------------------------------------------------

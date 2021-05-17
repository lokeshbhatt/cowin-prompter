#
# cowin-prompter
## Introduction: In order to secure a vaccination slot, one need to locate an available slot first, which is a game of speed. cowin-prompter runs independently on you laptop, talks directly to cowin data source via REST APIs and alerts on finding slot matching your criteria [state/district/pincode, age, feetype]
### Developer: [Lokesh Bhatt (Technology Architect & Python Enthusiast) ](https://www.linkedin.com/in/lokesh-bhatt-796a2ab/)
### (C) Copyright 2021 Lokesh Bhatt
#### This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
## Special thanks for [Dr. Bharat Bhatt](https://www.linkedin.com/in/bharat-bhatt-33010748/) for his support & contributions.
# 
#
# Background  
- Covid vaccination is open to all eligible indians now
- Securing vaccination is 2 step process  
   - Step-1: Registering on cowin portal and securing a registration number, this can be completed without any surprise
   - Step-2: Securing an available slot for vaccination, this is where cowin-prompter improves success rate 
#
#
# Problem Description   
- Securing vaccination slot may take considerable amount of time because of quickly vanishing slots  
   - NOTE: While you reading this page, enormous efforts are made to ramp up slots availability. But current situation would persist for sometime
- Currently there are 2 options available to acertain slot availability,  
   - Option-1: cowin portal  
      - Need to manually keep refereshing
      - Takes time to alter choices, incase of multiple selection criteria [more than one pincode, district]
   - Option-2: Third party alert (app/sms/mail)
      - Additional & unavoidable hops inserted during routing of slots availability, i.e., delayed delivery
      - By the time you generate OTP to book slot, they are gone :(  
#
#
# Solution Overview
Early observing available slots is key to success and here comes cowin-prompter to your aid
- cowin-prompter runs on your laptop/PC and lets you continously pull slots avalability from cowin without any manual intervention
- Allows capability to define multiple selection criterias, i.e., more than one pincode & district
- Uses sounds to attracts your attention for matching hits to your selection selection criterias
#
#
# Pre-requisites
- Platform: x86
- OS: Windows10
- User Permission: To write/create files into current directory & use laptop speaker
- **NOTE:** Efforts are on for a platform agnostic version
#
#
# How to run
- [How to run cowin-prompter video](
#
#
# Downloads
 - [Pre compiled binary for x86-Win10 - cowin-prompter-0.1](https://github.com/lokeshbhatt/cowin-prompter/blob/main/cowin-prompter-0.1.exe)
 - [ cowin-prompter-0.1.py](To be uploaded shortly)
#
#
### Feedback / Query / Issues / Change requests
#### [Lokesh Bhatt](https://www.linkedin.com/in/lokesh-bhatt-796a2ab/) | cowinprompter@gmail.com

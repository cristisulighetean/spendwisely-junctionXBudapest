# Spend Wisely - JunctionX Budapest

In this JunctionX hackathon we tried to solve the 'Wise' challenge by implementing a "wise" budgeting mode for travelers who often go out.

When using the Spend Wise mode, you set a budget, timespan and we will help you with sticking to the budget by making you aware of the current spending throughout the day.

Final [Figma prototype](https://www.figma.com/proto/aMTnCvA6jXVJZUsvuZxKwW/Spend-Wisely?node-id=5%3A2&scaling=scale-down&page-id=0%3A1&starting-point-node-id=5%3A2)
 and [Demo video](https://youtu.be/6vJy6s0z-S4)

### Short description:

-   Wise helps you with the budgeting while going out

### Configure the mode:

-   Manual / Automatic mode

-   Limit average budget (1 night out)

-   Time of the night in which you mostly go out

-   Type of OVER BUDGET procedure

### Other settings:

-   Add it to the wise home screen

-   Add it to the phone home screen as widget

### Automatic mode: how does it work?

-   DETECTION:

-   Repeatedly expenses over "short" amount of time

-   Know the "label" of the place you are spending (detect if bar/club/...) 

-   Search label distinction to be sure entertainment (museums, cinema) NOT same as clubs

-   Information gathered by settings regarding time and days user normally goes out

-   Possibility of ML about user behaviour (that's a little bit of a stretch)

### Manual mode: how does it work?

-   Activation will be based on either hours or a switch

-   Common: budget setting

### Turn OFF the mode?

-   Turn off by at a specific time

-   User can select time

-   The default time will be 6AM

-   Turn off automatically after a specific time from the last purchase

-   Also can be selected by user

-   Recognizing sleep mode from other apps (samsung health)

-   Turn off button

### Notifications (what notifications should we show to the user):

-   Have a permanent notification when drunk mode is on 

-   Configurable in the settings

-   Notifications when 50%, 90% and OVER BUDGET

-   The % notifications should be able to be chosen from settings

### Managing OVER BUDGET (selectable in the configuration)

-   Freeze card → Descart

-   Let normal payments but verification required?

-   How can we make verification? Ask Wise guy

-   Is it possible to only allow payment after X requirement (aka after X verification)

-   Let normal payments but notification appear? → Main procedure

-   Easy implementation, just rely on notifications

-   State how much over budget are you currently in
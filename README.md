# ExSize - Rewards and Tasks System 🎮🎯🎉
Purpose and target group

ExSize is an application that motivates children to perform household chores through a gamification system based on tasks, rewards in the form of coins and VIP points, and avatar personalization.

#### Target group: 
Children: Perform tasks, earn coins and VIP points, personalize avatars. No specific age range - the application is to be universal.
Parents: Create and manage tasks for children, approve their completion, supervise children's accounts.

## Platform

The application consists of:
Website (responsive - desktop and mobile).
Mobile application (Android / iOS).
Data synchronization between platforms via backend required.

## Size Pass 🎟️

Description: Special pass that unlocks additional features, including the Achievements tab.
Price: $30 per season (2 months).
Free Size Pass: Can be obtained after a year of regular task completion - minimum 5 tasks per day for 365 days (continuity required).
Validity: 2 months (season). After expiration:
Users lose access to the Achievements tab unless they renew the Size Pass within 7 days of expiration.
No effect on coins or inventory.
Notes: The Ultra variant has been discontinued - there is only one type of Size Pass.

## Coins 💰

Rules for obtaining:
Coins are obtained for completing tasks and missions.
Parents set coin rewards for tasks (approve their completion).
Types of tasks and rewards:

Type of task Max. amount/day Reward in coins Reward in VIP points (for Size Pass)

Normal 30 0-100 💵 0-100 VIP

Hard 15 100-300 💵 100-300 VIP

Large 5 300-500 💵 300-350 VIP

Extreme 1 500-1000 💵 350-500 VIP

Event missions:

Examples: "Do 20 tasks today" - reward: 1000 coins.

Defined by the system author, available in specific seasons.

Storage: Coins do not reset to zero - they are stored indefinitely.

## Store 🎨

Variants:

General: Permanent offer of items.
Event: Time-limited items (available for 2 weeks during the season).

Items:

Avatars, avatar decorations, avatar frames (cosmetic only, no impact on functionality).

Number of copies:

0-100 coin items: 1000 pieces.

100+ coin items: 150 pieces.

Changing items: No additional fees for changing a purchased item.

## Achievements 🏅

Availability: Tab available only to Size Pass holders (locked without the pass).

Differences from missions: Long-term goals defined by the system author, randomly assigned to users.

Examples:

"Spend 10,000 coins in a week" - reward: 20,000 coins.

"Collect 500 coins".

Storage: Progress resets after 24 hours from assigning the achievement.

## Missions 📅

Categories:
Daily: Drawn every day, max 10 missions.
Weekly: Drawn every week, max 10 missions.
Annual: Drawn every year, max 10 missions.
Rewards:
Daily: 10-30 coins.
Weekly: 40-70 coins.
Annual: 70-1000 coins.
Refresh:
Cost: 100 coins to refresh a category.
Limits:
Daily: 2x/day.
Weekly: 2x/week.
Annual: 2x/year.

## Inventory and avatar customization

Inventory:
Stores all purchased items.
No limit on the number of items.
Personalization:
Change the appearance of your avatar (avatar, decorations, frames) - free of charge.

## User Interface (UI)

Dashboard (after logging in):
Tiles:
Size Pass (large tile).
Missions.
Achievements.
Tasks.
Friends.
Shop.
Top Menu:
Settings (including enabling/disabling notifications).
Switch between parent/child section.
Notifications.
Profile.
Link to creator's website (www).
Accounts:
Parents: Separate account with a panel for adding/managing tasks and assigning child accounts (search for a child account and tag it).
Children: Separate account with access to Dashboard and gamification features.
Responsiveness: The application works on desktops, tablets and phones.

## Technical requirements

Backend:
Required for data synchronization between the website and the mobile application.
Stored data:
User accounts (parents and children).
Coins and VIP points.
Tasks, missions, achievements.
Inventory and purchase history.
Suggested database: Firebase.
Login:
Via Google accounts (authorization via Firebase Authentication).
Task verification:
The child reports the completion of the task, the parent approves it from your account.

## Notifications

Functionality:
Task reminders.
Size Pass expiration information.
Settings: Enable/disable in Settings.

## Future features

Tile customization: Ability to change the layout of tiles in the Dashboard (planned for the future).

 ## License

The project is licensed under the MIT license (see LICENSE file).

## Contact

Email: crystalgamesstudio9@gmail.com

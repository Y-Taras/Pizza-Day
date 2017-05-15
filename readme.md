# Pizza-Day

----------

### App features:

 - sign in/sign up
 - Google authentication
 - create users Groups (so, you don’t need to search for your co workers over whole users list
in app). Only Group creator may invite or remove people. Group should have name,
image/logo, menu items that can be ordered in this group (made for simplicity, so we
avoiding creating of restaurant).
 - Menu item should contain it’s name and price. Any group participant can create menu
items or edit existing ones.
 - Group creator is able to add/remove free pizza coupons (each coupon works only for
specific pizza (menu item)
 - create new “Pizza day” Event. Event contains event date, event status
**(ordering/ordered/delivering/delivered)**, user’s Group (that takes part in Event). Also,
each user from the Group should confirm he is taking part in Event, so he can add order
items in this event.
 - After Event creating each group participant (user) may choose menu items he want to order
(+ specify count).
 - When all event participants confirmed their order event status is changing to ordered. So,
each user receives to his email list of items he ordered and total amount $ he should pay to
event creator.
 - Event creator receives same email as simple participants + event summary (list menu items
he should order in “Local Restaurant”). After ordering event creator is able to change event
status to delivering.
 - [OPTIONAL] Ability to add discount coupons for specific menu items.

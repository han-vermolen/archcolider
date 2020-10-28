# Business Drivers (BD)

_List of business goals for system’s creation or modification. Presented not in importance order_ (* are they drivers or goals? Going to assume goals.)

1. System supports and engages ocassional users to make a purchase to increase users base. Converting Ocassional users to Known users, and Known users to Subscribers.
2. System provides rich options for engaging known users and subscribers by different kinds of loyality programs. New options are easily added in order to increase user satisfaction and a chance of recomendation. 
3. System provides information about consumed meals and on-demand requests to support Ghost Kitchen management. 
4. System should be easy to use for inexperiencied users to increase user base. 
5. Sustainable usage of service. 
6. Involve other specialist in health area to increase userbase.
7. Grow the number of outlets to provide healthy meals to more potential customers.
8. Support multiple vendors.
9. Harvest data to provide personalized recommendations based on users health goals, purchase history, and item ratings.
10. Make health and wellness radically affordable and accessible.
11. Become the dominant meal provider for the customers in order to let them optimize the benefits of their health gains through our meals.
12. Provide coupon and pricing strategies to engage more potential customers.


# Significant Architectural Requirements (SAR)
List of architecture driving requirements (major functional, quality attribute, and life-cycle requirements)

| # | Significant Architectural Requitements | From BD | 
|----|----|----| 
| 1 | System support cash and electronical payments | 1 | 
| 2 | Plugable system of feedback, survey, review abilities | 1, 2 | 
| 3 | On-time reports about consumed meals from fridges. Brakedown by subscribers and ocassional buying | 3 | 
| 4 | Scheduling system for subscribers, to avoid repetetive operations of ordering | 1, 3, 4, 5 | 
| 5 | Ability to purchase without registering first | 1, 4, 5 | 
| 6 | Notification system to inform user about their orders | 1, 4, 5 | 
| 7 | Notifications about new loyality programs and coupons | 2, 5 | 
| 8 | Detailed break down of a meal by components in catalog | 1, 5, 6 | 
| 9 | Secure payments | 1, 5 | 
| 10 | Maximizing guarantee of a meal picking up by user | 1, 5 | 

# Detalization of SARs 

## 1. System support cash and electronical payments

1. Cash payments supported by _PoS Admin_ and dedicated application for _Ocassional users_ 
AG: 
2. Users can add diffent payments methods to the App.
3. New payment method is easy to add with a month for a new areas. 
4. User can spend virtual funds (coupons and discounts) for payments.

## 2. Plugable system of feedback, survey, review abilities 

1. System remind user to add a review for a meal if it wasn't done before. 
2. User can read reviews for any meal in the catalog.
3. User can easily provide feedback about any aspect of the service.
4. Reviews groupped and categorized for the Owner.
5. Support for in app and external surveys. 

## 3. On-time reports about consumed meals from fridges. Brakedown by subscribers and ocassional buying

1. Ghost kitchen can browse and query menu schedule of subscribers 
2. Ghost kitchen recieve report about consumed meals with possible breakdown by PoS
3. Ghost kitchen can filter between subscribed meals and ocassional buying (L.D)

## 4. Scheduling system for subscribers, to avoid repetetive operations of ordering 

1. Subscriber can form menu for a week, prepaid and set pickup time. 
2. Subscriber can browse created menu. 
3. Subscriber can cancel menu and get notification about it. 
4. Subscriber can reorde the same menu for a previous time period in one click. (Possibly subscriber can select from any previous pre-formed menus)
5. Subscriber can accept or reject recomended meals (L.D)

## 5. Ability to purchase without registering first 

1. _PoS admin_ impersonate system user and make an order from the smart-fridge in the local PoS 
2. Any user can make a purchase and use any payment method supported by PoS 
 
## 6. Notification system to inform user about their orders 

1. User get notification about any significant action that related to actual ordering: payment process (initializing and result), availability of food for pickup, canceling, out of stock situation. 
2. User can set prefered way of notification: in-app, push, sms, email. 

## 7. Notifications about new loyality programs and coupon 

1. Notification about non-ordering event should be managed separately. 
2. User can set prefered way of notification: in-app, push, sms, email. 
3. User have dedicated account with accomulated coupons and bonuses. 

## 8. Secure payments 


## 9. Maximizing guarantee of a meal picking up by user

1. User can use registered card(s) to authorize pickup process. 
2. Pregenerated codes for pickup allows impersonated meal collecting. 

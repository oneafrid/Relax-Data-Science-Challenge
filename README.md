# Relax-Data-Science-Challenge
The data is available as two attached CSV files:
takehome_user_engagement. csv
takehome_users . csv
The data has the following two tables:
1] A user table ( "takehome_users" ) with data on 12,000 users who signed up for the
product in the last two years. This table includes: </br>
● name: the user's name</br>
● object_id: the user's id</br>
● email: email address</br>
● creation_source: how their account was created. This takes on one
of 5 values:</br>
○ PERSONAL_PROJECTS: invited to join another user's
personal workspace</br>
○ GUEST_INVITE: invited to an organization as a guest
(limited permissions)</br>
○ ORG_INVITE: invited to an organization (as a full member)</br>
○ SIGNUP: signed up via the website</br>
○ SIGNUP_GOOGLE_AUTH: signed up using Google</br>
Authentication (using a Google email account for their login
id)</br>
● creation_time: when they created their account</br>
● last_session_creation_time: unix timestamp of last login</br>
● opted_in_to_mailing_list: whether they have opted into receiving
marketing emails</br>
● enabled_for_marketing_drip: whether they are on the regular
marketing email drip</br>
● org_id: the organization (group of users) they belong to</br>
● invited_by_user_id: which user invited them to join (if applicable).</br>
2] A usage summary table ( "takehome_user_engagement" ) that has a row for each day
that a user logged into the product.</br>
Defining an "adopted user" as a user who has logged into the product on three separate
days in at least one sevenday
period , identify which factors predict future user
adoption .
We suggest spending 12
hours on this, but you're welcome to spend more or less.
Please send us a brief writeup of your findings (the more concise, the better no
more
than one page), along with any summary tables, graphs, code, or queries that can help
us understand your approach. Please note any factors you considered or investigation
you did, even if they did not pan out. Feel free to identify any further research or data
you think would be valuable.

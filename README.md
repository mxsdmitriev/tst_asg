# Description

The system implements a set of services for the clients of service providers. Each provider has its own set of users while each user can have just one provider. The set of permissions and available functions may vary by provider.

## Account types

There are several user account types which have different capabilities, see the table below. A user who ran out of their limits (per day or per 20 days) becomes the `idle` status until new time period comes or the account is upgraded.

|Account type|Session duration|Actions per day|Actions per 20 days|
|--|--|--|--|
|Guest|20 min|5|7|
|Basic|20 min|20|50|
|Advanced|Unlimited|Unlimited|Unlimited|
|Company|Unlimited|Unlimited|Unlimited|

## Account upgrade

User accounts can be upgraded and downgraded, see figure below. Note that upgrading from `guest` to `basic` requires a KYC (Know Your Client) authentication.

![Accounts upgrade scheme](http://www.plantuml.com/plantuml/png/FOt1YiCW48RlynG3Urlm1PPboJQ77le4fVGmrKaY62rcRF7j6r5pzFk_-HmseIXfTU1u4fI0qSwBeB6HjTZW0NP36C-9Dm6uVTzHgR_wn2zNv3bIXkwTQBEw3PcT2s-0AfUpklxWvJeY9LdOYvsiflfJzNwLgbvF_fiNUSscLNMctQsbqknpG-MyeruOm_eadrlWuH83TASqkd30KZaW3EnDMjq7 "Account type upgrades")



# AfroFarm


AfroFarm is a system inspired by the market gap due to the lack of a system linking real small 
farmers/global market and investors to help small farmers with their actual weather data 
according to their locations and links them to the global market to achieve perfect productivity 
and rewarding returns.


**Currently included functionalities for the managers**
```

- [x] Payments Management
- [x] Adding orders
- [x] Building updates
- [x] Add to cart
- [x] Hired Personnel Management
- [x] Work Order Management
- [x] Reports, complaints and Maintenance Management
- [X] Visits Scheduling and Management 
- [X] Email Communications and Notifications Management
- [x] Eviction Management
- [x] Managing Move Out Notices
```
**Currently included tenants' functionalities**
```

- [ ] Online payments
- [x] View payments history
- [x] View receieved notices & create moveout notice
- [x] View and send tenancy related emails using the platform
- [x] Make Complaints
- [x] Create reports
```
**Shared Funtionalities**
```
- [x] Account Management
    - SignUp & login, password change/reset, email confiration, profile update
- [x] Contact
- [x] Scheduling visits
- [x] Searching
```

## Modules


- [Accounts](https://github.com/MoAfifi0/AfroFarm/tree/main/accounts)
    - User
    - Profiles

- [Pages](https://github.com/MoAfifi0/AfroFarm/tree/main/pages)
    - About
    - Contactt
    - AfroFarm

[Requirements](https://github.com/MoAfifi0/AfroFarm/tree/main/requirements.txt )

# Running the project

### .env variables is needed
~~~
DJANGO_SECRET_KEY = #random secret string
SENDGRID_EMAIL_HOST_PASSWORD = # from your sendgrid account
CLOUDINARY_API_KEY=#from cloudinary account
CLOUDINARY_CLOUD_NAME=#from cloudinary account
CLOUDINARY_API_SECRET=#from cloudinary account
STRIPE_PUBLISHABLE_KEY=#from stripe account
STRIPE_SECRET_KEY=#from cloudinary account
~~~

- ```chmod +x run-project.sh```
- ```./run-project.sh``` and provide the env variables when prompted.
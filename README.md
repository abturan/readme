# YETTIM BUSINESS APP 
## ENDPOINT LISTS

**Login**

- `Login JWT Auth` <br/>https://restoranpanel.com/api/login

**Login Return Object**

  ```
{
    "code": 200,
    "message": null,
    "data": {
        "token": "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJodHRwOlwvXC90ZXN0LnJlc3RvcmFucGFuZWwuY29tXC9hcGlcL2xvZ2luIiwiaWF0IjoxNTc4NDg0MTA5LCJleHAiOjE1Nzg0ODc3MDksIm5iZiI6MTU3ODQ4NDEwOSwianRpIjoidFNidGNlZW1iREg1eDdoZSIsInN1YiI6MTE4MjUsInBydiI6Ijg3ZTBhZjFlZjlmZDE1ODEyZmRlYzk3MTUzYTE0ZTBiMDQ3NTQ2YWEifQ.RTU5G6WatcRJDUm4uSOJuYrfNbQfeS4Hbbtlt7mAV-4",
        "user": {
            "id": 11825,
            "invitation_code": "5dcdbe3f0096e",
            "user_group_id": 11,
            "user_group_permissions_id": null,
            "orders_number": 0,
            "name": "Test Super Admin",
            "gender": null,
            "mobile": "2321312453",
            "email": "testsuperadmin@yettim.net",
            "branch_web_push_id": null,
            "image": null,
            "status": 1,
            "confirmation_code": null,
            "confirmed": 0,
            "signup_newsletter": null,
            "birthday": null,
            "email_promotions_enabled": 1,
            "send_me_push_notifications": 1,
            "super_visor_ids": "[\"967\", \"953\", \"939\", \"844\", \"832\", \"764\", \"503\", \"35\"]",
            "created_at": "2019-10-30 16:18:50",
            "updated_at": "2019-11-14 23:51:11",
            "deleted_at": null,
            "referrer_id": null
        }
    }
}

  ```

**Orders**
- `New, Accepted, Prepared, Sent orders` <br/> https://restoranpanel.com/api/orders/todayOrders
- `Ignored and complated orders` <br/> https://restoranpanel.com/api/orders/oldOrders


- `Order details` <br/> https://restoranpanel.com/api/orders/order/{order_id}
- `Print the order details` <br/>https://restoranpanel.com/api/orders/print/{order_id}

- `Make the order Accepted` <br/> https://restoranpanel.com/api/orders/acceptOrder/{order_id}
- `Make the order Prepared` <br/> https://restoranpanel.com/api/orders/prepareOrder/{order_id}
- `Make the order Sent` <br/> https://restoranpanel.com/api/orders/sendOrder/{order_id}
- `Make the order Comleted` <br/> https://restoranpanel.com/api/orders/completeOrder/{order_id}
- `Make the order Cancel` <br/> https://restoranpanel.com/api/orders/cancel/{order_id}



**Index**

- `General Informations of User` <br/> https://restoranpanel.com/api

**Index Return Object**

```


{
    "announcement": [
        {
            "id": 1,
            "title": "Duyuru",
            "description": "Siparişlerde kullanılan 5TL indirim, firmamızca karşılanmaktadır. ",
            "color": "warning",
            "active": 1
        },
        {
            "id": 3,
            "title": "Duyuru",
            "description": "Teslim edilen siparişleri lütfen butonlara basarak sistemde tamamlamayı unutmayınız.",
            "color": "danger",
            "active": 1
        },
        {
            "id": 4,
            "title": "Duyuru",
            "description": "Değerli işletme sahipleri. Lütfen menü, teslimat bölgeleri ve fiyatları kontrol ederek güncel tutmamız yardımcı olun. Aksi halde müşterileriniz mağdur olmaktadır. 0850 255 0989",
            "color": "danger",
            "active": 1
        }
    ],
    "superOp": 3,
    "todayOrders": 2,
    "todayOrdersCash": 2,
    "todayOrdersCredit": 0,
    "monthOrders": 7,
    "restaurant_branch_settings": [
        {
            "id": 27,
            "active": 1,
            "fast": 0,
            "restaurant_id": 35,
            "restaurant_branch_id": 40,
            "show_time": 0,
            "min_order_delivery_purchase_amount": 45,
            "max_order_delivery_purchase_amount": null,
            "min_order_pickup_purchase_amount": 45,
            "max_order_pickup_purchase_amount": null,
            "tax": 18,
            "delivery_charges": null,
            "profit_charges": 0,
            "apply_tax_to_delivery_charges": 0,
            "delivery_estimate_time": 40,
            "monday_on": 1,
            "tuesday_on": 1,
            "wednesday_on": 1,
            "thursday_on": 1,
            "friday_on": 1,
            "saturday_on": 1,
            "sunday_on": 1,
            "monday_start_time_1": "11:00:00",
            "tuesday_start_time_1": "11:00:00",
            "wednesday_start_time_1": "11:00:00",
            "thursday_start_time_1": "11:00:00",
            "friday_start_time_1": "11:00:00",
            "saturday_start_time_1": "11:00:00",
            "sunday_start_time_1": "11:00:00",
            "monday_end_time_1": "22:00:00",
            "tuesday_end_time_1": "22:00:00",
            "wednesday_end_time_1": "22:00:00",
            "thursday_end_time_1": "22:00:00",
            "friday_end_time_1": "22:00:00",
            "saturday_end_time_1": "22:00:00",
            "sunday_end_time_1": "22:00:00",
            "accept_preorder": null,
            "close_message": null,
            "cancel_reason": null,
            "default_order_status": null,
            "created_at": "2018-11-30 11:36:47",
            "updated_at": "2019-11-03 17:22:10",
            "deleted_at": null,
            "mute_setting": 1
        } 
    ],
    "monthOrdersPrice": 95.51,
    "todayOrdersOnline": 0,

}


"SuperOp": {
        "superVisorBrances": [
            {
                "id": 943,
                "name": "Esenyurt (Cumhuriyet Mah.)",
                "slug": "kilisli-baklavaci-esenyurt-cumhuriyet-mah",
                "restaurant_id": 35,
                "user_id": 76,
                "city_id": 41152,
                "district_id": 1980,
                "branch_phone": "05459597979",
                "contact_name": null,
                "contact_email": "admin@yettim.net",
                "street_address": null,
                "detail": null,
                "postcode": null,
                "lat": "41.01325550",
                "lng": "28.65086580",
                "lang": null,
                "created_at": "2018-11-30 11:53:04",
                "updated_at": "2019-12-10 14:56:35",
                "deleted_at": null
            }, 
        ],
        "todayOrdersSuperOp": {
            "934": 0,
            "920": 0,
            "908": 0
           
        },
        "todayOrdersPriceSuperOp": {
            "934": 0,
            "920": 0,
            "908": 0
        },
        "weekOrdersSuperOp": {
            "934": 2,
            "920": 0,
            "908": 0,
            "817": 0
        },
        "weekOrdersPriceSuperOp": {
            "934": 24.509999999999998,
            "920": 0,
            "908": 0
        },
        "monthOrdersPriceSuperOp": {
            "934": 24.509999999999998,
            "920": 0,
            "908": 0,
        },
        "monthOrdersSuperOp": {
            "934": 2,
            "920": 0,
            "908": 0,
            "817": 0
        },
        "todayOrdersPrice": 40
    }
```

# USER STATUS'

- RESTAURANT_MAIN <br/> ``` superOp = 0 ```
- RESTAURANT_BRANCH` <br/>  ``` superOp = 1 ```
- SUPER_VISOR` <br/> ``` superOp = 3```


**RESTAURANT_MAIN**

If ```superOp == 0``` its mean that this account is an main restaurant account. So this account may be have more then one branches.In this case, restaurant may track all the branches and orders without do any interactivity like accept, cancel etc...

As an addition ```$data->SuperOp->superVisorBrances``` list should be listed. So account owner can see which branches s/he is tracking. ```$data->SuperOp->todayOrdersSuperOp```, ```$data->SuperOp->todayOrdersPriceSuperOp```, ```$data->SuperOp->weekOrdersSuperOp```, ```$data->SuperOp->weekOrdersPriceSuperOp```, ```$data->SuperOp->monthOrdersPriceSuperOp``` are represent the value's of branches. For example; 

``` 
"weekOrdersPriceSuperOp": {
            "934": 24.509999999999998,
            "920": 0,
            "908": 0
        }, 
``` 

That show up the 934 ID branche's weekly order price is 24.51. To catch the name of branch, you need the check the id in  the list of    ```$data->SuperOp->superVisorBrances```
        
 

and ```$data->SuperOp->todayOrdersPrice``` represent the value of total amount of the order's prices.

**RESTAURANT_BRANCH**


If ```superOp == 1``` its mean that this is just one branche control unit. So the account owner can accept, prepare, send, complate and cancel the orders and can show the notes and make print the order details. 

**SUPER_VISOR**

If ```superOp == 3``` its mean that the account is and super visor account and it may be include several restaurant and several branches. This account's behaviour is same with ```superOp == 0```



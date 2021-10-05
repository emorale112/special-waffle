# My-Article

The beginning of an awesome article...
![discord-avatar-512-42CAU.png](https://stoplight.io/api/v1/projects/cHJqOjY3NDU2/images/ndInAcLYkkg)

```json json_schema
{
    "api_response": "200",
    "total_result": 4,
    "next_page": 510603416,
    "data": [
        {
            "shipment_uuid": "1c64d067-7ff7-4f59-8790-39840d8ea6f8",
            "shipment_id": "c20210304001shipid",
            "tracking_number": "C20210304001TRACKNO",
            "carrier": "IO Test Express",
            "status": "return",
            "current_phase": {
                "name": "Others",
                "key": "X"
            },
            "created_date": "2021-03-04T06:51:37+00:00",
            "updated_date": "2021-03-04T06:51:41+00:00",
            "order": {
                "order_uuid": "a0144751-6530-4135-8d73-f258a28ba27d",
                "order_id": "c20210304001ordid"
            },
            "latest_event": {
                "event": "Shipment cancelled",
                "date_time": "2021-03-04T11:55:00+08:00",
                "timezone": "Etc/GMT-8",
                "location": {
                    "place": "Changi"
                }
            }
        },
        {
            "shipment_uuid": "ac465fe2-1af2-41f8-b316-6f87e7138a19",
            "shipment_id": "c20210304002shipid",
            "tracking_number": "C20210304002TRACKNO",
            "carrier": "IO Test Express",
            "status": "active",
            "current_phase": {
                "name": "Out for delivery",
                "key": "G"
            },
            "created_date": "2021-03-04T07:07:05+00:00",
            "updated_date": "2021-03-04T07:07:16+00:00",
            "order": {
                "order_uuid": "a8edced5-b841-4899-b0d4-87841640dc95",
                "order_id": "c20210304002ordid"
            },
            "latest_event": {
                "event": "Out for delivery",
                "date_time": "2021-03-04T11:10:00+08:00",
                "timezone": "Etc/GMT-8",
                "location": {
                    "place": "Changi"
                }
            }
        },
        {
            "shipment_uuid": "b6a7daff-4b4b-46cd-bb69-807ced5a3e80",
            "shipment_id": "c20210304003shipid",
            "tracking_number": "C20210304003TRACKNO",
            "carrier": "IO Test Express",
            "status": "active",
            "current_phase": {
                "name": "Out for delivery",
                "key": "G"
            },
            "created_date": "2021-03-04T07:10:32+00:00",
            "updated_date": "2021-03-04T07:10:36+00:00",
            "order": {
                "order_uuid": "4a5f1fc3-0c8d-42e9-aa78-30d41d8a6789",
                "order_id": "c20210304003ordid"
            },
            "latest_event": {
                "event": "Out for delivery",
                "date_time": "2021-03-04T11:10:00+08:00",
                "timezone": "Etc/GMT-8",
                "location": {
                    "place": "Changi"
                }
            }
        },
        {
            "shipment_uuid": "0520d8f3-27a4-4c19-ab1e-991a611aae06",
            "shipment_id": "c20210304004shipid",
            "tracking_number": "C20210304004TRACKNO",
            "carrier": "IO Test Express",
            "status": "active",
            "current_phase": {
                "name": "Out for delivery",
                "key": "G"
            },
            "created_date": "2021-03-04T07:16:35+00:00",
            "updated_date": "2021-03-04T07:16:40+00:00",
            "order": {
                "order_uuid": "fecf7f51-8f86-4b18-ae64-19adfaaa54c0",
                "order_id": "c20210304004ordid"
            },
            "latest_event": {
                "event": "Out for delivery",
                "date_time": "2021-03-04T11:10:00+08:00",
                "timezone": "Etc/GMT-8",
                "location": {
                    "place": "Changi"
                }
            }
        }
    ]
}
```

```json json_schema
{
  "type": "object",
  "properties": {
    "id": {
      "type": "string"
    }
  }
}
```
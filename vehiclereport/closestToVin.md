Description and examples for /v2/vehiclereport/closestToVin to follow...
Retrieve a list of vehicles closest to a designated Vehicle VIN within a given radius
  * Example:
    * http://api.gpsinsight.com/v2/vehiclereport/closesttovin?vin=X&group=X&radius=X&sort=X&attr_clause=X
  * Result:

    {
    head: { ... },
    data: [
        {   "vin": "1111111222222222",
            "vin2": "12345",
            "vehicle": "3900e",
            "vehicle_id": null,
            "trailer": 0,
            "is_asset": 0,
            "fname": null,
            "lname": null,
            "refid": null,
            "alert_pref": 0,
            "phone_number": null,
            "email_address": null,
            "date": "Jan 02, 2014",
            "time": "22:38",
            "ageMinutes": 88800,
            "fix_time_adj": "Jan  2 2014 10:38PM",
            "fix_time_utf": "Jan  2 2014 10:38PM",
            "latitude": 33.598,
            "longitude": -111.9925,
            "ignition": "off",
            "speed": "0",
            "speed_units": "MP",
            "speed_type": "Max",
            "heading": 348,
            "distance": 35950,
            "has_garmin": 1,
            "formattedDistance": "6.8 mi.",
            "formattedTime": "22:38 min",
            "formattedDriveDistance": "14.5 mi.",
            "formattedVehicle": "3900e"
        },
        { ... },
        { ... },
    ]}

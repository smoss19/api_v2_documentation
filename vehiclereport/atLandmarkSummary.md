Description and examples for /v2/vehiclereport/atLandmarkSummary to follow...
Get a vehicle count summary by landmarks  
  * Example:
    * http://api.gpsinsight.com/v2/vehiclereport/atlandmarksummary?group=X&landmark_group=X&rows=X&sort=X
  * Result:

    {
    head: { ... },
    data: [
        {   
            "landmark_id": 100147,
            "name": "ACME Regional Warehouse",
            "latitude": 29.9674388,
            "longitude": -95.517705,
            "number": 2
        },
        { ... },
        { ... },
    ]}


API link https://farmer-friend-v2.onrender.com/

#Request Body
{
    "year": 2025,
    "month": 3,
    "region": "Bilaspur Division",
    "temperature": 40,
    "rainfall": 87,
    "humidity": 10,
    "soil_pH": 5,
    "soil_nitrogen": 34,
    "soil_phosphorus": 34,
    "soil_potassium": 34,
    "soil_organic_matter": 5,
    "fertilizer_use": 34,
    "pesticide_use": 34,
    "previous_year_yield": 34,
    "sowing_to_harvest_days": 34,
    "farm_size_acres": 89,
    "irrigation_available": true,
    "supply_tons": [123, 340, 4500, 670, 7800, 405, 5600, 708, 9080, 506, 7080, 340, 95, 504, 7500, 460, 750, 4050, 807],     
    "soil_type": "Black soils",
    "crops": [
      "Wheat", "Rice", "Maize", "Soybean", "Niger", "Urd", "summer paddy", "Gram", "Tiwra",
      "Millets", "Arhar", "Mustard", "Jwar", "Moong", "Kulthi", "Groundnut", "Masoor", "Til", "Pea"
    ]
  }

  #Response Body
[
  {
    "crop": "Pea",
    "score": 0.5022897897897898
  },
  {
    "crop": "Masoor",
    "score": 0.46138752450130505
  },
  {
    "crop": "Groundnut",
    "score": 0.4249198712463461
  },
  {
    "crop": "Moong",
    "score": 0.3652797949168592
  },
  {
    "crop": "Jwar",
    "score": 0.34602646029005063
  },
  {
    "crop": "Mustard",
    "score": 0.2962954536757974
  },
  {
    "crop": "Millets",
    "score": 0.21332481600817849
  },
  {
    "crop": "Rice",
    "score": 0.18406400547864332
  },
  {
    "crop": "Wheat",
    "score": 0.14700534620564676
  },
  {
    "crop": "Gram",
    "score": 0.12136557713449428
  },
  {
    "crop": "Soybean",
    "score": 0.10800193349673015
  },
  {
    "crop": "Urd",
    "score": 0.008629075504075503
  }
]

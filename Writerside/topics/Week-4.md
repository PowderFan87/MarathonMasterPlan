# Week 4 (September 02 - September 08)
```json
{
  "week_number": "4",
  "date_range": "2024-09-02 to 2024-09-08",
  "runs": [
    {
      "date": "2024-09-02",
      "type_of_run": "Recovery",
      "distance_km": 5,
      "duration_hh_mm_ss": "00:40:00",
      "average_pace_min_per_km": "08:00",
      "average_heart_rate_bpm": "Low Zone 2",
      "notes": "Take this run very easy to recover from last week’s long run. Focus on a relaxed pace."
    },
    {
      "date": "2024-09-03",
      "type_of_run": "Easy",
      "distance_km": 8,
      "duration_hh_mm_ss": "01:00:00",
      "average_pace_min_per_km": "07:30 to 08:00",
      "average_heart_rate_bpm": "Mid Zone 2",
      "notes": "A moderate easy run. Keep the pace comfortable."
    },
    {
      "date": "2024-09-04",
      "type_of_run": "Interval",
      "distance_km": 6.5,
      "duration_hh_mm_ss": "00:45:00",
      "intervals": [
        {"duration": "400m", "pace": "5:20 to 5:30 min/km", "recovery": "200m walk/jog", "repeat": 8}
      ],
      "average_pace_min_per_km": "Varies",
      "average_heart_rate_bpm": "Varies",
      "notes": "Focus on speed during intervals. Recover fully between each repetition."
    },
    {
      "date": "2024-09-06",
      "type_of_run": "Tempo",
      "distance_km": 10,
      "duration_hh_mm_ss": "01:05:00",
      "average_pace_min_per_km": "06:20 to 06:40",
      "average_heart_rate_bpm": "Zone 3",
      "notes": "Run at a controlled, steady tempo pace. Should feel comfortably hard."
    },
    {
      "date": "2024-09-07",
      "type_of_run": "Easy",
      "distance_km": 6,
      "duration_hh_mm_ss": "00:45:00",
      "average_pace_min_per_km": "07:30 to 08:00",
      "average_heart_rate_bpm": "Zone 2",
      "notes": "A relaxed run to shake out any residual fatigue."
    },
    {
      "date": "2024-09-08",
      "type_of_run": "Long",
      "distance_km": 26,
      "duration_hh_mm_ss": "02:55:00",
      "average_pace_min_per_km": "07:20 to 07:40",
      "average_heart_rate_bpm": "Zone 2 to Low Zone 3",
      "notes": "Repeat the 26 km distance. Start earlier in the day if possible. Focus on staying hydrated and fueling as needed."
    }
  ]
}
```

## Results
```json
{
  "week_number": "XX",
  "date_range": "YYYY-MM-DD to YYYY-MM-DD",
  "runs": [
    {
      "date": "YYYY-MM-DD",
      "type_of_run": "Easy/Tempo/Interval/Long",
      "distance_km": X.X,
      "duration_hh_mm_ss": "HH:MM:SS",
      "average_pace_min_per_km": "MM:SS",
      "average_heart_rate_bpm": XX,
      "max_heart_rate_bpm": XX,
      "heart_rate_zones": {
        "zone_1_percentage": X,
        "zone_2_percentage": X,
        "zone_3_percentage": X,
        "zone_4_percentage": X,
        "zone_5_percentage": X
      },
      "perceived_effort_1_to_10": X,
      "weather_conditions": {
        "temperature_C": XX,
        "humidity_percentage": XX,
        "wind_speed_kph": XX
      },
      "additional_observations": "Any notable feelings, fatigue, pain, or exceptional performance details"
    }
  ]
}
```
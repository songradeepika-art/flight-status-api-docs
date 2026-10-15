# Flight-status response: practice example

This fictional example is a learning exercise. It does not represent a tested API.

## Example response

```json
{
  "flight_number": "AB123",
  "departure_date": "2026-10-15",
  "status": "delayed",
  "delay_minutes": 30
}
```

## Response fields

| Field | Description |
|---|---|
| `flight_number` | Flight number identifying the service. |
| `departure_date` | Scheduled departure date in `YYYY-MM-DD` format. |
| `status` | Current operational status of the flight. |
| `delay_minutes` | Departure delay in minutes relative to the scheduled departure time. A value of `null` indicates that the duration is unavailable. |

## Another status value

The `diverted` status indicates that the flight is being redirected or has been redirected to another airport.

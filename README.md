# RunningPlans

Strideplan is a lightweight, browser-based interface for creating and reviewing a running plan.

## Run locally

```bash
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080). No build step or external application dependencies are required.

## Included workflows

- **Weekly plan:** Review the seven-day training calendar with total distance, time, training load, and session count.
- **Editable sessions:** Add, update, or delete sessions with a title, interval/recovery details, kilometers, duration, and a 0–10 expected intensity.
- **Insights:** Explore weekly-distance and training-load trends alongside the current week's key metrics.
- **Plan builder:** Generate a draft plan summary from a race distance, goal time, race date, and experience level.

Session edits are saved in the browser's local storage, so a refresh retains the current plan on that device.

# Seasonality on Spotify
### Kwame V. Taylor

This project will explore the seasonality of music tracks on Spotify using time-series analysis.

---

> From a business / stakeholder perspective, what is the goal of this project? What hypotheses will you investigate? (It's okay if this is hypothetical at this point)

The goal is to predict how well a particular kind of song will do based on season, so that publishers can time the release of singles and albums to be during peak seasonality for that kind of song.

Does Lo-fi get played during the day, at night, or in the morning?

Does distance to the equator change the seasonality of a particular song or songs?

Which timezone plays the most K-Pop across all months?

---

> From a business / stakeholder perspective, what are the deliverables of this project? (It's okay if this is hypothetical at this point)

Find drivers of song seasonality, find differences in seasonality based on genre, tempo, danceability, Billboard chart positions, artist, etc., a machine learning model to predict amount of plays per song or type of song, a Jupyter notebook, visualizations, a presentation.

---

> Data Sources
> - Who owns the data?
> - What format is the data in?
> - How will you access the data?
> - Have you accessed the data in the past? Are you currently able to access the data?
> - Are there any special permissions you need to access the data?

- Spotify
- Metadata
- Spotify's API
- No, and Yes
- No

---

> Are there any technologies you plan to incorporate outside of what you learned at Codeup? If so please list them and what you intend to use them for.

Spotipy, a light weight Python library for the Spotify Web API, to make using the API easier.

---

> Are there any third parties (i.e. anyone outside of Codeup) involved in this project? If so, explain their involvement.

No.

---

> Is there any part of this project that can't be shared publicly?

No.

---

> Provide any additional details on what your project will entail.

Features marking seasonality can include:
 * Month
 * Day of Month
 * Year
 * Season (Quarters split by Equinoxes and Solstices)
 * Astrological Sun Sign of that day
 * Moon Phases
 * Events such as Eclipses, Holidays

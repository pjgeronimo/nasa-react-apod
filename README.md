# NASA APOD(Astronomy Picture of the Day) App

This React app uses the NASA API to display NASA's APOD, along with its title. The photo's date and description can be found by opening up the modal using the button in the bottom right. [The app is deployed on Netlify.](https://pjgeronimo-apod-app.netlify.app/)

The app uses the useState and useEffect hooks to render the data fetched from NASA's API. Caching is implemented in order to locally store the data, preventing redundant API calls.

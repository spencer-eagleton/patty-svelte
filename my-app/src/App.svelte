<script>
import { Map, controls, Marker } from '@beyonk/svelte-mapbox'
const { GeolocateControl, NavigationControl, ScaleControl } = controls;
let mapComponent



</script>

<main>
<Map
  accessToken="pk.eyJ1Ijoic3BlbmNlcmVhZ2xldG9uIiwiYSI6ImNsNTF6cXJmYTA1NXEza290ZjgxYnR6a2UifQ.dctP4IPprh_LaSDHqR-moQ" 
  options={{ scrollZoom: true, center: [-74, 40.7] }}>
<Marker
  label={'New York'}
  lat={40.7127281}
  lng={-74.0060152}
  >
</Marker>
<NavigationControl />
</Map>



</main>

<style>

   main {
        height: 100vh;
   }
  /* :root {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
  }

  img {
    height: 16rem;
    width: 16rem;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4rem;
    font-weight: 100;
    line-height: 1.1;
    margin: 2rem auto;
    max-width: 14rem;
  }

  p {
    max-width: 14rem;
    margin: 1rem auto;
    line-height: 1.35;
  }

  @media (min-width: 480px) {
    h1 {
      max-width: none;
    }

    p {
      max-width: none;
    }
  } */
</style>

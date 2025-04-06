# Offset overlapping routes

This web application provides an interactive map visualisation of bus routes with a focus on resolving the challenge of route overlaps. A common issue when displaying a route network map is that overlapping bus routes often obscure one another, making it difficult to distinguish individual lines. This app addresses that by dynamically splitting routes into segments based on where overlaps occur and offsetting only those overlapping segments. Notably, this is achieved 'on the fly' without altering the original route geometries (polylines), ensuring data integrity while greatly improving map clarity and usability.

Developed in TypeScript using React and React-Leaflet with PolylineOffset.

https://route-offset.vercel.app/

# Offset Overlapping Routes

This web app explores a practical solution to a common issue in visualising a route network map: overlapping routes often obscure one another, making it difficult to distinguish individual lines. The app proposes a method to address that by dynamically splitting routes into segments based on where overlaps occur and offsetting only those overlapping segments. This is done 'on the fly', without altering the original route geometries (polylines), improving map readability while keeping the underlying data intact.

Developed in TypeScript using React and React-Leaflet with PolylineOffset.

https://route-offset.vercel.app/

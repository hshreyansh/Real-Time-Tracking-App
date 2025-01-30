# Real-Time-Tracking-App 📌

![image](https://github.com/user-attachments/assets/79bc1dec-eaac-46ce-8915-b7b7b888aedc)

## Overview

This project is a real-time device tracking application that utilizes geolocation and WebSockets to monitor device locations and display them on a map. Built with Node.js, Express, Socket.io, and Leaflet.js, it enables seamless real-time updates and dynamic map rendering.

## Features

1. Real-time Device Tracking: Continuously monitors and updates device locations in real-time.
2. Interactive Map with Markers: Displays device locations on a dynamic map with easily identifiable markers.
3. Automatic Marker Updates: Instantly updates markers as device locations change.
4. Multi-Device Support: Tracks and displays multiple devices simultaneously.

## Tech used

-**Node.js**

-**Express.js**

-**Socket.io**

-**Leaflet.js**

-**EJS (Embedded JavaScript templating)**

## Structure

![image](https://github.com/user-attachments/assets/c4c791df-a90d-48d3-aa66-228e4ed02e2f)

## Working of the Real-time Device Tracking Application 🗺️

## Backend

1. Server Initialization: The server is set up using Express.js, which initializes an HTTP server to handle client requests.
2. Socket.io Integration: Socket.io is implemented for real-time communication. When a client connects, a unique socket ID is assigned.
3. Geolocation Data Handling: The server listens for geolocation updates from connected clients. Upon receiving data, it broadcasts location updates to all clients in real time.
4. Client Disconnection Management: If a client disconnects, the server removes the associated data and notifies other clients to delete the corresponding marker from the map.
   
## Frontend

1. Geolocation Retrieval: The browser’s Geolocation API continuously tracks the device’s position.
2. Socket.io Client: The client establishes a WebSocket connection with the server using Socket.io for real-time updates.
3. Location Transmission: The client sends its current geolocation to the server at regular intervals.
4. Map Rendering: An interactive map is generated using Leaflet.js, with markers representing device locations.
5. Real-time Updates: As new location data is received, marker positions on the map update dynamically.
6. Marker Management: The client-side logic efficiently handles creating, updating, and removing markers based on real-time server data.
   
## Conclusion

>> By integrating Express.js, Socket.io, Geolocation API, and Leaflet.js, this Real-time Device Tracker delivers a seamless and efficient solution for monitoring multiple devices. It ensures instant location updates on an interactive map, making it ideal for real-time tracking applications.
>> 📍📍🌍🌍🗺️🗺️

## Support

📧 email- shreyansh.maholi@gmail.com

🔗linkedin- https://www.linkedin.com/in/shreyansh-shukla-7a7166249/

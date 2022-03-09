# API documentation USSP

This document contains a description of the API between the U-space
services and the drone operators and drones (Interface 4 + 6).
Messages are exchanged using the library ZeroMQ. Each message is
formatted as a JSON-struct.

- [Ground height](doc/1_ground_height.md)

  - [Query Ground Height](doc/1_ground_height.md#Query-Ground-Height)

- [Flight authorization](doc/2_flight_authorization.md)

  - [Request Plan](doc/2_flight_authorization.md#Request-Plan)

  - [Get Plan](doc/2_flight_authorization.md#Get-Plan)

  - [Accept Plan](doc/2_flight_authorization.md#Accept-Plan)

  - [Cancel Plan](doc/2_flight_authorization.md#Cancel-Plan)

  - [Activate Plan](doc/2_flight_authorization.md#Activate-Plan)

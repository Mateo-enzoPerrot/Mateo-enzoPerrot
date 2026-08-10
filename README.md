# Mateo-Enzo Perrot

I write software that reads cars.

Founder of [NexPit](https://nexpit.fr) — automotive software: OBD-II and telemetry
acquisition, time-series processing, embedded vision, mapping applications.
Software engineering student at Epitech (Grande École programme), specialising in
C/Python and systems programming.

**Currently looking for an internship** — Clermont-Ferrand, Lyon, Saint-Étienne or remote.

---

## What I work on

**Vehicle data acquisition and processing.** Reading what a car produces — ECU,
sensors, simulator — and turning it into timestamped, durable data. The hard part is
never a single channel: it is holding an acquisition over time, across sensors that
answer at different rates, on a link that drops at the first speed bump.

**Line-of-business mapping and database applications.** Accounts, roles, geographic
data, real integrity constraints. Rules live in the database, not only in the layer
that gets rewritten next year.

**Computer vision under time constraints.** Running a model on ordinary hardware,
with datasets built for the actual use case rather than borrowed from a public set
that fails precisely on the cases that matter.

---

## Selected projects

| Project | What it does | Stack |
|---|---|---|
| [Pitlabs](https://github.com/Mateo-enzoPerrot/pitlabs) | Sim-racing and track telemetry: channel capture, lap splitting, braking analysis, trajectory comparison | Python, pandas, Tkinter, matplotlib |
| [Vehicle acquisition](https://github.com/Mateo-enzoPerrot/vehicle-acquisition) | 8-channel OBD-II reading, network lap timing on microcontroller, real-time gauges | C, C++, Python, ESP32, TCP sockets |
| [Pr-venx](https://github.com/Mateo-enzoPerrot/pr-venx) | Real-time road sign and traffic light detection on a camera stream, hand-annotated datasets | Python, YOLOv8, OpenCV |
| [nexgen3d](https://github.com/Mateo-enzoPerrot/nexgen3d) | CLI that reconstructs a textured 3D model from a single photograph, Blender-ready | Python, Hunyuan3D-2, TripoSG, trimesh |
| [CarWatch](https://nexpit.fr/en/projets/carwatch) | Garage and fuel station mapping with routing and fuel-cost estimation from real vehicle specs | TypeScript, Express, PostgreSQL, React, Leaflet |
| [RaceShare](https://nexpit.fr/en/projets/raceshare) | Matching platform for drivers, sponsors and motorsport professionals, with real-time messaging | React 19, Express 5, PostgreSQL, socket.io |

Longer write-ups, architecture diagrams and the decisions that cost something are on
[nexpit.fr](https://nexpit.fr/en).

---

## Stack

**Systems & low level** — C, C++, Make, OBD-II, TCP sockets, ESP32, shared memory,
processes and signals

**Python** — pandas, matplotlib, OpenCV, Ultralytics/YOLOv8, Tkinter, trimesh

**Web** — TypeScript, Node.js, Express, React, Vite, React Router, Leaflet, socket.io

**Data** — PostgreSQL (enums, CHECK constraints, versioned migrations), CSV/time-series
formats, glTF

**Practices** — typed APIs with centralised error handling, JWT/bcrypt authentication,
rate limiting, security headers, migrations from day one

---

## How I work

- Constraints go where they hold: in the database, in the types, in the protocol.
- Migrations are versioned from day one, before the database holds anything important.
- A readable format beats a compact one when the data must outlive the tool that wrote it.
- A third-party outage is a nominal case, not an incident.
- I say no when a need falls outside what I can do, rather than learning at a client's expense.

---

## Education

**Epitech — Programme Grande École**
Specialising in C/Python, systems programming, and game development in CSFML.

**Baccalauréat**, 2025

---

## Contact

- Company — [nexpit.fr](https://nexpit.fr) · contact@nexpit.fr
- Email — perrotnomate@gmail.com

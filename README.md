# Bus_Event_-Simulator

A Python event-driven bus system simulator.

## Features
- Simulates buses moving across a ring of stops
- Models passenger arrivals, boarding, drop-off, and travel
- Uses an event queue with discrete-event simulation
- Tracks bus positions, occupancies, wait times, and travel times

## Technologies
- Python
- NumPy
- Matplotlib

## Example
```python
sim = Simulation(num_stops=5, num_buses=2, person_rate=2, trace=False)
sim.run(steps=200)
sim.plot()

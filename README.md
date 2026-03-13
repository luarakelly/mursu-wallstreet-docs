

# Mursu Wallstreet Documentation

This repository contains the documentation for the *Mursu Wallstreet* project.

*Mursu Wallstreet* is a Java-based electronic exchange simulator with a JavaFX user interface.  
The simulator models order arrivals, validation, order matching, trade execution, and order book updates during a simulated trading session.

This repository stores the written project documentation.

## Documentation Structure

- `controller` – JavaFX controllers responsible for UI actions and application flow.
- `database` – persistence layer used to store simulation results and metrics.
- `framework` – core discrete‑event simulation infrastructure (Clock, EventList, Engine, ServicePoints).
- `model` – exchange domain logic including orders, trades, order book, and matching engine.
- `distributions` – random distribution utilities used by the simulation engine.
- `view` – JavaFX user interface components and visualization logic.

## Related Project

The source code of the simulator is located in the main project repository:

`https://github.com/luarakelly/mursu-wallstreet`

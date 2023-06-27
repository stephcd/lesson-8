[![Simulation](../../actions/workflows/main.yml/badge.svg)](../../actions/workflows/main.yml)

# Lesson 8 - Exporting Data

The `tape` module `recorder` object is used to record data from an object. The object must specify the file name, the sampling interval, and the object properties to be sampled.  

The `tape` module can output CSV files with a single header line using the `csv_header_type` module variable using the `NAME` value.

Output data can be plotted using the `plot` subcommand. The `plot` is run when the simulation exits successfully with exit code `0` using the `#on_exit` macro. 

## Tasks

1. Setup the building schedule.
2. Import the `tape` module.
3. Add the commercial building to `load_1`.
4. Add the data recorder to the building.
5. Get and load the weather forecast.
6. Set the simulation clock.
7. Plot the load when the simulation exits successfully.

# Exercices

1. Plot the load of a residential building on load 2.

# More Information

* [Tape module](https://docs.gridlabd.us/index.html?owner=arras-energy&project=gridlabd&branch=master&folder=/Module&doc=/Module/Tape.md)
* [Recorder object](https://docs.gridlabd.us/index.html?owner=arras-energy&project=gridlabd&branch=master&folder=/Module/Tape&doc=/Module/Tape/Recorder.md)

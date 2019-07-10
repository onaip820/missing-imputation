# missing-imputation
Artificial data used in the work of "Smoothed LSTM-AE: A Spatio-Temporal Deep Model for Multiple Time-Series Missing Imputation", for the test of missing imputation performance.


The TE process is a simulation system according to a chemical production process.
It is a commonly used benchmark problem in the process system engineering field.
It simulates many typical characteristics of the real complex industrial process system,
and thus, it is widely applied in the research of control, optimization, process monitoring, and fault diagnosis.
The whole TE process consists of five operating units: reactor, condenser, compressor, separator, and stripper.
There are 41 measurement sensors monitoring temperature, pressure, and liquid levels, and 12 control parameters.
The data used in the experiments are simulated from the TE process MATLAB simulation,
and only the measurement sensor data are used.
A total of 15000 data were simulated for 150 min,
and several control parameters were changed to simulate different operating conditions.
Reactor level: 65 to 75 at 30 min;
Separator level: 50 to 30 at 70 min;
Reactor level: 75 to 65 at 90 min;
Reactor press: 2800 to 2000 at 120 min.

# Navigation Transformation

Transform trust and steering inputs to discrete coordinates

You have the [inputs.csv](inputs.csv) as reference for the values from a simulation and you
also have [outputs.csv](outputs.csv) which is the desired result from your algorithm. The
implementation for the resolution of this problem can be a:

- Neural Network
- Classical mathemathical model

You can test the margin of error with the script:

´´´sh
test.sh output.csv results.csv
´´´

That should give you a close estimation of how "bad" your algorithm is, the lower the better.

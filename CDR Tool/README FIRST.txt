To see that the call generator works
====================================

Choose any of the models by navigating through the records selector.  Press Generate.

When Completed, you can either look at the customerCalls table to see the CDR, or simply run the qryCallSummary4Weeksv2 query to see the aggregated output that is sent to MATLAB via ODBC.

For each model you want to generate, you have to move to the model and click generate.

You can play around with the models all you like, but what must be noted if you change any of the weighted distributions you must scale them to ensure they take the range of 0 to 1.
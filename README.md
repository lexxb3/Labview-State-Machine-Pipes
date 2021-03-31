# Labview-State-Machine-Pipes
State Machine Pipes provides an easy way of implementing the Pipe and Filter design pattern within a state machine in Labview.

This allows you to specify a sequence of operations to be executed as a group (pipe), in which data from one operation is available to be further processed or used by the next operation. Also allows you to cancel the entire pipe if there is an error in one of its operations, for example.

This design pattern allows you to specify operations more granularly, avoiding unecessary duplication of code for similar code sequences. Also allows you to specify 2 or more code sequences which are identical with the exception of one operation (which may be decoded dynamically) without duplicating code.

See the link below for a description of the design pattern:
https://docs.microsoft.com/en-us/azure/architecture/patterns/pipes-and-filters

<b>Contact us at contact@oxorigin.com with any suggestions for improvements, so we can include them in future versions.</b>

www.oxorigin.com

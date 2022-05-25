# RabbitX
This tool can be used to execute EFT payment HSM functions .
You only need to pass the complete function in order to execute the function {Function without header and length} this tool will add Safenet header and length of the function automatically.
It also generates log files with file name as date and time in format YYYY-MM-YY-HH-MM-SS.
It does not have functionality to check the network connection hence if the IP is not whitelisted execution will fail and the tool will shut down.

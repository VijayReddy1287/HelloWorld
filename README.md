# HelloWorld
My first repository
# Low level Test Plan for Fundtransfer
| TEST No. | Description | Expected Input |Expected output | Actual Output | Pass/Fail | HLT No |
|----------|-------------|-----------------|-----------------|----------------|-----------|--------|
| L_7|Check whether the new.dat file is present or not|Pointer to the file|FILE_NOT_PRESENT|FILE_NOT_PRESENT|Pass|H_7|
| L_7|Check minimum balance is sent to reciever account|0|INSUFFICIENT_BALANCE|INSUFFICIENT_BALANCE|Pass|H_7|
| L_7|Check whether sufficient balance is present in sender account|20|SUFFICIENT_BALANCE|SUFFICIENT_BALANCE|Pass|H_7|
| L_7|Check whether account number of sender is present or not|6|ACCOUNT_PRESENT|ACCOUNT_PRESENT|Pass|H_7|
| L_7|Check whether record.dat file is present or not|Pointer to the file|FILE_PRESENT|FFILE_PRESENT|Pass|H_7|

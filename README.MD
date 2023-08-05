# AHR Stamp

## Usage (ahr_stamp.c)

The `counter` increments with each call to ahr_stamp, and the `timestamp` is in the format `YYYYMMDDHHMMSS.NNNNNNNNN`, where:

- `YYYY`: Year
- `MM`: Month
- `DD`: Day
- `HH`: Hour
- `MM`: Minute
- `SS`: Second
- `NNNNNNNNN`: Nanoseconds

To generate an auto-generated timestamp, simply run the `ahr_stamp` command:
ahr_stamp

Example output:
000000001:20230728123456.789012345

## Verify Installation

To verify that the AHR service and `ahr_stamp` utility are installed and running, you can use the following command:
./ahrStamp.sh verify

This command will check if the `ahr_stamp` executable is installed and if the AHR service is running and set to start on boot.

# asof="20230805"
# added simAHR.sh
# https://github.com/ahrink/stamp
# Praevisio Installer is simulation implementing the ahr_stamp as a service for future projects:
# https://github.com/ahrink/Praevisio-Installer

## License
This project is licensed under the [MIT License](LICENSE).

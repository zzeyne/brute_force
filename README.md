# brute_force
Script to detect brute force attempts from auth.log
# Brute Force Detection Script

A simple Python script that analyzes `auth.log` to detect possible brute force attacks by counting failed SSH login attempts per IP address.

## Usage

1. Place your `auth.log` file in the same directory as `brute_force.py`.
2. Run the script:

```bash
python brute_force.py

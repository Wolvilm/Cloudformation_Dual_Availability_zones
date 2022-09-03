# Cloudformation_Dual_Availability_zones

The template when run allows you to choose a region and two availability zones.

It then goes on to spin up a vpc and subnets based on the selected options.

It should be noted that EIPs do not get deleted when you delete your stack and there are only 5 allowed at any one time per vpc (unless you request more from AWS).

If you run into issues, be sure to check that this isn't what's holding you back. You might need to manually delete the EIPs.

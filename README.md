# macOS-Patching
A script to manage macOS updates from Jamf

MacOS updates are notoriously bad for enterprise users with no real way to manage them or let users know whats going on.

This script adds simple interactive user prompts to alert them to updates being available. The user can choose to install the udpates or to postpone them for 4 days and then will force them on the 4th day. This can all be customized to your settings within the script.

The script will also differentiate between M1 and Intel macs and update the device according to the correct method.

Some pre-reqs are required to set in Jamf to scope devices in need of updates and also just to avoid issues. (UPDATE TO FOLLOW)

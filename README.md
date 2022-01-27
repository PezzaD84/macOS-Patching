# macOS-Patching
A script to manage macOS updates from Jamf

MacOS updates are notoriously bad for enterprise users with no real way to manage them or let users know whats going on.

This script adds simple interactive user prompts to alert them to updates being available. The user can choose to install the udpates or to postpone them for 4 days and then will force them on the 4th day. This can all be customized to your settings within the script.

The script will also differentiate between M1 and Intel macs and update the device according to the correct method.

Some pre-reqs are required to set in Jamf to scope devices in need of updates and also just to avoid issues. (UPDATE TO FOLLOW)


<img width="615" alt="Screenshot 2022-01-27 at 15 20 18" src="https://user-images.githubusercontent.com/89595349/151388704-f5e52c23-f191-4cc3-9cb8-2693fdf55428.png">
<img width="554" alt="Screenshot 2022-01-27 at 15 21 04" src="https://user-images.githubusercontent.com/89595349/151388794-fc4d99a7-310d-4782-8ec5-29ef69f58bb0.png">
<img width="546" alt="Screenshot 2022-01-27 at 15 21 40" src="https://user-images.githubusercontent.com/89595349/151388821-ad0f6ed6-83d4-4550-8636-9466fd1ef5d3.png">

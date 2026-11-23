This project is a step-by-step guide for setting up a personal private cloud storage server using Nextcloud on Ubuntu, along with a web-based server management tool.

Key components include:

Nextcloud Installation: Installing Nextcloud via Snap, configuring admin credentials, opening firewall ports, and resolving common conflicts (e.g., stopping Apache2 and setting trusted domains).

Cockpit Management: Installing and enabling Cockpit, a browser-based server management dashboard, and opening its port (9090) for monitoring and administration.

Storage Verification: Using df -h to check available disk space for Nextcloud data.

Device Partitioning: The partition-size-5.pdf outlines a recommended disk layout (EFI, Boot, Root, Swap, Home) totaling ~1 TB, ensuring the server has sufficient space for cloud storage.

The included screenshots illustrate the expected outcomes: untrusted domain errors, Cockpit's login page, Nextcloud's login screen, and the Apache2 default page.

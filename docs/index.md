# Welcome

![Home Page](./img/misc/title_image.png)

## Introduction

The SANS Holiday Hack Challenge 2025 dropped participants into a winter town taken by mischievous gnomes, breaking things across city hall, the hotel, the park, and the retro shop. The challenge spans 27 objectives across five difficulty tiers, covering offensive and defensive security topics.

I completed 21 of the 27 objectives, spanning cloud security (Azure RBAC, storage, and network misconfigurations), web application exploitation (IDOR, JWT/JWKS spoofing, Firebase leaks), core networking and firewalls, digital forensics and reverse engineering, and hardware signal analysis (1-Wire, SPI, I²C) and proposed prevention for exploitation objectives.

<!-- ### Story

ACT I

The Counter Hack crew is in the Neighborhood festively preparing for the holidays when they are suddenly overrun by lively Gnomes in Your Home! There must have been some magic in those Gnomes, because, due to some unseen spark, some haunting hocus pocus, they have come to life and are now scurrying around the Neighborhood.

ACT II

The Gnomes’ nefarious plot seems to involve stealing refrigerator parts. But why?

ACT III

The Gnomes want to transform the neighborhood so that it’s frozen solid year-round, an environmental disaster. But who is the mastermind behind the Gnomes’ wickedness? -->

### Map

![Map of Area](./img/misc/map.png)

??? tip "Navigation tip"
    Even with less than 50 pages, there's still quite a bit of information to read through. To make things a little easier, you can use ++"P"++ or ++","++ to go to the previous section, ++"N"++ or ++"."++ to navigate to the next section, and ++"S"++, ++"F"++, or ++"/"++ to open up the search dialog.

    **TL;DR** if you keep pressing ++"N"++ or ++"."++ from this point forward, you'll hit all the content in the right order! :smile:

## Answers


??? success "Act I"

    !!! success card "1. Its All About Defang - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
        [Phishing & IOC analysis : investigated a malicious email and defanged/reported its indicators of compromise.](./objectives/o1.md){: .card-link }

    !!! success card "2. Neighborhood Watch Bypass - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
        [Linux privilege escalation : escalated from a restricted shell to admin access to restore the fire alarm system.](./objectives/o2.md){: .card-link }

    !!! success card "3. Santa's Gift-Tracking Service Port Mystery- :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
        [Network service enumeration : used `ss` to locate a relocated service's listening port and validated it with `curl`.](./objectives/o3.md){: .card-link }

    !!! success card "4. Visual Networking Thinger - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
        [Core networking protocols : walked through DNS, TCP handshake, HTTP, TLS, and HTTPS flows in an interactive packet simulator.](./objectives/o4.md){: .card-link }

    !!! success card "5. Visual Firewall Thinger - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
        [Firewall rule design : configured zone-based firewall rules to enforce least-privilege access between network segments.](./objectives/o5.md){: .card-link }

    !!! success card "6. Intro to Nmap - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
        [Network scanning with Nmap : ran targeted and full-range scans to discover open ports and hidden services.](./objectives/o6.md){: .card-link }

    !!! success card "7. Blob Storage Challenge in the neighborhood - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
        [Azure Storage auditing : used the Azure CLI to find a storage account with public blob access misconfigured.](./objectives/o7.md){: .card-link }

    !!! success card "8. Spare Key - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
        [Azure least-privilege review : audited storage accounts via CLI to uncover an exposed website leaking a spare credential.](./objectives/o8.md){: .card-link }

    !!! success card "9. The Open Door - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
        [Azure NSG auditing : enumerated Network Security Groups via CLI to find a rule exposing RDP/SSH to the internet.](./objectives/o9.md){: .card-link }

    !!! success card "10. Owner - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
        [Azure RBAC auditing : queried subscriptions and role assignments via CLI to find identities with standing Owner access.](./objectives/o10.md){: .card-link }

??? success "Act II"

    !!! success card "11. Retro Recovery - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
        [Disk image forensics : mounted and analyzed a FAT12 floppy disk image to recover hidden files.](./objectives/o11.md){: .card-link }

    !!! success card "12. Mail Detective - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
        [IMAP investigation : used `curl` to enumerate a mailbox over IMAP and trace a phishing lead to a pastebin URL.](./objectives/o12.md){: .card-link }

    !!! success card "13. IDORable Bistro - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
        [IDOR exploitation : manipulated a receipt endpoint's object reference to enumerate records and identify a target customer.](./objectives/o13.md){: .card-link }

    !!! success card "14. Dosis Network Down - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
        [Router RCE (CVE-2023-1389) : exploited an unauthenticated command injection flaw to recover the Wi-Fi password from a router's config.](./objectives/o14.md){: .card-link }

    !!! success card "15. Rogue Gnome Identity Provider - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
        [JWT/JWKS spoofing : forged a JWKS-based JWT to escalate privileges and identify the malicious firmware being served.](./objectives/o15.md){: .card-link }

    !!! success card "16. Quantgnome Leap - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
        [SSH key recon & crypto trail : traced SSH key comments and post-quantum key material across a server to recover the final flag.](./objectives/o16.md){: .card-link }

    !!! success card "17. Going in Reverse - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
        [Reverse engineering : reverse engineered a Commodore 64 BASIC program's XOR obfuscation to recover the hidden flag.](./objectives/o17.md){: .card-link }

??? success "Act III"

    !!! success card "18. Gnome Tea - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star:"
        [Firebase misconfiguration : exploited an exposed Firebase client config to query Firestore directly and leak a secret passphrase.](./objectives/o18.md){: .card-link }

    !!! success card "20. Snowcat RCE & Priv Esc - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star:"
        [Web RCE & privilege escalation : chained a deserialization RCE with privilege escalation to recover an unused API key.](./objectives/o20.md){: .card-link }

    !!! success card "21. Schrödinger's Scope - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star:"
        [Scoped web app pentest : conducted a scoped penetration test of a registration site while working around gnome interference.](./objectives/o21.md){: .card-link }

    !!! success card "23. On the Wire - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star:"
        [Signal protocol analysis : decoded 1-Wire, SPI, and I²C captures and XOR-decrypted the payload to extract sensor data.](./objectives/o23.md){: .card-link }


██████╗ ███████╗ █████╗ ██████╗ ███╗   ███╗███████╗ 
██╔══██╗██╔════╝██╔══██╗██╔══██╗████╗ ████║██╔════╝ 
██████╔╝█████╗  ███████║██║  ██║██╔████╔██║█████╗   
██╔══██╗██╔══╝  ██╔══██║██║  ██║██║╚██╔╝██║██╔══╝   
██║  ██║███████╗██║  ██║██████╔╝██║ ╚═╝ ██║███████╗ 
╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═════╝ ╚═╝     ╚═╝╚══════╝ 
---------------------------------------------------------------------------

# CB Studios — Resource Versions

Official public version metadata maintained by CB Studios.

This repository provides a centralized and lightweight source of public
release information used by CB Studios products and services.

---------------------------------------------------------------------------

# Repository Purpose

This repository is dedicated exclusively to public version metadata.

It allows supported CB Studios products to check their installed version
against the latest published release information.

The repository may contain metadata such as:

• Resource identifier
• Product name
• Published version
• Release information
• Documentation URL
• Official store URL

No commercial resource files are distributed through this repository.

---------------------------------------------------------------------------

# Repository Structure

The repository uses a simple metadata-based structure:

versions/

├─ resource-name.json
├─ another-resource.json
└─ ...

Each JSON file corresponds to a CB Studios product and contains only
the public information required for version and release checking.

This structure allows additional products to be added without requiring
changes to this documentation.

---------------------------------------------------------------------------

# Version Format

CB Studios uses Semantic Versioning for published releases.

Format:

MAJOR.MINOR.PATCH

Examples:

1.0.0
1.0.1
1.1.0
2.0.0

Version metadata is maintained by CB Studios and represents the latest
publicly published release.

---------------------------------------------------------------------------

# Update Checking

Supported CB Studios products may use the public metadata provided by
this repository to perform an update check during initialization.

The general process is:

Installed Version
        ↓
Public Version Metadata
        ↓
Version Comparison
        ↓
Release Status

Update checking is informational and should not prevent a product from
operating when the metadata service is temporarily unavailable.

---------------------------------------------------------------------------

# Public Information Only

This repository does not contain private or protected product data.

The following information is not stored here:

• Commercial source code
• Protected assets
• Customer files
• Private configuration
• License keys
• Purchase information
• Authentication credentials
• Internal development files
• Private server information

The repository exists only to provide public release metadata.

---------------------------------------------------------------------------

# Distribution

Commercial CB Studios products, downloads and customer access are
provided through the official CB Studios distribution channels.

This repository is not a download mirror and does not grant access to
commercial products.

---------------------------------------------------------------------------

# Data Integrity

Version metadata is maintained by CB Studios.

The contents of the metadata files should be treated as official public
release information published by CB Studios.

If metadata appears to be incorrect or unavailable, please contact
CB Studios through the official support channel.

---------------------------------------------------------------------------

# Support

For product-related technical support, please use the official
CB Studios support Discord.

When requesting support, include relevant information such as:

Product Name
Installed Version
Server Build
Framework (if applicable)
Relevant Dependencies
Console Errors
Description of the Issue

Support Discord:

https://discord.gg/hsx6AvBg5s

---------------------------------------------------------------------------

# Copyright

© CB Studios. All rights reserved.

This repository contains public version metadata only.

No rights are granted to redistribute, resell, reproduce, modify,
or otherwise distribute CB Studios commercial products through this
repository.

 ██████╗██████╗     ███████╗████████╗██╗   ██╗██████╗ ██╗ ██████╗ ███████╗ 
██╔════╝██╔══██╗    ██╔════╝╚══██╔══╝██║   ██║██╔══██╗██║██╔═══██╗██╔════╝ 
██║     ██████╔╝    ███████╗   ██║   ██║   ██║██║  ██║██║██║   ██║███████╗ 
██║     ██╔══██╗    ╚════██║   ██║   ██║   ██║██║  ██║██║██║   ██║╚════██║ 
╚██████╗██████╔╝    ███████║   ██║   ╚██████╔╝██████╔╝██║╚██████╔╝███████║ 
 ╚═════╝╚═════╝     ╚══════╝   ╚═╝    ╚═════╝ ╚═════╝ ╚═╝ ╚═════╝ ╚══════╝ 

Store -> https://pichirin-cb.tebex.io/
Documentation -> https://docs.pichirincb.com
Support Discord -> https://discord.gg/hsx6AvBg5s  

---------------------------------------------------------------------------

End of documentation

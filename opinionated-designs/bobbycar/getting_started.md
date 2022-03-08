---
layout: home
title: Getting Started
nav_order: 3
has_children: false
parent: Bobbycar
grand_parent: Opinionated Designs
---

# Bobbycar - Installation

You can use the **install.sh** script to simply install demo.

1. Fill in the mandatory properties in **install_cleanup_vars.sh**, i.e.:


    NAMESPACE=bobbycar

    APP_DOMAIN=apps.ocp.domain

    API_DOMAIN=api.ocp.domain

    GOOGLE_API_KEY=here_goes_my_maps_api_key

2. Run the **install.sh** script

3. Run the **cleanup.sh** script to uninstall the demo

If you want to manually install Bobbycar in your own environment, please follow these [installation instructions!](https://github.com/sa-mw-dach/bobbycar/tree/master/helm)
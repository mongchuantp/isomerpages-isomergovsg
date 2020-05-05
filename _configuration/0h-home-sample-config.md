---
title: Sample Configuration
permalink: /configuration/home/sample-config/
third_nav_title: Home Page
---
This is a full sample configuration for a home page, integrating every section that has been covered. You may copy this configuration to your home page as a start, and edit the values accordingly.

```yml
---
layout: homepage
title: Ministry of ABC
description: The Ministry of ABC is the ministry in charge of XYZ
permalink: /
notification: Initiative A will be launching soon! <a href="/register/">Register now</a>
sections:
    - hero:
        title: Ministry of ABC
        subtitle: We provide Singaporeans with XYZ services
        background: /images/banner.png
        url: /contact-us/
        button: Contact
        key_highlights:
            - title: ABC services
              description: Find out what ABC can do for you
              url: /services/
            - title: Our Annual Reports
              url: /annual-reports/
            - title: Join ABC
              description: Unleash your passion and be rewarded with a fulfilling career!
              url: /careers/
    - infobar:
        title: Work for the public good
        subtitle: Careers
        description: Start a fulfulling and rewarding career with the Ministry of ABC!
        button: Join Us
        url: /careers/
    - infopic:
        title: Integrity
        subtitle: Core Values
        description: Integrity drives everything we do at the Ministry of ABC
        button: Learn More
        url: /core-values/
        image: /images/integrity.png
        alt: Members of the Ministry of ABC shaking hands
    - infopic:
        title: Professionalism
        subtitle: Core Values
        description: We strive to deliver work of the highest calibre
        button: Learn More
        url: /core-values/
        image: /images/professionalism.png
        alt: Members of the Ministry of ABC in suits
    - resources:
        title: Media
        subtitle: Learn more
        button: View More
---
```

The above configuration will produce a home page similar to the following:

![Full page screenshot of a home page](/images/config/home.png)

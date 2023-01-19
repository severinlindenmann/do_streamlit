---
title: Deploy Streamlit to Digitalocean
date: 2023/1/13
description: How to deploy streamlit to digitalocean
tag: web development
author: Severin
---

import Image from "next/image";

# How to Deploy Streamlit to Digitalocean App

## Step 1 - Create Repo

Create a Github Repo or clone [my Example](https://github.com/swisscenturion/do_streamlit)

## Step 2 - Create Digitalocean App

Create the app and configure
<Image
  src="https://images.severin.io/blog/images/blog/1_1_create_app.PNG"
  alt="Severin Lindenmann"
  width={900}
  height={600}
  priority
  className="next-image"
/>

## Step 3 - Edit the Run Command

```
streamlit run streamlit_app.py --server.port 8080 --server.headless true
```

<Image
  src="https://images.severin.io/blog/images/blog/1_1_run_command.png"
  alt="Severin Lindenmann"
  width={900}
  height={600}
  priority
  className="next-image"
/>

## Step 4 - Deploy and Enjoy

<Image
  src="https://images.severin.io/blog/images/blog/1_2_success.PNG"
  alt="Severin Lindenmann"
  width={900}
  height={600}
  priority
  className="next-image"
/>

If you find my blogs informative and helpful, I would greatly appreciate it if you used my referral link. Not only will it support my efforts in creating content, but it can also provides you with a free $200 credit on digitalocean.
[![DigitalOcean Referral Badge](https://web-platforms.sfo2.digitaloceanspaces.com/WWW/Badge%202.svg)](https://www.digitalocean.com/?refcode=5cd6ce01ae65&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=badge)

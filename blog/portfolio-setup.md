---
title: "How I Set Up My Cybersecurity Portfolio"
layout: default
---
# How I Set Up My Cybersecurity Portfolio

**When I started job hunting, I realized I needed a single, professional URL to showcase my security projects and streamline my outreach.** I wanted a secure domain, branded email, and a live site—all without spending days on setup.

## Step 1: Register Domain & Enable 2FA  
I chose **cyber-pat.com** through Cloudflare Registrar for its wholesale pricing and simple dashboard. Immediately after purchase, I activated TOTP-based two-factor authentication on my Cloudflare account to protect against unauthorized changes. With nameservers pointed to Cloudflare, I could manage DNS and email routing in one place.

## Step 2: Configure Email Routing  
Using Cloudflare’s Email Routing feature, I created **me@cyber-pat.com** and forwarded it to my Gmail. Cloudflare automatically published SPF, DKIM, and DMARC records to prevent spoofing. A live test email and quick `nslookup` confirmed that my branded address was fully functional within minutes.

## Step 3: Launch GitHub Pages Site  
I initialized a public repo named **cyber-pat-portfolio** on GitHub, added an `index.html` landing page, and pointed the custom domain in the Pages settings. GitHub issued an SSL certificate, securing the site over HTTPS. Visitors now see my Bio, Contact, and project links live at **https://cyber-pat.com**.

## Key Takeaway  
Automating DNS, email, and hosting setup saves time and builds a strong security baseline. Securing your domain and communications early prevents headaches down the road and signals professionalism to recruiters.

**Check out the full code and step-by-step instructions on GitHub:**  
[Jumpman2217/cyber-pat-portfolio](https://github.com/Jumpman2217/cyber-pat-portfolio)  
Feel free to fork and share your feedback!  

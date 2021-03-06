---
layout: post
title: "Sayuri"
published: true
comments: true
categories:
- General
tags:
- Servers
- Linux
- Colo
- MacStadium
- Sayuri
---
### Nayuki and Shiori

I've had colo servers since around 2003, when I built Nayuki and racked her in my friend's rack at Stargate (now Expedient).  Nayuki is still alive and kicking after 10 years, though she wasn't without downtime during that period.  Over the years, she's had catastrophic hardware failure including hard drive and SATA controller failures.  She originally hosted various web sites, a mail server, DNS, IRC/SILC servers, and served as my main gateway to IRC.  At some point, I bought Shiori, and migrated some of the web sites from Nayuki to her to spread the load.  When Nayuki's hard drive failed, I moved my mail to Google Apps, and DNS to Shiori.  She lived in my apartment for a while, mostly powered off.  I eventually was able to get most of the data from the failed hard drive, though, through pure luck, but I had already reformated her with a compact flash drive for boot partitions (this was before SSD was viable) and new SATA drive for storage.  I re-racked her for the purpose of personal storage and IRC access only -- Shiori was my main server at that point.

Both Nayuki and Shiori's hardware was getting pretty dated, and storage on Shiori was always very low due to small drives and RAID-5 configuration.  So I started to plan on getting a new server.  With the rise of dedicated mac mini colo facilities, it quickly became obvious that they were my best option for a new server.  Shipping 1U servers is expensive, but I'd be able to easily move a mac mini server between colo facilities for not a whole lot of money.  This was increasingly important because my friend's rack was starting to be unreliable due to subletters leaving and him having trouble making payment on the rack.  Simply put, I could no longer depend on the servers there being accessible on a long-term basis.

I decided to go with macstadium because of pricing: unlimited 100mbps bandwidth and 5 ip addresses 


### Hard Drive Death

Unfortunately, shortly after she was racked, Sayuri began to show signs of drive degradation with slow write speeds.  There were no kernel messages at first, but after a while, they started flying in.  The second drive must have got damaged during shipment.

"Ugh.  I don't want to have to deal with this," I thought, as my stomach sank a little bit.  I'd have to have the drive shipped back to me, then buy a new hard drive, then watch 20 youtube videos on how to take apart a Mac Mini to replace the drive.  Then I'd have to ship it back to the colo, hoping that it didn't suffer the same fate.

But I didn't have to do any of that!  I opened a ticket with MacStadium and asked them how they usually handle this, as I'm sure it happens frequently for them.  They replied back within a half hour saying "We can replace it no problem with Genuine Apple parts.  Which drive model is it? 1TB 5400 RPM? 500GB 5400 RPM? 500GB 7200 RPM? Other?"

Holy crap!  They'll swap out the drive for me?!  I totally wasn't expecting that level of service.  Hardware maintenance was always something I had to do on my own with Nayuki and Shiori and after moving away from Pittsburgh, I had to have friends/family do maintenance for me.

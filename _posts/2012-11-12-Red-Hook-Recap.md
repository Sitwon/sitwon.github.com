---
layout: post
title: Red Hook Recap
---

Over this past weekend the Project Byzantium team was called up to New York to help with continuing
communications challenges resulting from Hurricane Sandy and then the Nor'easter that followed it.
We did manage to get quite a big accomplished, but it wasn't quite what we had expected. It would
probably be a good idea to start from the beginning.

Project Byzantium is an emergency mesh networking project that I have been involved with since it
began in February of 2011. We envisioned Byzantium being used to help restore communications in
emergency situations such as political protests (Occupy, Arab Spring) or natural disasters (Haiti,
Katrina). In the process of developing Byzantium we have connected with other groups developing
similar solutions, such as the Commotion Wireless project of the New America Foundation's Open
Technology Institute. Hurricane Sandy, which caused a tremendous amount of damage in New Jersy and
New York, is exactly the type of situation that we have been developing Project Byzantium to help
with. So when we heard from Willow Brugh of Geeks Without Bounds (GWOB.org) that our software and
expertise was needed we were jumped at the opportunity.

It began on Tuesday when Willow sent us a short and rather cryptic email that Byzantium was needed
to help restore communications in an area that had been affected by Sandy. The email didn't mention
which state we were headed to, let alone which neighborhood, but we were ready to drive up there
immediately anyways. Since she mentioned that we may need to run off of solar power I figured that
Commotion routers would ultimately be a part of the solution, as the Ubiquity hardware they run on
is much more power-thrifty than a laptop booted with Byzantium Linux. We set to work that evening
prepping a special re-spin of Byzantium to interoperate seamlessly with Commotion and solve some
other challenges that had been sitting on our to-do list. Then we did not hear back for a couple
days and began wondering if the whole plan had fallen though.

Finally on Friday afternoon we got a reply from Willow with some details and contacts who could fill
in the rest for us. We immediately left from work, packed my car, and hit the road. By this time our
modifications to Byzantium were mostly completed by not yet fully tested. Friday night we made it up
to Bridge Water, NJ, where we spent the night in a hotel before continuing on to Red Hook at 10am
the next morning. When we arrived we found that our destination was an Ikea in Red Hook that FEMA
was using as a base of operations. Once there we met Frank and Tony and found out that we would be
helping the Red Hook Initiative (RHI) to extend their exiting Commotion Wireless network, whoes
progress had been stymied by a lack of cooperation from the City ... until Sandy happend. Now, with
city officials on their side, they wanted to accelerate their deployment efforts and connect as much
of the public areas and public housing as they could.

Over the course of the morning and early afternoon The Doctor and I polished out some final kinks in
the latest Byzantium build while Chris went back to RHI with Tony and began flashing routers with
the Commotion Wireless firmware. Later, The Doctor and I also found our way to RHI where we started
planning with Tony where place new routers for optimal coverage. He took us to the roof of one
building where a router had already been deployed so we could check out the lines of sight and we
helped him identify a few alternative paths we could take to linking the building with the RHI
center. On our way back, we were lucky enough to speak to the propery owner of one location and we
got a router installed on his roof that very night.

On Sunday, we got back to RHI at 10:30am. Just as we were settling in a pair of technicians arrived.
Frank had worked some magic with IT-DRC to get a 15M satellite connection installed on the roof of
the RHI center to provide bandwidth to the mesh we were rolling out. Working together we got the
satellite installed and running in record time. (No small feat given the weight of the equipment and
the difficult roof access.) Afterwards, Johnathan and I went out to deploy a new router which
provided internet access to Coffee Park and surrounding buildings. Chris and The Doctor hung back to
resolve some lingering issues with the gateway router and continue flashing routers with Commotion.
By the end of the weekend they must have flashed at least two dozen routers, which were neatly
labled and organized to faciliatate a rapid rollout.

So at the end of the day we did not actually deploy any Byzantium nodes. It was ironic but this was
a case where we had plenty of Ubiquiti routers (normaly pretty exotic hardware), but the spare
laptops we had asked for never actually materialized. Also, given some of the limitations of
Byzantium as it stands today, such as the inability to connect with mobile devices, Commotion _is_
a better solution if you have the hardware available. However, we did lend our experience with mesh
networking and deployment to save them several days of effort and greatly expedite the roll-out of
mesh-delivered Interent to a community still struggling with basic infrastructure more than two
weeks after the storm. It may not be precisely what we had expected to accomplish, but as far as I
am concerned it was still a significant accomplishment. By Sunday night when we left, we all felt
that we can done everything we could manage to do in those two days and set up RHI for a smooth
deployment process once they get the access they need from city officials.

There were many more small accomplishments and lessons learned from this adventure, I think, going
forward, we may end up making some big changes to the way we approach Project Byzantium. This
experience has shown us that there are a number of practical challenges of a deployment which may
reduce the effectiveness of what we have created so far. We are going to re-evalute some of our
design decisions at an up-coming development sprint and try to get more involved with on-site
disaster recovery efforts to continue to learn about how we can best approach and solve these kinds
of problems.

Get involved:
http://www.project-byzantium.org
http://www.gwob.org
http://rhicenter.org/
https://redhook.recovers.org/


# Week 1

**Objectives:** Docker, Terraform, SQL Refresher

## My Background coming into this week

- Had heard of Docker and Terraform before
- In my day job (analytics engineer), I don't deal with these directly; as we have a strong DevOps function at work
- But, sometimes it does feel like "cheating" as I just wing through conversations at work around these tools
- Everytime I tried understanding Docker; I have just given up. Sometimes, I fall asleep. Sometimes, I choose to Netflix over Docker.  
- My biggest fear before starting the week, was the fear of *not completing*.

## Thoughts while going over the course material

- Damn! Why the hell am I doing this at 1:00 am?
- I need coffee!
- Okay...this Docker thing is not as bad as I have feared it
- Wait, so all of this is just copy-paste?
- This is such well-designed material and these are well-presented videos
- Oooh...there is homework too? Wait, submission is in 2 days?
- Love how Alexey is googling bits as he is teaching. Makes it seem real and relatable.

## Keystone Concepts

Btw, these are summarised versions of my handwritten (handdrawn) notes as I went over the material. Most probably, the only person who these notes may make sense to in the world would be me.

If you were looking for much better notes than my ramblings, check out notes from the community [here](https://github.com/DataTalksClub/data-engineering-zoomcamp/blob/main/01-docker-terraform/README.md#community-notes)

### What is Docker?
- Think isolation, think self-contained containers, think "it works on your system, then why not on mine?"
- Dockerfile + Application Code => Docker Image => Docker Container
- Reproducibility, local experiments, integration testing, cloud deployment
- A Dockerfile is just a bunch of commands `INSTRUCTION command`; `FROM`, `RUN`, `COPY`, `ENTRYPOINT`
- Docker desktop - GUI to manage it all
- Want to persist data? Think Docker volumes. When a container starts, it gets data from the host
- Want containers to share assets? Think Docker network
- You can stick together a whole data pipeline using Docker (note to self: check drawings in notebook)
- Want multiple containers to run together? Think Docker Compose

### Setting up a GC project
Not much to take down here. I work with Gogle Cloud everyday. So, pretty simple.

### What is Terraform?
- Infrastructure As Code
- Simple, code-driven, easy to collaborate, reproducibility, ensures resources are removed
- Does not manage code on the infra
- Can only handle bits defined in the `.tf` files
- Key commands - fmt, init, plan, apply, destroy
- Download from Hashicorp. Also, get the VS Code plugin for ease of development
- Terraform Providers, Resources, Variables








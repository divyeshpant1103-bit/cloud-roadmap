# Cloud Learning Roadmap (Winter Break 2026)

My plan for the break: build a networking base first, then Linux, then AWS cloud fundamentals.
Everything I watch, read and build goes in this repo.

## Plan (about 4 weeks)

| When | Topic | Main resource |
|---|---|---|
| Weeks 1-2 | Networking | Professor Messer Network+ N10-009 |
| Days 15-18 | Linux and command line | Linux Journey, freeCodeCamp Linux course |
| Weeks 3-4 | AWS cloud fundamentals | Andrew Brown's Cloud Practitioner course (freeCodeCamp) |
| Stretch | AWS Cloud Practitioner exam | AWS Skill Builder |

After the break: core services (EC2, VPC, RDS, Lambda, load balancers), a deployment project, Docker, CI/CD, Kubernetes and Terraform.

## Playlists and links

### Networking
- [Professor Messer N10-009 Network+ playlist](https://www.youtube.com/playlist?list=PLG49S3nxzAnl_tQe3kvnmeMid0mjF8Le8) - 87 videos, about 12h 55m. Focus on Section 1 (concepts, IP, subnetting).
- [Professor Messer course index](https://www.professormesser.com/network-plus/n10-009/n10-009-video/n10-009-training-course/)
- [Practical Networking](https://www.practicalnetworking.net) - for subnetting and how packets move. Watch when Messer doesn't click.
- Google Bits and Bytes of Computer Networking (Coursera, audit free) - link: TODO
- Neso Academy / Gate Smashers computer networks playlists (Hindi) - link: TODO

### Linux
- [Linux Journey](https://linuxjourney.com)
- freeCodeCamp Linux course (YouTube) - link: TODO

### AWS
- Andrew Brown, AWS Cloud Practitioner (freeCodeCamp, YouTube) - link: TODO
- [AWS Skill Builder](https://skillbuilder.aws) - free Cloud Practitioner prep

## Checklist

### Networking
- [ ] OSI and TCP/IP models
- [ ] Binary math
- [ ] IPv4 addressing and subnetting (by hand)
- [ ] IPv6 basics
- [ ] DNS, DHCP, NAT
- [ ] Routing and switching
- [ ] Firewalls and ports
- [ ] Wireshark: capture and read a real trace
- [ ] `ping`, `traceroute`, `nslookup`, `curl` on my Mac

### Linux
- [ ] File system and permissions
- [ ] Processes and services
- [ ] `ssh`, `grep`, `curl`
- [ ] Package managers
- [ ] A simple shell script

### AWS fundamentals
- [ ] Open AWS account and set a billing alert (do this first)
- [ ] Cloud basics, regions and availability zones
- [ ] Shared responsibility model
- [ ] IAM: users, roles, policies
- [ ] Pricing model
- [ ] Launch and terminate one EC2 instance
- [ ] Create an S3 bucket
- [ ] Look at a default VPC and its subnets and security groups

## Repo layout

```
cloud-roadmap/
├── README.md        this file
├── networking/      notes, subnetting practice, Wireshark captures
├── linux/           command cheat sheet, scripts
├── aws/             notes, screenshots, small experiments
└── projects/        later: the deploy-behind-a-load-balancer project
```

## Notes
- Keep a short note per video or topic in the matching folder.
- Billing alert first, then everything else. Terminate what I launch.

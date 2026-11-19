# Make Software that Heals itself

## Steps

- 1990s: Bare Metal: servers you own
- 2000s: Virtual Machines: many pretend machies that share resources on one
- 2006: Rent by the hour: Cloud servers on demand
- 2013: Containers: Pack an app with all dependancies
- 2014: Orchestrate: Kubernetes keeps you app alive for you

## Common Problems
- Too many people accessing the application
- Crashes: Things break at 2am
- Chain reactions: one small bug takes everything down
- "It works on my machine" : runs here breaks anywhere else


### 1/4 Crowds
- Scale up: Buy bigger machines.Costly, idle most of the year and still just once
- Scale out: Add identical copies when busy, remove them when it's quiet

### 2/4 Crash at 2am
- Self Healing: Run several copies, something watches them

### 3/4 Chain Reactions
- Split apps into parts
- Monolith: one big program: one failure makes the whole thing goes down)
- Microservices: Small programs that interact with each other

Downside: More parts to monitor

### 4/4 "It works on my machine"
- Containerization: put app and dependencies together

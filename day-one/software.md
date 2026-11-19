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

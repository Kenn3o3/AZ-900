# [[Global Infrastructure]]
## Fault and Update Domains

<hr>

An [[Availability Zones]] (AZ) in Azure region is a combination of a ==fault domain== and an ==update domain==.

Fault Domain:
*A logical grouping of hardware to avoid a single point of failure within an AZ. group of virtual machines that share a common power source and network switch.*

Update Domain
*Azure may need to apply updates to the underlying hardware and software. Update domains ensure your resources do not fo offline.*

Availability Set
*A logical grouping that you can use in Azure to ensure that the VMs you place in the Availability Seet are different fault/update domains to avoid downtime.*

![](https://lh5.googleusercontent.com/Zu8ihEoMgdVm8uEhmF0m-g3LLnyYn0Cjq3CoV-fLTrNV4nkkD8yYEdbAsZt1UJAbAaM7fm7EtfaBbDfsORGFAb8l34D1soWjD0u8gM55dTrW8NCYKbHFvJqo06zEzULQqE591kkN_dmb9C3tRQ)

Next Chaper -> 
<- [[Main]]
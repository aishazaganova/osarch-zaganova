**Allocation:** 

*For Ubuntu Server guest:* 

vCPUs: 1

disk size: 2 GB RAM (dynamically allocated)

memory: 10 GB

network adapter(s): NAT

mode: virtual

*For Windows 11 guest:(impossible to run)*

vCPUs: 0

disk size: 2 GB RAM (dynamically allocated)

memory: 10 GB

network adapter(s): NAT

mode: virtual



**Arithmetic:**

Left for the host:

vCPUs: 1

disk size: 4 GB RAM

memory: 11 GB free

I think host needs the base minimum of 1 vCPU, but in this case it's impossible to run all the guests with the host. To function properly 2 GB RAM is fine, but it's better to have more RAM for smooth operations. Memory is the one left after the guests, that's why I left it the way it is.



**Justification:**

Again, the same thing I stated in arithmetic category.



**Verification plan:**

Unfortunately, it seems that to have 2 guests run at the same time is impossible for the current machine that I had never seen. It would be best, if the company provided with at least 3-4 cores to ensure that 2 guests and the host would run without error. 



I can not run both guests, since they aren't built yet on my laptop.


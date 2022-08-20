# Scaled Up Web Infrastructure

![Image of a scaled up web infrastructure](3-scale_up.jpg)


## Description

This web infrastructure is a scaled up version of the infrastructure described [here](2-secured_and_monitored_web_infrastructure.md). In this version, all SPOFs have been removed and each of the major components (web server, application server, and database servers) have been moved to separate GNU/Linux servers. The SSL protection isn't terminated at the load-balancer and each server's network is protected with a firewall and they're also monitored.

## Specifics About This Infrastructure

+ The addition of a firewall between each server.<br/>This protects each and every server from unwanted and unauthorized users rather than protecting a single server.

## Issues With This Infrastructure

+ High maintenance costs.<br/>Moving each of the major components to its own server, means that more servers would have to be bought and the energy consumption will increase along with the introduction of new servers. More funds will have to be used to buy the servers and pay for the energy consumption needed to keep the all servers (including the new and old ones) running.


## Recommendations

+ Use a load-balancer to balance the traffic between the servers.<br/>This will reduce the energy consumption and the load on the servers.

## References

+ [AWS Amazon](https://aws.amazon.com/blogs/architecture/scale-your-web-application-one-step-at-a-time/)
+ [AWS Web Services](https://aws.amazon.com/web-services/)
+ [AWS Web Services Architecture](https://aws.amazon.com/web-services/architecture/)
+ [AWS Web Services Architecture - Scaling](https://aws.amazon.com/web-services/architecture/scaling/)
+ [AWS Web Services Architecture - Security](https://aws.amazon.com/web-services/architecture/security/)
+ [AWS Web Services Architecture - Monitoring](https://aws.amazon.com/web-services/architecture/monitoring/)
+ [AWS Web Services Architecture - Load Balancing](https://aws.amazon.com/web-services/architecture/load-balancing/)
+ [AWS Web Services Architecture - Application Load Balancing](https://aws.amazon.com/web-services/architecture/application-load-balancing/)
+ [AWS Web Services Architecture - Elastic Load Balancing](https://aws.amazon.com/web-services/architecture/elastic-load-balancing/)

## Conclusions

+ The web infrastructure is scaled up.
+ The web infrastructure is secured.
+ The web infrastructure is monitored.

## Copyright

© 2022 by [Tijani Mukhtar Akande](https://linkedin.com/in/tijanimukhtarakande).




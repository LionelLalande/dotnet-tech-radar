---
title: "Ocelot"
ring: trial
quadrant: languages-and-frameworks
tags: ["library","web","gateway"]
--- 
Ocelot is an API Gateway. The project is aimed at people using .NET running a micro services / service orientated architecture that need a unified point of entry into their system. In particular I want easy integration with IdentityServer reference and bearer tokens.  reference tokens. Ocelot is a bunch of middlewares in a specific order. Ocelot manipulates the HttpRequest object into a state specified by its configuration until it reaches a request builder middleware where it creates a HttpRequestMessage object which is used to make a request to a downstream service. The middleware that makes the request is the last thing in the Ocelot pipeline. It does not call the next middleware. The response from the downstream service is stored in a per request scoped repository and retrived as the requests goes back up the Ocelot pipeline. There is a piece of middleware that maps the HttpResponseMessage onto the HttpResponse object and that is returned to the client. That is basically it with a bunch of other features.

- Documentation: https://ocelot.readthedocs.io/en/latest/
- Source: https://github.com/ThreeMammals/Ocelot
- NuGet: https://www.nuget.org/packages/Ocelot



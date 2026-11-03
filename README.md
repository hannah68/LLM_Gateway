# LLM_Gateway
A multi-tenant LLM gateway that connects applications to LLM providers, providing centralised control over access, usage, and costs

## Overview
When an organisation has multiple AI applications, each application may need to independently handle concerns such as authentication, rate limiting and usage tracking. Normally, these applications can send requests directly to LLM providers, making it harder to centrally understand and control usage across them. An LLM gateway sits between the applications and LLM providers and centralises these shared concerns. This gives the organisation better visibility and control over which applications are making requests, how much they are using, and how much they cost.

## Project Status
The project is currently in the initial system design and planning phase, defining requirements, architecture, and key design decisions before implementation begins.

## Documentation
Design documentation will be added in `docs/design.md`.

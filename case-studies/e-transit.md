# e-Transit — Smart Transit Ecosystem

<small>Classification: Delivery-planning simulation · Role: Scrum Delivery Planning · Planning window: 2 weeks</small>

## Overview

e-Transit is a simulated contactless transit-payment and mobile point-of-sale concept. The planning scenario focuses on a journey where connectivity may be unreliable and where payment records must later be reconciled.

This is a delivery-planning exercise, not a live payment product or a deployed transit service.

## Objective

Practise defining a small, time-boxed Scrum delivery plan and making functional expectations and non-functional requirements visible before implementation.

## Planning focus

- Defined a two-week Scrum planning window.
- Considered an offline-capable mobile POS workflow at a conceptual level.
- Identified the need to retain transaction records when connectivity is unavailable and reconcile them when connectivity returns.
- Documented a tap-to-feedback latency target of **under 400 ms** as a proposed non-functional requirement.
- Modelled an end-of-day reconciliation scenario in which a two-hour manual process could be reduced to under one minute.

## Targets versus results

- **Under 400 ms** is a planned latency target; it is not a measured result from a working application.
- **Two hours to under one minute** is a modelled scenario used to discuss a possible workflow benefit; it was not measured in a live transport or payment environment.

## Project-management work

The simulation emphasises sprint goal definition, backlog slicing, acceptance criteria, dependency awareness, offline-use risks, and reconciliation requirements.

## Limitations

No payment gateway, card reader, transit operator, banking service, or production POS system was integrated or deployed. No real transaction data or verified performance measurements are included.

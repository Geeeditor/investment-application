# Overview

## Context

Investify is an application built to sell promising business oportunites by allowing investors and seed finders connect, interact and close deals in the event of the satisfaction of both parties with the terms of the published seed funding advertisment.

## Problem statment

This inital implmentation is using nextJs to build a full-stack application, for starters, users of investify will be able to create a profile as an investor or seed finder.

Seed finders should be able to publish proposals and investors should be able to reach out to seed finders via published advertisment.

## User need

The seed finder need is to login, verify kyc status, publish a request for seed funding and track the status of published seed funding advertisment.

and

investors need is to login, verify kyc status, browse through published seed-funding ads and connect with the users look for seed funding.

## Goals

This tech-doc is only created to make the MVP with inital feature for the web app.

### User Flow

The user signs up as either a seed finder or an investor.

#### SIGNING UP AS A USER LOOK FOR AN INVESTOR

The user verify's kyc status and publishes a proposal for seed funding, stating clearly his/her terms in the published proposal.

#### SIGNING UP AS A USER LOOKING TO FUND A BUSINESS

The user can login with already created profile to view published seed funding advertisment, in the event of finding a promising published seed funiding advertisment a process to close the deal is initiated.

#### PROCESS OF CLOSING THE DEAL

1. Investors accepts the terms of the published ads with a click of a button.
2. A meeting is scheduled using calendaily which notifys the ads publisher.
3. The parties gets to converse through a secure link (Method yet to be decided).
4. A form for uploading final document which will be reviewed by the investor is initiated.
5. SUCCESS✅✅🚀

## Technical implementation

Depending on the scope and nature of your proposal, consider also addressing: Reliability, Maintainability, Scalability, Observability, Developer Experience, Documentation.

### Datebase

YET TO BE DECIDED

### Backend

YET TO BE DEDICED (BUT BASIC LOGIN SYSTEM COULD BE SIMULATED WITH CLERK AUTH)

### Frontend

The frontend of our application will be developed using Next.js, React, and Tailwind CSS.

## Success Criteria

1. Both user must compulsorily have a verified KYC status.
2. Both user can login anytime .
3. Seed-finders can publish a proposal and investors can view content of the proposal.
4. Investors can reject poor documents quality.
5. Both parties can report an account for breaking investify community rules and regulations.
6. Both parties can delete their profile if need be.
7. Both users can leave a rating experience which is used as a metric for future post from the seed-finder or credibilty of the investors.

## Risks

What if the user lost the data?
what if the user identity and information are became public?
what if the web app does not accept new users?
what if data are leaked?

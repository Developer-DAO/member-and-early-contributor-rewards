# Snapshot Votes & POAP Holders

## Snapshot Votes

Snapshot Votes were retrieved using `graphql`.

### Proposal 1

**Proposal Link:** https://snapshot.org/#/devdao.eth/proposal/QmdZQD8h28PiWwwsdJo5mD2DBdC7BvYzrktmbsMoP4AcP6

GraphQL Link: https://hub.snapshot.org/graphql?operationName=Votes&query=query%20Votes%20%7B%0A%20%20votes%20(%0A%20%20%20%20first%3A%201000%0A%20%20%20%20skip%3A%200%0A%20%20%20%20where%3A%20%7B%0A%20%20%20%20%20%20proposal%3A%20%22QmdZQD8h28PiWwwsdJo5mD2DBdC7BvYzrktmbsMoP4AcP6%22%0A%20%20%20%20%7D%0A%20%20%20%20orderBy%3A%20%22created%22%2C%0A%20%20%20%20orderDirection%3A%20desc%0A%20%20)%20%7B%0A%20%20%20%20voter%0A%20%20%7D%0A%7D%0A

**Eligible Addresses:** 443

### Proposal 2

**Proposal Link:** https://snapshot.org/#/devdao.eth/proposal/0x52fc76fe5865cf038b89b8c6ef78b6e691c0ab9c2b1228b84b0813b7832ce369

GraphQL Link: https://hub.snapshot.org/graphql?operationName=Votes&query=query%20Votes%20%7B%0A%20%20votes%20(%0A%20%20%20%20first%3A%201000%0A%20%20%20%20skip%3A%200%0A%20%20%20%20where%3A%20%7B%0A%20%20%20%20%20%20proposal%3A%20%220x52fc76fe5865cf038b89b8c6ef78b6e691c0ab9c2b1228b84b0813b7832ce369%22%0A%20%20%20%20%7D%0A%20%20%20%20orderBy%3A%20%22created%22%2C%0A%20%20%20%20orderDirection%3A%20desc%0A%20%20)%20%7B%0A%20%20%20%20voter%0A%20%20%7D%0A%7D%0A

**Eligible Addresses:** 600

## POAP Holders

There were four POAPs taking place before Season 0 that are eligible for additional tokens. Each event's attendees were retrieved on the `event` page on POAP's website.

### POAP 1

**Title:** Developer DAO - Town Hall - October 8 2021

**Event Link:** https://poap.gallery/event/9944

**Eligible Addresses:** 45

### POAP 2

**Title:** Developer DAO - Town Hall - October 15 2021

**Event Link:** https://poap.gallery/event/10630

**Eligible Addresses:** 34

### POAP 3

**Title:** Developer DAO - Town Hall - October 29 2021

**Event Link:** https://poap.gallery/event/12096

**Eligible Addresses:** 73

### POAP 4

**Title:** Developer DAO - Town Hall - November 5 2021

**Event Link:** https://poap.gallery/event/12824

**Eligible Addresses:** 163

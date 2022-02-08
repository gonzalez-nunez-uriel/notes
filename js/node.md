# Understading Node

## Context

At first I learned how to use Node from tutorials and guides. This lead to a quick start up but set me up to failure with any project of nontrivial complexity. After passing through tutorial-hell, I finally gave up and read some of the official docs. Node is surprisingly well documented - but they still need a lot of polishing. I went down the rabit hole and eded un in the Official Design Overview of libuv. Now I want to learn Node with the level of detail as the design overview of libuv. This document serves that purpose.

## Node Components

Node is event-driven and it has an event queue, a job queue, and it mocks many of the web APIs exposed by browsers.

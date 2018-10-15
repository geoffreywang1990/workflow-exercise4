# Exploring webhooks

[Webhooks](https://developer.github.com/webhooks/) are GitHub's notification system for events that occur. This repo helps you explore how these are delivered. 

### See it in action

1. In this repository, generate some events by performing actions, like opening an issue for example.
1. This repository is connected to this server: https://smee.io/DLKerAbD9NzU5KAd
1. Examine the webhooks that get delivered. 

### Implement it

1. Fork this repository. 
1. Navigate to the repository Settings > Webhooks > Add a webhook
1. Generate a new channel by visiting smee.io and click on Start new channel. Copy the URL.
1. Paste your unique SMEE URL into the Payload URL field.
1. For Content Type, select `application/json`.
1. For the events that are sent, select: Send me everything
1. Add the webhook. GitHub automatically sends a ping. Visit your SMEE url to see it. 
1. Generate events by taking different actions in your GitHub repository like: opening issues, closing issues, creating branches, creating commits, opening PRs.

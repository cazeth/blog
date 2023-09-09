---
layout: ../../layouts/PostLayout.astro
title: XMTP
date: '2023-07-26'
tags: ['messaging','XMTP']
summary: Real-time text messaging has room for improvement.
images: []
---

Real-time chat messaging - what everyone does on WhatsApp, Messenger, WeChat, Signal, and other apps - is a technology with much room for improvement. That's because these apps are unnecessarily siloed. I cannot send a message from WhatsApp to WeChat. I have no fewer than five apps primarily used for one-to-one messaging (not counting group chat) and I can't delete a single one, because different contacts use different apps. This makes real-time chat feel primitive compared to email. It's easy for a Gmail user to email an Outlook user, but chat lacks this interoperability.

I don't expect that the incumbent apps will wake up one crisp spring morning and decide to collaborate to provide this. Although it would be a product improvement, the user network is a key resource to any chat app. They would hardly risk a user outflow by allowing users to communicate within their network through other apps.

A better approach is to build the similarities that the apps share, sending messages within a user network, as an open-source protocol. The differences that users want, such as different UXs and encryption levels, exist in applications on top. Like email but for chat.

Enter XMTP, which I've been using for chat. It's an open-source protocol for text communication. Unlike email, it works in real-time. It's also easier to switch applications, so if you prefer a different application with maintained access to the same network, that's easy to do. Logging into a new application took me less than a minute. Different apps have different UXs but still work together.

The idea is to turn XMTP into a protocol that runs independently of any organization. This would mean that anyone who builds on the protocol can do so without being at the mercy of another team's permission. The organization behind XMTP is currently working on getting to full decentralization. Once that is achieved, the challenge is to maintain it. As apps try to carve out a competitive position for themselves by solving problems in the application layer, the ease of switching apps becomes harder to maintain.

I've mostly used converse.xyz, an intuitive chat application for iOS, similar to WhatsApp. If you're on XMTP (whichever application you prefer), drop me a message at hey.caz.eth to get in touch.

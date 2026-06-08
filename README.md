---
category: architecture
title: Notifications API — Architecture
description: Central API for sending customer and driver notifications.
related_teams:
  - notifications
---

# Notifications API

Central API for sending customer and driver notifications.

## Overview

`notifications-api` is a api owned by the Notifications team. It runs in production as a tier-high service.

## Dependencies

It talks to:
- `push-gateway`
- `email-service`
- `sms-gateway`
- `notification-prefs`

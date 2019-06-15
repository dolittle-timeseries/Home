---
title: Deployment
description: Describes how the general architecture is
keywords: TimeSeries
author: einari
weight: 2
---
As with any software, versioning and deployment are some of the hardest things
to get right and with a scaled out scenario with multiple physical locations and
multiple target nodes to run software on, this becomes even harder and is
very error prone if one has to do it manually.

When working with time series [data pipelines]({{< relref data >}}) and the pipelines
consist of multiple different [modules](/timeseries/modules) that go together and to
top it off with then multiple edge locations, this becomes very interesting.

With the [Dolittle platform](/platform) and the continuous improvement engine, all
this complexity goes away. This also applies for deploying time series modules, as
it is just another piece of software that needs to run somewhere. Working together
with our [edge](/edge) support, it has all been optimized to make this seamless for
the developer.

